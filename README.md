# HydraFusion

A unique approach to detecting, tracking, and mitigating user evasion through alt accounts.

HydraFusion Bot is written in JavaScript for use with NodeJS.
InDev Node.js v20.18.0

## The Goal of HydraFusion
HydraFusion is being developed (privately for now) with large discord servers in mind.   
The intent of this bot is to provide large server moderators a tool that easily tracks users joining servers with multiple accounts. This bot will function to nexus when accounts belong to the same person and link them together. This bot will incorporate auto-moderation features that will encompass the follwoing
- Similarity detection between two user's profile photos using the Resemble & Rembrandt JS Libraries
- Similarity detection between two user;s profile handle, name, and about-me using RegEx
- Create a "Fusion Case" for linking multiple accounts together

In addition to these functions, the bot will systematically help with the following:
- Generating leads on new joining accounts and checking against current existing Fusion Cases
- Suggesting the creation of a new Fusion Case when a strong lead is generated
- Actioning of linked alt accounts when one account linked to a Fusion Case is actioned
- Recursive account actioning for new accounts lead linked to a Fusion Case (Ban Evade Detection)

## Setup Guide
Whoa there pal, this bot isnt quite ready for deployment. Run this bot in a local environment at your own risk.
**Requirements for start-up**
- Bot Token (Generate from Discord Development Portal)
- MongoDB Database (Minimum 1MB DataStore)
- RabbitMQ Partition (Minimum 1MBpS Volume Transfer) [Only required for cross server data share]
- Dedicated Environment (Larger servers will need more CPU available for bot processes)

You can contact me in Discord with the username: **Small.Fry** or via the [Combo Meal Discord Server](https://discord.gg/CrYSHNqjQw)
