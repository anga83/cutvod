# cutvod

### Description

Download a portion of a Twitch VOD via Bash terminal script.

The user provides a Twitch VOD URL, a start time, and an end time or a duration, respectively. The script will first fetch the VOD's metadata to suggest a filename consisting of the Twitch usersname and the title of the VOD. Once the user enters start and end point, the script will download only the specified portion of the VOD.


### Dependencies

- [streamlink](https://streamlink.github.io/)
- [yt-dlp](https://github.com/yt-dlp/yt-dlp)
- [ffmpeg](https://ffmpeg.org/)
- [jq](https://stedolan.github.io/jq/)
<br />

- Bash environment with Bash in version >= 4.2

