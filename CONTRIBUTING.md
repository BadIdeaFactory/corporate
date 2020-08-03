# BIFFUD Corporate Contribution Guidelines

This document contains information of use to partners looking to
improve the BIFFUD's corporate documentation.  See [README.md](README.md)
for a sense of the purpose of this repository.

You should also look at the [Corporate Bylaws](documents/operating.md)
which lays out some of the processes around the repository.

## Baseline Concepts
### Submitting and Reviewing Documentation

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

Note: Some types of PR require a vote by the corporate overlords. for instance
approval of minutes or project applications.  Others can be merged by the
Secretary of Code, Overmind, or Undermind.

### Issues

Issues are used for keeping track of corporate tasks as well as for tracking
various types of application.

Applications covered by issues:

- Project applications
- Corporate Overlord applications
- Requested budget changes
- Expense requests

More detail for each of these tasks is provided later in this document.

### Wiki

The wiki is the shared knowledge base of BIFFUD.  It provides a public index
of projects and BIFFUD overlords as well as information about how to go about
using the various tools that we use as an organization.

The repository represents reality and canonical truth.  The wiki should be
seen as a helpful, lucid dream.

### Branching and Branch Names
We will have a few "perma" branches that will always exist and
are maintained by the appropriate elected role:

- order: this branch is for serious business such as contracts and legal
documentation.  It is managed by the Overmind and Undermind.
- code: this branch is for repo infrastructure and changes to code related documentation.  It is managed by the Secretary of Code.
- treasure: this branch is for tracking budgets and expenses.  It is managed
by the Treasure Goblin.
- lore: this branch is for tracking documentation and minutes.  It is managed
by the Keeper of Lore.
- projects: this branch is for keeping track of projects and relevant
documents or agreements.  It is managed by the Beastmaster.
- popularity: this branch is for keeping track of communications and marketing
materials such as emoji, logos, and catch phrases.  It is managed by The
Popular One.
- chaos: this branch is for chaos.  It will hopefully never be merged.  It is
managed by all of the corporate overlords.

There shouldn't be any other branches than these.  If something doesn't fit
into any of these branches, open an issue.

### Rebases and force-pushes

REBASES AND FORCE PUSHES ON ANY BRANCH ARE FOR THE WEAK.  LIVE WITH YOUR
MISTAKES FOR THE WORLD TO SEE INDEFINITELY.

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
The corporate is published under the [Apache License, Version 2.0](http://www.apache.org/licenses/).
It is important that the codebase continue to be publishable under that
license.  To make that possible, here are some guidelines on including 3rd
party content.

If you submit content that you wrote or that you have authority to submit
from your employer or institution, you give it to us under the Apache License,
Version 2.0. If the material you submit is already licensed under a similarly
permissive license (BSD, ISC), you can tell us that and give it to us under
that license instead.

Please make the license of the contribution clear in your pull request.  Tell
us who wrote it, if that isn't just you.  If the code was written for
an employer, tell us that too.  Tell us what license applies to the
code, especially if it differs from the project's Apache License, Version 2.0.

### Developer's Certificate of Origin 1.1

By making a contribution to this project, I certify that:

(a) The contribution was created in whole or in part by me and I have the right to submit it under the open source license indicated in the file; or

(b) The contribution is based upon previous work that, to the best of my knowledge, is covered under an appropriate open source license and I have the right under that license to
submit that work with modifications, whether created in whole or in part by me, under the same open source license (unless I am permitted to submit under a different license), as Indicated in the file; or

(c) The contribution was provided directly to me by some other person who certified (a), (b) or (c) and I have not modified it.

(d) I understand and agree that this project and the contribution are public and that a record of the contribution (including all personal information I submit with it, including my sign-off) is maintained indefinitely and may be redistributed consistent with this project or the open source license(s) involved.

### Elections
People running for a position should commit an application (found at [applications/elections/general_candidate.md](applications/elections/general_candidate.md)) to the `records/elections/candidates/[date]/[lastname]_[firstname].md`

As described in operating.md, the Issue must be opened 24 hours before the election is held.

## How do I (general) ...
### Apply to add a project to BIFFUD?
1. [Create an issue](https://github.com/BadIdeaFactory/corporate/issues/new?template=project_issue_template.md) and fill out the form
2. Add a title in the form [PROJECT NAME] Project Application
3. Label it a project application using the Labels tag on the right side
4. Submit!

### Apply to be a Corporate Overlord?
1. [Create an issue](https://github.com/BadIdeaFactory/corporate/issues/new?template=overlord_issue_template.md) and fill out the form
2. Add a title in the form [YOUR NAME] Corporate Overlord Application
3. Label it a corporate overlord application using the Labels tag on the right side
4. Submit! (and Profit?)

### Apply for an elected position?
1. [Create an issue](https://github.com/BadIdeaFactory/corporate/issues/new?template=elected_issue_template.md) and fill out the form
2. Add a title in the form [YOUR NAME] Elected Position Application
3. Label it a elected position using the Labels tag on the right side
4. Submit!

### Know when the next Plotting Session will be?
I don't know - I'm not your secretary. Check the slack or [BIFFUD Calendar](https://calendar.google.com/calendar/embed?src=2i1b09fb2hquvsin3jkiljprc8%40group.calendar.google.com&mode=agenda). It may or may not be right.

### Submit a new poem?
[Create a new file](https://github.com/BadIdeaFactory/corporate/tree/master/poems) in poems. Wait for mockery or praise or most likely no response.

### Create a new contract with someone?
Hire a lawyer? Or:
1. [Create an issue](https://github.com/BadIdeaFactory/corporate/issues/new?template=contract_issue_template.md) and fill out the form
2. Add a title in the form [Company or Person NAME] Contract Application
3. Label it a contract using the Labels tag on the right side
4. Submit! And send it to them for their review, probably

### View the next meeting's agenda?
It should be in the [master agenda](https://github.com/BadIdeaFactory/corporate/tree/master/records/agendas) but it probably isn't (yet). Check [order agenda](https://github.com/BadIdeaFactory/corporate/tree/order/records/agendas)

### Add something to the next meeting's agenda?
There will probably be a template for this at some point but for now I recommend whining loudly in the #biffud-corporate slack

### View meeting minutes?
It should be in the [master minutes](https://github.com/BadIdeaFactory/corporate/tree/master/records/minutes) but it probably isn't (yet). Check [order minutes](https://github.com/BadIdeaFactory/corporate/tree/master/records/minutes)

### Request a paid expense?
1. [Create an issue](https://github.com/BadIdeaFactory/corporate/issues/new) and input the basic information, including the project, request reason, cost, etc
2. Add a title in the form [Project] Expense Request
3. Label it a expense request using the Labels tag on the right side
4. Submit!

### Make a modification to a project budget?

## How do I (Overmind)...
Use the [Tome of Knowledge: Overmind](https://github.com/BadIdeaFactory/corporate/wiki/Tome-of-Knowledge:-Overmind)

## How do I (Keeper of Lore)...
Use the [Tome of Knowledge: Keeper of Lore](https://github.com/BadIdeaFactory/corporate/wiki/Tome-of-Knowledge:-Keeper-of-Lore)

## How do I (Beastmaster)...
Use the [Tome of Knowledge: Beastmaster](https://github.com/BadIdeaFactory/corporate/wiki/Tome-of-Knowledge:-Beastmaster)
