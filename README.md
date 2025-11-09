# ban-management-Extension
The Ban Appeal System extension enables server administrators to manage bans across two linked servers: a main community server where users are banned from, and a dedicated appeal server where banned users can submit appeals. 
> 💡 **Built for the Zygnal Ecosystem — to download and use this extension, you must be part of the Zygnal Ecosystem.**  
> This extension (cog) is part of the **Zygnal Ecosystem** and is only available through its supported platforms.  
> You can use it with:  
> - The **[Discord Bot Framework](https://github.com/TheHolyOneZ/discord-bot-framework)** — ideal for developers who want full control and flexibility *(includes an integrated extension marketplace)*, or  
> - The **[ZygnalBot](https://zygnalbot.de)** — a prebuilt, plug-and-play Discord bot *(also includes an integrated extension marketplace)*.  
>
> Browse and install extensions at [zygnalbot.com/extension](https://zygnalbot.com/extension).  
> For help or community discussions, join us on Discord: [discord.gg/sgZnXca5ts](https://discord.gg/sgZnXca5ts)
# Ban Appeal System

## Overview
The Ban Appeal System creates a structured process for handling ban appeals across two Discord servers. It allows banned users to submit appeals with evidence and provides staff with tools to review and manage these appeals efficiently.

## Features
- **Dual-Server Setup**: Link a main community server with a dedicated appeal server
- **Automatic Detection**: Automatically detects banned users when they join the appeal server
- **Evidence Submission**: Users can submit appeals with text explanations and file attachments
- **Staff Review System**: Dedicated notification channel for staff to review pending appeals
- **One-Click Actions**: Approve or deny appeals with custom feedback to users
- **Automatic Unbanning**: Automatically unbans users when appeals are approved

## Setup Instructions
1. Use `!banappeal setup` to access the setup interface
2. Configure your community server and appeal server IDs
3. Set a notification channel where staff will receive new appeals
4. Test the system by having a banned user join the appeal server

## Commands
- `!banappeal` or `!ba` - Shows the main ban management panel
- `!banappeal setup` - Configure the ban appeal system

## Technical Details
- Appeals are stored in JSON format with timestamps and review information
- File attachments are supported up to 25MB per file
- Configuration is server-specific and persists across bot restarts
- Requires administrator permissions to configure

## Best Practices
- Create a dedicated appeal server with minimal channels
- Set clear rules about the appeal process in the appeal server
- Assign specific staff members to handle appeals
- Regularly review pending appeals to maintain good user experience
