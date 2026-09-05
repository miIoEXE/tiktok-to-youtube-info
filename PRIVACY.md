# Privacy Policy

**TikTok to YouTube auto-poster**

Last updated: 4 September 2026

## What this app does

This app copies videos from a TikTok account to a YouTube channel that the same person
owns. When a new video appears on the connected TikTok profile, the app downloads it and
uploads it to the connected YouTube channel as a Short, reusing the original caption as the
title and description.

## What data the app accesses

The app asks for these Google account permissions:

| Permission | Why |
|---|---|
| `youtube.upload` | Uploads videos to the channel you connect |
| `youtube.readonly` | Reads your channel name and ID so the app can show which channel it is posting to |
| `openid`, `userinfo.email` | Identifies which Google account connected the channel |

The app requests no other permission. It does not read your YouTube comments, subscribers,
analytics, watch history, or any other Google service.

## What the app stores

When you connect a channel, the app stores:

- Your YouTube channel ID, channel name, and channel avatar URL
- The email address of the Google account you signed in with
- An OAuth refresh token, which lets the app upload without asking you to sign in again
- The TikTok handle you chose to mirror
- A list of TikTok video IDs already posted, so nothing is posted twice

## Where it is stored

On infrastructure controlled by the person who runs this app. There is no shared or central
database, and the operator is the only party with access.

## What is never collected

The app does not collect, transmit, sell, or share your personal data with any third party.
There is no analytics, no tracking, and no advertising. The only outbound connections it
makes are to TikTok, to read the profile and download videos, and to the YouTube Data API,
to upload them.

## Deleting your data

Two ways, and you can use either:

1. Revoke the app at https://myaccount.google.com/permissions, which invalidates the
   stored token immediately.
2. Ask the operator to disconnect the channel, which deletes the stored record.

## Retention

Tokens and channel records are kept only while a channel stays connected. Downloaded video
files are deleted from disk right after a successful upload.

## Google API Services User Data Policy

This app's use of information received from Google APIs follows the
[Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy),
including the Limited Use requirements.

## Contact

fjndjayy@gmail.com
