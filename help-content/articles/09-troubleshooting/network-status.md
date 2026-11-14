---
title: What the Network Status rings mean
slug: network-status
collection: troubleshooting
type: concept
priority: P2
sort_order: 30
excerpt: >-
  The small rings at the top of the screen show how well Polkadot is connected to the network. Tap Network Status in the dock to see each connection.
keywords: [network status, rings, circles, connection indicator, people chain, statement store, disconnected, connecting]
related: [no-connection, taking-longer-than-usual, messages-not-arriving]
flags: []
status: draft
last_checked: 2026-11-03
---

The small rings at the top right of the main screens show how well the app is connected to the parts of Polkadot's network it uses. When they're all connected, everything works as normal.

## See each connection

Tap **Network Status** at the far right of the dock. A panel titled "Network Status" opens with one row for each connection:

- "People Chain"
- "Hub Chain"
- "Bulletin Chain"
- "Statement Store"

Tap **Network Status** again to close the panel. The rings at the top of the screen show the same thing, and you can't tap them.



## What each state means

| You see | What it means | What to do |
|---|---|---|
| "Connected" | This connection is working. The extra figures, such as "Live 99%", are technical detail you can ignore. | Nothing. |
| "Connecting…" | The app is connecting. | Wait a few seconds. |
| "No internet" | Your phone isn't online. | See ["Waiting for network connection…" or "No connection"](no-connection.md). |
| "Disconnected" | The app lost this connection. | Check your internet, then close and reopen the app. |
| "Not producing blocks" or "Chain broken" | There's a problem on the network side, not with your phone. | Wait and try again later. |

If one row stays on anything other than "Connected" for a long time, some things in the app may be slow or not work. For example, messages can take longer to send.

## Related

- ["Waiting for network connection…" or "No connection"](no-connection.md)
- ["This is taking longer than usual"](taking-longer-than-usual.md)
- [My messages aren't arriving](messages-not-arriving.md)
