# Distant
# Overview
The Distant Bot is designed to enrich user interaction within Discord servers by providing a seamless way to share media from popular social platforms directly into Discord channels. It supports Instagram Reels, TikTok videos, and Twitter posts. By utilizing direct links from ddinstagram, vxtiktok, and fxtwitter, the bot bypasses the need for users to leave Discord to view content, enhancing the user experience and engagement within the community.

## Features
- Ping Command: Quickly check if the bot is responsive and operational.
- Share Command: Share media from Instagram, TikTok, or Twitter directly into your Discord server by providing the post's link. The bot processes these links and returns a direct link to the video or post, viewable within Discord.
How It Works
The bot listens for specific slash commands issued within a Discord server:

- /ping: The bot responds with "Pong" and the username of the requester, confirming its active status.
- /share <url>: Users can share a media link from Instagram, TikTok, or Twitter. The bot then extracts the necessary identifiers from the URL, creates a direct link to the media, and posts it back into the channel.