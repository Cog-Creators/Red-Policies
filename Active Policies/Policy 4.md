# QA
## OVERVIEW
Clarifying processes for QA moving forward.
## GOALS
- Outlining the duties of the lead QA role.
- Set out duties of QA duties.
- Set out QA recruitment.
## BREAKDOWN
### <ins>Assigning a Lead QA</ins>
Should a lead QA become inactive, the active org members would have a vote to have an acting QA take their place for the duration of the inactivity. If the QA with most votes decides to not become an acting lead, then another vote would be triggered with them no longer considered in the eligible QA pool.
Should the inactive QA trigger the retried timescale outlined on [policy 2](Policy%202.md), the acting lead will be elevated to the lead role.
**Note**: if the lead QA is taking a break, they are eligible to partake in the vote for choosing the acting lead.

### <ins>Lead QA duties</ins>
- Work with other team leaders to manage the org,
- Work with lead core dev to prioritize testing quality assurance of specific issues and pull request.
- Work with QA to prioritize repo reviews.
- Work with other QA to prioritize issues.
- Will manage the cog support server.
- Will manage the [cogboard](https://cogboard.red/).
- Will manage the [cogs.red](http://cogs.red/).

### <ins>QA duties</ins>
- Will triage new issues in the repo.
- Will test open pull requests in the repo.
- Will help the lead QA manage the cog support server and [cogboard](https://cogboard.red/) and [cogs.red](http://cogs.red/).
- Will review repo applications.

### <ins>Minimum Core QA</ins>
- There should always be a minimum of 3 QA, but we should make an effort to have at least 5 in multiple time zones (to ensure a wider availability during core dev working hours).
- As part of this policy, [Aika](https://github.com/aikaterna) should officially become the Lead QA.
- All current members of the [QA team](https://github.com/orgs/Cog-Creators/teams/quality-assurance) will have the chance to remain active as part of this policy if they voice the desire to do so, if no desire is voiced prior to the vote then they will be moved to the inactive team.
  - [Aika](https://github.com/aikaterna) expressed his desire to remain active.
  - [Draper](https://github.com/Drapersniper) expressed his desire to remain active.
  - [Flame](https://github.com/Flame442) expressed his desire to remain active.
  - [Jack](https://github.com/jack1142) expressed his desire to remain active.
  - [Trusty](https://github.com/TrustyJAID) expressed his desire to remain active.

### <ins>Reviewing pull requests</ins>
QA should do the following when reviewing a pull request:
- Have the pull request assigned to themselves.
- Complete the review ensuring the pull request follows PEP and uses internal utilities instead of having duplicate implementations, is fully compliant with i18n (translation support) and makes a clean and performant use of the config API.
- Request changes where needed or approve the pull request.
- Once the pull request is approved squash merge it.
  - As a general rule though, the reviewer should also merge the pull request they review. If they need a second pair of eyes, making a comment about it or something like that is absolutely fine of course, but other than that the pull request shouldn't be hanging after approval.
  - There are situations where pull request can be approved earlier, but can't be merged just yet for some reason (e.g. Red 3.4 breaking changes); in such situations, the pull request should be labeled as blocked and when the reason for blocking is no longer valid, it can be merged by anyone

