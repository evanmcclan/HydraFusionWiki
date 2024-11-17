# HydraFusion Privacy Policy
## HydraFusion overview

HydraFusion is a moderation bot for Discord that allows server staff to carry out moderator actions pertaining to identifying, and actioning user alternate accounts (mute, kick, ban, view user information, etc.). HydraFusion keeps records of alternate accounts, performs automated actions on punishment evading accounts, posts detailed logs in logging channels, and sets up systems such as cases and evidence tracking for alternate accounts. The bot also includes a web dashboard that server administrators can log in to through Discord OAuth.

The bot's source code is available at https://github.com/evanmcclan/HydraFusion.

_You must request access from the owner as this repository is private_

## Stored data

When HydraFusion is used by a server, the following categories data can be stored by the bot. The specific categories of data saved for each server depends on how the server has configured HydraFusion.

- Recent messages and username/nickname changes of users engaged on the server
- Recent updated to profile avatar and banner
- Basic user information, moderator-entered text, and relevant message archives for infraction records
- A subset of previously held roles to be restored when a user rejoins
- Basic server details of the server using the bot
- A basic analysis of the user's diction and message history while on the server

Additionally, when a user logs in to the web dashboard the following types of data are stored:

- Basic Discord user information
- Time and originating IP address of the login for security audit purposes 

## Data retention
Unless otherwise specified, Data retention is indefinite until manually deleted by the server staff.
On Account Joining the Server:

- Account current username
- Account global nickname (tag)
- Account local nickname (server displayname)
- Account avatar hash (CDN cache)

While Account is a Member of the Server:

- Updates to account username
- Updates to global nickname (tag)
- Updates to local nickname (server displayname)
- Updates to local about-me (server biography)
- Updates to avatar hash (CDN)(global/local)
- Updates to current roles
- Cached message history (from last join or last account moderator action) [Deleted when case is deleted]
- Infraction record data is kept until the server stops using HydraFusion [Deleted when case is deleted or user is unlinked]
- User information for users logged in to the bot's web dashboard via Discord OAuth is stored as long as the server uses HydraFusion

After an Account Leads the Server:

- All data is retained until the case is deleted

## Data access and deletion requests

To request access to personal data stored about you, or to request its deletion, to the extent permitted by GDPR, please send an email to evanmcclan@gmail.com 
