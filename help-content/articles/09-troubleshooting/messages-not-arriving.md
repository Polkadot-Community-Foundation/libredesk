---
title: My messages aren't arriving
slug: messages-not-arriving
collection: troubleshooting
type: troubleshooting
priority: P1
sort_order: 50
excerpt: >-
  Usually the other person hasn't accepted your message request or opened the app yet, or one of you is offline. Messages arrive once you're both online.
keywords: [messages not sending, messages not delivered, not receiving messages, message stuck, can't send message, missing messages, delayed messages]
related: [message-requests, no-connection, not-getting-notifications, chat-not-fully-private]
flags: [F13, F17]
status: draft
last_checked: 2026-11-03
---

Usually, the other person hasn't accepted your message request or hasn't opened the app yet, or one of you is offline. Messages are delivered once you're both connected.

## Check these first

1. Is it a message request? Until they accept, you can send one message, and you'll see "Wait for jake.23 to accept your message request." (with their username). See [How message requests work](../03-chats-and-calls/message-requests.md).
2. Are you online? Tap **Network Status** in the dock and check every row says "Connected". See ["Waiting for network connection…" or "No connection"](no-connection.md).
3. Have they opened the app? If you see "Couldn't start a chat with this user. Ask them to open the app to finish setting up chats.", ask them to open Polkadot.
4. Did you block them? If you blocked them, their chat says "You won't receive any messages and requests until you unblock" followed by their username. See [Block or unblock someone](../03-chats-and-calls/block-someone.md).
5. Did you tap **Don't send**? If the app showed "This chat can't be fully private right now" and you tapped **Don't send**, those messages weren't sent. See ["This chat can't be fully private right now"](../03-chats-and-calls/chat-not-fully-private.md).

## If you use the direct download version

The direct download version (for GrapheneOS and phones without Google Play) doesn't get push notifications, so new messages only show up while Polkadot is open. 

## If you see "Some messages could not be retrieved and are permanently unavailable."

Some messages in this chat couldn't be delivered and can't be recovered. Ask the other person to send them again.

<details><summary>How long does a message wait to be delivered?</summary>

If the other person is offline, your message waits to be delivered for up to 48 hours. If it still hasn't been delivered, your app tries again the next time you open it. <!-- REVIEW F17: confirm the 48-hour window and the retry behaviour before publishing. -->

</details>

## If you see "Unsupported message content. Please update the app."

The other person sent something that needs a newer version of the app. Update Polkadot, then open the chat again. See [Update the app](../08-settings-and-account/update-the-app.md).

## Still need help?

Email us at [help@pcf.network](mailto:help@pcf.network), or in the app tap **Settings** > **Legal & Support** > **Contact us**. Tell us your app version (it's at the bottom of **Settings**) and the exact message you saw.

## Related

- [How message requests work](../03-chats-and-calls/message-requests.md)
- [I'm not getting notifications](not-getting-notifications.md)
- ["Waiting for network connection…" or "No connection"](no-connection.md)
