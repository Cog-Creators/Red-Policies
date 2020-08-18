# Official Support Server (Server restructure)
## OVERVIEW
Restructure the server to better display the org members and project contributors.
## BREAKDOWN
- A new hoisted role called “Org Members” would be created. 
  - All active and [inactive members](https://github.com/orgs/Cog-Creators/teams/inactive-org-members) should be shown under this role.
  - [Retired members](https://github.com/orgs/Cog-Creators/teams/retired-org-members) would not be shown under this role.
  - Active and [inactive members](https://github.com/orgs/Cog-Creators/teams/inactive-org-members) should have different colours to more easily indicate to users which members are active.
- All active org members will have the same colour regardless of role within the org.
- All [inactive members](https://github.com/orgs/Cog-Creators/teams/inactive-org-members) will have the same colour regardless of role within the org.
- All [retired members](https://github.com/orgs/Cog-Creators/teams/retired-org-members) will have the same colour regardless of role within the org as long as they are part of the org.
- We should move toward proudly displaying people making active contributions to the server.
  - Red followed by Staff should be the top 2 hoisted roles
  - Org Members should be the 3rd hoisted role ([retired members](https://github.com/orgs/Cog-Creators/teams/retired-org-members) shouldn’t be hoisted here).
  - Support Squad members should be the 4th hoisted role.
  - [Contributor](https://github.com/Cog-Creators/Red-DiscordBot/graphs/contributors) should be the 5th hoisted role.
  - Cog Creator (V3 only) should be the 6h hoisted role.
  - [Translator](https://crowdin.com/project/red-discordbot/activity_stream) should be the 7th hoisted role.
    - Hoisting of this role is dependent on us being able to check users stats in Crowdin and seeing who has active contributions there and the number of contributions they have made.
    - This role would also be dynamic, meaning that it would be updated once a month (or another length of time), with current translators with active translations and if you don’t meet the bar you lose the role.
  - Patreon should be the 8th (or 7th) hoisted role.
  - [Retired members](https://github.com/orgs/Cog-Creators/teams/retired-org-members) should be the 9th (or 8th) hoisted role.
  - V2 Cog creators should no longer be hoisted.
  - If a member does not belong to any of the above, they would just be listed under the default hoist.

**Note**: Core Dev, QA roles should still exist but be made neutral in colour and all have the same colour, as the display of this role does provide useful information, however there should be no display distinction between them.