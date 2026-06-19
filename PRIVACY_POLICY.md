# Privacy Policy — Role Restore Bot

**Last updated:** June 19, 2026

## What data we collect

When a member leaves a Discord server where this bot is active, we store:
- Their Discord user ID
- Their Discord server (guild) ID
- The IDs of roles they had at the time of leaving
- Their Discord username/tag

## How we use the data

The stored data is used **solely** to restore a member's roles if they rejoin the same server. No data is shared with third parties, sold, or used for any other purpose.

## Data encryption

All role data is encrypted at rest using AES-256-CBC encryption.

## Data retention

- Role data is automatically deleted after roles are successfully restored upon rejoin.
- Users can delete their own data at any time using the `/deleteme` command.
- Data is retained indefinitely until the user rejoins or requests deletion.

## Data deletion

Users may request deletion of all their stored data by using the `/deleteme` slash command in any server where the bot is present. This immediately and permanently removes all saved role records for that user across all servers.

## Contact

For privacy concerns or data requests, contact: devilevo666@gmail.com
