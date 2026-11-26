# rsg-merlion privacy policy

_Last updated: 26 November 2026_

rsg-merlion is a Reddit Developer Platform (Devvit) app. When a subreddit's moderators install it, it copies each new post in that subreddit to a Telegram group or channel that those moderators choose.

## What the app processes

When someone submits a post in a subreddit that uses the app, Reddit sends the app that post's details. The app uses:

- the post's title, body text, flair, permalink, and link or image URLs;
- whether the post is marked NSFW or spoiler;
- the author's Reddit username.

The app does not process private messages, votes, IP addresses, email addresses, or any other account information.

## Where it goes

- **Telegram.** The app sends the post's title, author username, flair, the first 700 characters of the body, image URLs, link URL and permalink to the Telegram group or channel the moderators set up, using Telegram's Bot API (`api.telegram.org`). Anyone who can see that group or channel can see the message. Telegram's own [privacy policy](https://telegram.org/privacy) applies to it there.
- **Logs.** The app logs each post submission it receives and each message it sends to Telegram, to help diagnose failed messages. Reddit stores and retains these logs as part of the Developer Platform, under Reddit's [privacy policy](https://www.reddit.com/policies/privacy-policy).
- **Storage.** The app stores the IDs of the posts it has sent in Reddit's Developer Platform storage for 24 hours, so a post isn't sent twice. It stores no other data.

The app does not sell data, does not use it for advertising, and does not send it anywhere other than the places listed above.

## Removing content

The app copies a post when it's submitted. Editing or deleting the post on Reddit afterwards doesn't change or remove the Telegram message. To have a message removed, contact the moderators of the subreddit.

## Changes

Changes to this policy will be published at this page, with a new "last updated" date.
