# Slack backup status

This public repository hosts an aggregate status page for encrypted Slack backups. It contains counts, storage totals, and backup dates. The encrypted assets remain in the **private** `newdarwindev/dots-slackdump-export` repository; this page provides no artifact links. No message content, channel or user identities, tokens, or decryption keys are published here.

The status feed was initially published from verified private Release metadata. Future successful backup workflows can update only `status.json` through a write deploy key scoped to this public repository. GitHub Actions billing currently blocks hosted runs in the private backup repository, so no automatic update has run yet. Archived message-record totals include overlap across incrementals and are not unique-message counts. Attachment bytes and direct messages are excluded from the backups.
