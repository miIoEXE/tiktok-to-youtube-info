# Ascend Connect

A personal automation that mirrors one TikTok account to one YouTube channel.

When a new video is posted on the connected TikTok profile, it downloads the clip and
uploads it to the connected YouTube channel as a Short, reusing the original caption as
the title and description.

## Google account permissions

The app requests four scopes and nothing else:

| Scope | Purpose |
|---|---|
| `youtube.upload` | Upload the video to the channel you connect |
| `youtube.readonly` | Read your channel name so the app can show which channel it posts to |
| `openid` | Identify the Google account |
| `userinfo.email` | Identify the Google account |

It does not read comments, subscribers, analytics, or watch history, and it touches no
other Google service.

## Privacy

See [PRIVACY.md](PRIVACY.md).

## Contact

fjndjayy@gmail.com
