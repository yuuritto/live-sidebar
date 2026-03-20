# Privacy Policy — Live Sidebar

**Last Updated:** March 20, 2026

## Overview

Live Sidebar is a Chrome browser extension that displays your Twitch followed channels and YouTube subscribed channels in a unified sidebar, showing their live streaming status. This Privacy Policy describes how Live Sidebar ("we", "our", or "the Extension") collects, uses, stores, and shares your information.

## Information We Collect

### Authentication Data

When you connect your Twitch or YouTube account, the Extension receives OAuth tokens (access tokens and refresh tokens) that allow it to access your account data on your behalf. We do **not** collect or have access to your Twitch or YouTube passwords.

### Data Accessed via Twitch API

- Your Twitch user ID and display name
- Your list of followed channels
- Live streaming status of your followed channels (stream title, game name, viewer count, thumbnails)

### Data Accessed via YouTube API

- Your YouTube channel ID and channel title
- Your list of subscribed channels
- Live streaming status of your subscribed channels (stream title, viewer count, thumbnails)

### Data We Do NOT Collect

- We do **not** collect your browsing history or web activity
- We do **not** collect personal information such as your name, email address, or physical address
- We do **not** collect payment information (payments, if any, are processed entirely by third-party payment providers)
- We do **not** collect analytics or usage tracking data

## How We Use Your Data

All data accessed by Live Sidebar is used **solely** to provide the core functionality of the Extension:

- Displaying your followed/subscribed channels and their live status in the sidebar
- Maintaining your authenticated session with Twitch and YouTube
- Sending desktop notifications for live stream events (if enabled by you)

We do **not** use your data for advertising, marketing, analytics, or any purpose unrelated to the Extension's functionality.

## Data Storage

- All data (OAuth tokens, channel lists, and cached streaming data) is stored **locally on your device** using Chrome's `chrome.storage.local` API
- **No data is transmitted to or stored on any external server operated by us**
- Twitch token exchange and refresh operations are processed through a secure proxy server that handles authentication only and does not store any user data
- Cached channel data is automatically refreshed at regular intervals and replaced with current data

## Data Sharing

We do **not** sell, trade, license, or share your data with any third parties.

Your data is only transmitted to:

- **Twitch API** (api.twitch.tv) — to retrieve your followed channels and their live status
- **YouTube Data API** (googleapis.com) — to retrieve your subscribed channels and their live status
- **YouTube RSS Feeds** (youtube.com/feeds) — to check for recent videos (no authentication required, no user data transmitted)

## Data Retention and Deletion

- All data is stored locally on your device and is not retained by us on any server
- You can delete all stored data at any time by:
  - Clicking the "Disconnect" button for each platform within the Extension
  - Uninstalling the Extension (which removes all locally stored data)
- Upon disconnecting an account, all associated tokens and cached data for that platform are immediately deleted from local storage

## Google API Services — Limited Use Disclosure

Live Sidebar's use and transfer to any other app of information received from Google APIs will adhere to the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including the Limited Use requirements.

Specifically:

- We only use YouTube API data to display your subscribed channels and their live streaming status
- We do not transfer YouTube API data to any third party
- We do not use YouTube API data for advertising or any unrelated purpose
- We do not allow humans to read YouTube API data except as necessary to provide the Extension's functionality to you

## YouTube API Services

Live Sidebar uses YouTube API Services. By using Live Sidebar, you also agree to be bound by the [YouTube Terms of Service](https://www.youtube.com/t/terms).

You can revoke Live Sidebar's access to your YouTube data at any time through your [Google Account permissions page](https://myaccount.google.com/permissions).

## Twitch API Services

Live Sidebar uses Twitch API Services. By using Live Sidebar, you also agree to be bound by the [Twitch Terms of Service](https://www.twitch.tv/p/legal/terms-of-service/) and the [Twitch Developer Services Agreement](https://www.twitch.tv/p/legal/developer-agreement/).

You can revoke Live Sidebar's access to your Twitch data at any time through your [Twitch Connections settings](https://www.twitch.tv/settings/connections).

## Children's Privacy

Live Sidebar is not directed at children under the age of 13 (or applicable age in your jurisdiction). We do not knowingly collect personal information from children.

## Changes to This Privacy Policy

We may update this Privacy Policy from time to time. Any changes will be reflected by updating the "Last Updated" date at the top of this page. Your continued use of the Extension after changes are posted constitutes your acceptance of the updated Privacy Policy.

## Contact

If you have questions about this Privacy Policy or your data, please contact us at:

**Email:** entet.info@gmail.com


---

© 2026 Live Sidebar. All rights reserved.
