# PlaylistChecker
Checked a playlist at Spotify by Google Apps Script.

## Getting Started
### Spotify
1. Create Apps at https://developer.spotify.com/dashboard/applications
1. Save clientID & clientSecret in a ScriptProperties.
1. Publish the authorizationCode. ex. https://accounts.spotify.com/authorize?response_type=code&redirect_uri=https://example.com/callback&client_id={clientID}
1. Save authorizationCode in a ScriptProperties.
### Slack
1. Prepared incoming webhook. ex https://api.slack.com/messaging/webhooks