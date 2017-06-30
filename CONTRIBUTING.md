# BIFFUD Corporate Contribution Guidelines

This document contains information of use to partners looking to
improve the BIFFUD's corporate documentation.  See [README.md](README.md)
for a sense of what this repository is handles.

## Submitting and Reviewing Documentation

This repository has a home on
[GitHub](https://github.com/BadIdeaFactory/corporate).  Please submit
[pull requests](https://help.github.com/articles/about-pull-requests/)
(PRs) there.

Please submit changes via pull request, even if you have direct commit
access to the repository.  The PR process allows us to get additional
eyes on change proposals and gives us all a chance for corporate
amusement.

Generally, the more controversial, complex or large a change, the more
opportunity people should have to comment on it.  That means it should
garner more comments/approvals or it means it should sit longer before
being merged.

PRs with meaningful changes will require a 50% or more vote from voting
partners.

### Branching and Branch Names

We do all development on lightweight branches, with each branch
encapsulating one logical changeset (that is, one group of related
commits).  Please try to keep changesets small and well-bounded: a
branch should usually be short-lived, and should be turned into a PR,
reviewed, and merged to `master` as soon as possible.  Keeping
branches short-lived reduces the likelihood of conflicts when it comes
time to merge them back into master.

When a branch is associated with an issue ticket, then the branch name
should start with the issue number and then give a very brief summary,
with hyphens as the separator, e.g.:

    871-fix-provider-risk-score

Everything after the issue number is just a reminder what the branch
addresses.  Sometimes a branch may address only part of an issue, and
that's fine: different branches can start with the same issue number,
as long as the summary following the issue number indicates what part
of the issue that particular branch addresses.

If there is no issue number associated with a branch, then don't start
the branch name with a number.

While there are no strict rules on how to summarize a branch's purpose
in its name, it may help to keep in mind some common starting words:
"`fix`", "`feature`", "`refactor`", "`remove`", "`improve`", and "`test`".

### Rebases and force-pushes

Force pushes (after a rebase or a `commit --amend`) are currently
allowed everywhere except the master branch.  This repository has master
as a "protected" branch, meaning force-pushes are disabled
automatically.  If you're working with someone else on a shared branch
you should talk with them before changing shared history.  We expect
force-pushing to mostly occur in active PR branches.

### Commit Messages

Please adhere
to [these guidelines](https://chris.beams.io/posts/git-commit/) for
each commit message.  The "Seven Rules" described in that post are:

1. Separate subject from body with a blank line
2. Limit the subject line to 50 characters
3. Capitalize the subject line
4. Do not end the subject line with a period
5. Use the imperative mood in the subject line
6. Wrap the body at 72 characters
7. Use the body to explain _what_ and _why_ vs. _how_

Think of the commit message as an introduction to the change.  A
reviewer will read the commit message right before reading the diff
itself, so the commit message's purpose is to put the reader in the
right frame of mind to understand the code change.

The reason for the short initial summary line is to support commands,
such as `git show-branch`, that list changes by showing just the first
line of each one's commit message.

### Indentation and Whitespace

Please use spaces, never tabs.  The file [.editorconfig](.editorconfig)
encodes these formatting conventions in a way that most text editors
can read.

### Licensing Your Contribution
The corporate is published under the
[MIT License](http://www.apache.org/licenses/).  It is important that
the codebase continue to be publishable under that license.  To make
that possible, here are some guidelines on including 3rd party content.

If you submit content that you wrote or that you have authority to submit
from your employer or institution, you give it to us under the MIT License.
If the material you submit is already licensed under a similarly permissive
license (BSD, ISC), you can tell us that and give it to us under that
license instead.

Please make the license of the contribution clear in your pull request.  Tell
us who wrote it, if that isn't just you.  If the code was written for
an employer, tell us that too.  Tell us what license applies to the
code, especially if it differs from the project's MIT license.

### Expunge Branches Once They Are Merged

Once a branch has been merged to `master`, please delete the branch.
You can do this via the GitHub PR management interface (it offers a
button to delete the branch, once the PR has been merged), or if
necessary you can do it from the command line:

    # Make sure you're not on the branch you want to delete.
    $ git branch | grep '^\* '
    * master

    # No output from this == up-to-date, nothing to fetch.
    $ git fetch --dry-run

    # Delete the branch locally, if necessary.
    $ git branch -d some-now-fully-merged-branch

    # Delete it upstream.
    $ git push origin --delete some-now-fully-merged-branch
