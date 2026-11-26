# rsg-merlion privacy policy

_Last updated: 26 November 2026_

rsg-merlion is a Reddit Developer Platform (Devvit) app. When a subreddit's moderators install it, it copies each new post in that subreddit to a Telegram group or channel that those moderators choose. It also sends each report on a post or comment to the same group or channel, and removes link posts that repost a link from the last 7 days.

## What the app processes

When someone submits a post in a subreddit that uses the app, Reddit sends the app that post's details. The app uses:

- the post's title, body text, flair, permalink, and link or image URLs;
- whether the post is marked NSFW or spoiler;
- the author's Reddit username.

When someone reports a post or comment, Reddit sends the app the report reason and the reported post's title, body text, permalink and report count, or the reported comment's text, permalink and report count. For a comment, the app also looks up the title of the post it's on. Reddit doesn't tell the app who made the report.

The app does not process private messages, votes, IP addresses, email addresses, or any other account information.

## Where it goes

- **Telegram.** The app sends the post's title, author username, flair, the first 700 characters of the body, image URLs, link URL and permalink to the Telegram group or channel the moderators set up, using Telegram's Bot API (`api.telegram.org`). Anyone who can see that group or channel can see the message. Telegram's own [privacy policy](https://telegram.org/privacy) applies to it there.
- **Telegram, for reports.** The app sends each report's reason, the title of the reported post (or of the post a reported comment is on), the first 700 characters of the post or comment text, the report count and the permalink to the same group or channel.
- **Telegram, for reposts.** When the app removes a repost, it sends the repost's title, author username and link URL, and the permalinks of the repost and the original post, to the same group or channel.
- **Logs.** The app logs each post submission and report it receives and each message it sends to Telegram, to help diagnose failed messages. Reddit stores and retains these logs as part of the Developer Platform, under Reddit's [privacy policy](https://www.reddit.com/policies/privacy-policy).
- **Storage.** The app stores the IDs of the posts it has sent, and the ID, reason and report count of each report it has sent, in Reddit's Developer Platform storage for 24 hours, so nothing is sent twice. To spot reposts, it stores each link post's ID with its link URL (minus tracking parameters) and title, for 7 days. It stores no other data.

The app does not sell data, does not use it for advertising, and does not send it anywhere other than the places listed above.

- **Reddit, for reposts.** When the app removes a repost, it leaves a comment on it, as the app's account, linking the original post.

## Removing content

The app copies a post when it's submitted, and a report when it's made. Editing or deleting the post on Reddit afterwards doesn't change or remove the Telegram message. To have a message removed, contact the moderators of the subreddit.

## Changes

Changes to this policy will be published at this page, with a new "last updated" date.
