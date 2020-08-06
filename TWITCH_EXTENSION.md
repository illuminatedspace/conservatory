Title: Twitch Extension
Subtitle: Notes on creating a Twitch Extension

Goal: Create the Headphones Buddy Twitch Extension
Headphones buddy is to try and create an extension where streamers and viewers can listen to the same music in an external channel from the stream recorded audio.

Features:
- Sign into a music provider like Spotify
- Be able to listen to same playlist as streamer for the stream
Stretch Goals:
- Sync songs
- Group listening
- Song requests
- Additional music providers: Pretzel?

# Steps
## Create a new extension
Loosely followed this at first: https://dev.twitch.tv/docs/extensions

Went to the developer page
https://dev.twitch.tv/console/extensions/27tpbph3dnhlbig6lixod6t3h76b1k/0.0.1/status

Most of the information seems to be editable after the fact. I envision I'll need a small video overlay component for signing in to whatever music service, and controling volume.
I don't think we'll need a panel for this. It makes more sense to have a video overlay component.

## Set up Twitch Developer Rig
https://dev.twitch.tv/docs/extensions/rig/

Set up the Project by selecting it from the drop down,
I had to install Node on the windows side of my machine because I'm developing using WSL
I can still change the code in the WSL env and continue to develop normally.

The directions fail to mention that you have to run backend and front end and then look at the desired view in the `Extension Views` tab.

To edit the code go into the html and add the script tags
