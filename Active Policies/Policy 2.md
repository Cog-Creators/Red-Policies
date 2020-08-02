# Org Teams
## OVERVIEW
Currently, the security and management of the org is very fragile, having several owners, and several members with write permissions who are inactive. This makes both decision making and changes within the org and server very difficult, not to mention leaves the org vulnerable.
## GOALS
- Simplify the decision-making process.
- Simplify the recruiting of new org members.
- Improve security.
## SPECIFICATIONS
Going forward we change the org model to use the [principle of least privileges](https://en.wikipedia.org/wiki/Principle_of_least_privilege).
We will set some basic guidelines to follow which apply to all org members that would make org management easier.
## BREAKDOWN
### <ins>Defining Inactivity</ins>
#### QA
- If someone isn’t actively reviewing pull requests.
- If someone isn’t actively reviewing cog applications.
- If someone misses too many org meetings without a valid reason.
- If someone isn’t actively making pull requests (*This is optional*, for QA role the above points are what are important, and QA shouldn’t be looked down on for not opening pull requests).
#### Core Dev
- If someone isn’t actively closing issues.
- If someone isn’t actively making pull requests.
- If someone isn’t actively reviewing pull requests. (*This is optional*, for the core dev role the above points are what are important, and core devs shouldn’t be looked down on for not reviewing pull requests).
- If someone misses too many org meetings without a valid reason.
#### Support Team (Discord role)
- Not actively helping in support for 3 months.
#### Other Roles
- If someone misses too many org meetings without a valid reason.
- When a new role is proposed and voted into place by active org members, then their inactivity guidelines should be specified in this Policy.
### <ins>Member inactivity and inactive roles</ins>
- We will be creating 2 new teams in the org, [inactive](https://github.com/orgs/Cog-Creators/teams/inactive-org-members), and retired.
- If a member goes on break we would move them to the [inactive team](https://github.com/orgs/Cog-Creators/teams/inactive-org-members) in the org until they are back. The above would also apply to members who are considered inactive by the majority of the active org members.
- Once a member is back, their original role would be reinstated. If a member is inactive for a long enough period, they would be moved from [inactive](https://github.com/orgs/Cog-Creators/teams/inactive-org-members) to [retired](https://github.com/orgs/Cog-Creators/teams/retired-org-members).
- The [retired team](https://github.com/orgs/Cog-Creators/teams/retired-org-members) does not mean a member is no longer part of the org. Should that member wish to reactivate their role in the org, an org vote should be triggered. Each active org member at the time would be able to vote if the member should be made active, should the vote be a draw, the leader of the team that org member was in has the deciding vote, ideally the retired member would have shown some activity recently, opening pull requests, engaging issue and pull request threads, engaging in discord on development conversations.

**Note**: The above is only applicable when a member has been moved to the [retired team](https://github.com/orgs/Cog-Creators/teams/retired-org-members), should someone in the [inactive team](https://github.com/orgs/Cog-Creators/teams/inactive-org-members) ask to have their main role reinstated after coming back they are free to do so by asking their team lead.

**Inactive threshold**: <ins>Taking a break or 1 month of inactivity</ins><br />
**Retired threshold**: <ins>2 months in the inactive team</ins>

### <ins>Org member recruitment</ins>
- Going forward, we would vote on any new proposal, with the anyone in the team having the power to veto (reject) the acceptance of a new member being proposed to their team.
- Each **<ins>active</ins>** org member at the time would be able to vote on the member. Should the vote be a draw, the leader of the team the new org member is recruited for has the deciding vote.
- If an active org member disapproves of the new member, they should voice their concerns to the org before the vote taking place.

### <ins>Org privileges</ins>
- Only the leaders of the QA and core dev team should ever have access to **<ins>owner</ins>** permission to the org.
- Core devs should have **<ins>maintain</ins>** permission on all repositories.
- 3 active core devs should have **<ins>admin</ins>** permissions on all repos, this should be decided within the core dev team.
- QA should have **<ins>write</ins>** permissions on all repositories.
- QA should have **<ins>maintain</ins>** permission on the following repositories:
  - [Applications](https://github.com/Cog-Creators/Applications)
  - [cogsupport-cogs](https://github.com/Cog-Creators/cogsupport-cogs)
  - [cog-cookiecutter](https://github.com/Cog-Creators/cog-cookiecutter)
- Active org members outside of QA and Core devs should **<ins>never</ins>** have write access.

**Note**: Access to any other service we use (PyPi or Cogboard, for example) should be delegated as needed using the [principle of least privileges](https://en.wikipedia.org/wiki/Principle_of_least_privilege).

### <ins>Pull requests bypassing QA</ins>
- Pull requests should not bypass QA unless absolutely necessary. This should only be considered when there is no one available to help review it. When bypassed these pull requests should always be labeled with “QA: Bypassed”
- The only exceptions for these are the following:
  - Version bump pull requests
  - Changelogs (If there is a person who can help you out with this, it should be preferred over doing it on your own)
  - Hotfix after release (If there is a person who can help you out with this, it should be preferred over doing it on your own)
    - Only if reverting pull requests that caused the regression if it can be done safely
    - Identifying the root cause of the issue in reasonable time and making a pull requests 

**Note**: Based on rules use your best judgement, if there's no one who can help you reviewing at the time and it can't wait slap the QA bypassed label and merge it

### <ins>Org forced removal</ins>
- If there is a security concern, the user permissions should be restricted as soon as possible, QA and Core Dev leads should decide what the severity is and restrict the perms for this user.
- If there is a concern for this user being part of the org, then at that point an org vote should be called between both the [Core Dev](https://github.com/orgs/Cog-Creators/teams/core-developers) and [QA](https://github.com/orgs/Cog-Creators/teams/quality-assurance) teams, and a decision on whether the member in question should be removed from the org should be made. 
  - One or two members on each team should have team maintainer status in the event it is necessary to remove someone from their team when the Core Dev and QA leads are unavailable, to be decided by the team lead.

**Note**: Certain titles have general expectations for the position. A core dev is expected to close issues by making pull requests and close issues that are no longer applicable; QA is expected to review open pull requests and close pull requests that are no longer valid. However we recognize that everyone has their own strengths and preferences for the time they are volunteering to the project. Inactivity on the stated positional responsibilities and whether that translates to removal will be situational for each person. We are trusting the dev and QA teams to view each instance of this situation with consideration for the overall contributions of said person and whether they have been ignoring their duty to the project in general. However, it is strongly suggested that individuals spend some of their time on the positional expectations as a QA team and a dev team that continuously add new features will never get bug fixes, for example.