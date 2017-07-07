Bad Idea Factory Limited Liability Corporation
===================================================================

Contents:

1.  Official Operating Agreement
2.  Partnership
3.  Projects
4.  Money
5.  Governing Process
6.  Policies

---------------------------------------------------------------------
SECTION 1: 📚📚📚 Official Operating Agreement 📚📚📚
---------------------------------------------------------------------
- [ ] Company term
- [ ] Continuance of company
- [ ] Rickroll
- [ ] Game of Mario Party 3 before legal arbitration between members

---------------------------------------------------------------------
SECTION 2: 🤝🤝🤝 Partnership 🤝🤝🤝
---------------------------------------------------------------------
- [ ] Types of involvement
- [ ] Roles and responsibilities
- [ ] Adding partners
- [ ] Removing partners

---------------------------------------------------------------------
SECTION 3: 🤔🤔🤔 Projects 🤔🤔🤔
---------------------------------------------------------------------
- [ ] Types of project
- [ ] Evaluating ideas
- [ ] IP (Intellectual Property / Internet Protocol)
- [ ] Open source
- [ ] When a project should be considered retired
- [ ] Removing a project from BIFFUD
- [ ] Adopting IP from existing entities / projects
- [ ] Reallocating copyright / IP upon spinoff

---------------------------------------------------------------------
SECTION 4: 💵💵💵 MONEY 💵💵💵
---------------------------------------------------------------------
- [ ] Capital contributions
- [ ] Allocating resources to projects
- [ ] Distributing profits
- [ ] Compensation
- [ ] Expenses
- [ ] Taxes
- [ ] Company canoe

---------------------------------------------------------------------
SECTION 5: 🗣🗣🗣 Governing Process 🗣🗣🗣
---------------------------------------------------------------------
- [x] Types of decision
- [x] Records and documentation
- [x] Mechanisms for deliberation
  - [x] ... On GitHub
  - [x] ... On Slack
  - [x] ... Plotting Sessions
- [x] Use of emoji

### Deliberation Processes

#### Slack
Decisions made over slack are intended to be short term decisions that
do not require intense deliberation or buy-in from the majority of the
Hive Mind.

1. A single pinned message is created, posing the entire question up
for vote.

2. Discussion happens entirely in a threaded response to the question.

3. Voting is performed using emoji in response to a single pinned message
that poses the entire content up for vote. Positive Emoji are used for a yes
vote, Negative Emoji are used for a no vote, and Ambiguous Emoji are used
for an abstention.

4. The results of a vote are tallied and reported back inside of the thread
in addition to being catalogued in `/votes/slack` as described later in this
document.


#### Plotting Session
Plotting sessions are agenda driven and require a Quorum to occur.  They
are led by the chair (as determined by the chain of command).

The Hive Mind will use Robert's Rules of Order to run plotting sessions
in an orderly and Robertly fashion.

If the plotting session is held virtually, video should be enabled for all
attendants where bandwidth allows.

If the virtual platform enables costumes or static overlays on top of avatars,
the meeting chairperson is to select an overlay to represent the Greek Chorus.
This overlay should be selected to maximally hide the faces of the Greek Chorus.

Each Corporate Overlord must wear overlays depicting wealth.  For example this
could be a monacle, crown, or in the distant future a laser that fires precious
gems.

If the virtual platform enables emoji or other forms of visual flair, votes are
to be calcualted using the platform's equivalent of a thumbs up or thumbs down
emoji. If directly equivalent emoji reactions do not exist on the platform, the
meeting chair may select alternative emoji to represent positive and negative votes.

If there is no support for emoji or appropriate effects the Corporate Overlords must
instead fabricate physical emoji on sticks for both positive and negative votes.  If an
overlord is unable to fabricate an emoji, they must draw a shaded thumbs up and a
thumbs down on their hand using a marker or pen.  If they don't have hands or a means
to draw, they can work with the meeting chair to determine an appropriate alternative.

A verbal vote may only be taken if the above methods are not reasonably possible to
follow in a meeting.


#### GitHub
Decisions made purely on GitHub are generally intended to either be interim
decisions that require a Plotting Session to finalize, or decisions related
to the organization, documentation, or beurocracy of `/corporate`.

Regardless of whether or not a decision can be finalized in GitHub, the method
of deliberation is the same.

1. A branch (Corporate Overlord) or fork (Member) is created from `corporate`
against `master` or an appropriate sub-branch.

2. The appropriate template file is used in the appropriate subdirectory to
create the relevant request or proposed addition.

3. A Pull Request is made against the relevant branch, with commit comments
written using the standards described in `CONTRIBUTING.md`

4. Corporate Overlords are automatically asked to review the Pull Request.

5. Corporate Overlords vote using GitHub's review feature.  Approval is a yes
vote, Rejection is a no vote, and Comments are used to request more information
or changes.  Active abstention should be communicated via a comment review.

6. If a plotting session is not required, a vote is considered passed if there
are enough approval votes as determined by this document based on the decision
type.  At this point the passage should be noted by the Overmind or the Secretary
of Lore and the relevant action based on the decision can be undertaken.

7. If a plotting session is required, the votes are simply an indication of favor
and depending on the decision type may indicate temporary approval.

A vote can be changed at any time until the decision has been determined to be final.

Votes during plotting sessions override votes shown on Pull Requests, even if the same
Corporate Overlord voted differently in both places.


#### GitHub -> Plotting Session
Some decisions are explored on GitHub but ultimately culminate in a live vote during
a Plotting Session.  The process is the same as described in GitHub, but votes for
open tickets are either scheduled into plotting sessions in advance or raised via
a motion during the New Business portion of an agenda.


### Voting Decisions
The following decisions will require a formal input from the Hive Mind.


- **Adding projects:** GitHub -> Plotting Session, 30% vote for preliminary approval,
70% vote for final approval.  Applications are submitted to `/projects` using the
`/documents/project.md` template.  A project representative should attempt to attend
the relevant Plotting Session to answer questions.

- **Updating projects:** GitHub -> Plotting Session, 30% vote for preliminary approval,
70% vote for final approval.  The relevant project file should be updated via Pull Request
in `/projects`.

- **Removing projects:** GitHub -> Plotting Session, 30% vote for preliminary approval,
70% vote for final approval.  Removing a project from BIFFUD involves a Pull Request to place
its `.md` into `/projects/archive` and to update the file appropriately.

- **Adding Corporate Overlords:** Plotting Session, 70% vote.
- **Removing Corporate Overlords:** Plotting Session, 70% vote.
- **Changing section 1 of `operating.md` OR changing this bullet:** GitHub -> Plotting Session, 100% vote.
- **Changing any other section of `operating.md`:** GitHub -> Plotting Session, 70% vote.
- **Approving expenses:** GitHub -> Plotting Session, 50% preliminary approval, 70% final approval.
Applications are submitted to `/expenses` using the `/documents/expense.md` template.
- **Canceling tax reimbursement:** Plotting Session, 70% vote.
- **Creating one-time capital contributions from the Hive Mind:** Plotting Session, 100% vote.
- **Creating one-time capital dispersements to the Hive Mind:** Plotting Session, 70% vote.
- **Electing Corporate Overlords to named positions:** GitHub -> Plotting Session, 10% preliminary,
Democratic Vote. Election applications are submitted to `/elections` using the `/documents/election.md`
template. If a candidate gets 10% approval their application is merged.  Candidates must be locked in
a full day before the election is held.
- **Making modifications to `CONTRIBUTING.md`:** GitHub -> Plotting Session, 50% vote.
- **Making modifications to `/corporate`:** GitHub, vote requirements
based on change type, determined by `CONTRIBUTING.md`.
- **Approving minutes:** GitHub, 50% vote. Pull Request made to `/meetings` using
the `documents/meeting.md` template.
- **Posting to official social media channels with `- HM` or `- CO`: Slack, 30%

Here's a summary table:

| Decision          | Vote      | Deliberation |
| ----------------- | :-------: | ------------ |
| + project         | 30% / 70% | GH -> Pl Ssn |
| ~ project         | 30% / 70% | GH -> Pl Ssn |
| - project         | 30% / 70% | GH -> Pl Ssn |
| + overlord        | 70%       | Plotting Ssn |
| - overlord        | 70%       | Plotting Ssn |
| ~ section 1       | 100%      | GH -> Pl Ssn |
| ~ section X       | 70%       | GH -> Pl Ssn |
| + expenses        | 50% / 70% | GH -> Pl Ssn |
| - taxes           | 70%       | Plotting Ssn |
| + capital         | 100%      | Plotting Ssn |
| + dispersement    | 70%       | Plotting Ssn |
| -> position       | 50%       | Plotting Ssn |
| ~ contributing.md | 50%       | GH -> Pl Ssn |
| ~ /corporate      | !!!       | GitHub       |
| + minutes         | 50%       | GitHub       |
| + social          | 30%       | Slack        |


### Delegated Decisions

This has to be fleshed out, but basically what kinds of things can elected
titles do.  For instance...

- Beastmaster can decide if a preliminary approval
of a project should translate into full blown onboarding.

- Secretary of Lore can potentially reject a Pull Request that does not meet
commit message standards even if it is otherwise approved.  (Note that the
President can override that rejection, you know, to prevent any funny
business.)

### Records and Documentation

Deliberation should always be performed using the guidelines dictated by
the associated deliberation process.  Minutes should be taken during Plotting
Sessions, and it is the responsibility of the Secretary of Lore to take notes
to reflect attendance, decisions made, meaningful discussion, and vote counts.

Decisions made on Slack should be properly memorialized as described in the
deliberation process.

These minutes make up the corporate records.  Documentation structure and
organization should be performed as outlined in `CONTRIBUTING.md`. Furthermore,
every commit message in `corporate` should be written using the standards and
guidelines outlined in `CONTRIBUTING.md`.

The Secretary of Lore is responsible for overseeing commits and being a stickler
for quality.

---------------------------------------------------------------------
SECTION 6: 📜📜📜 Policies 📜📜📜
---------------------------------------------------------------------
- [ ] Annual algorithmic board meeting
- [ ] Emoji on sticks
- [ ] Pronunciation of BIFFUD
- [ ] Pun rating system applied in minutes


