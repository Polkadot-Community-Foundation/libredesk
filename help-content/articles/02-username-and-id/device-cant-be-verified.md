---
title: "\"We couldn't verify this device\""
slug: device-cant-be-verified
collection: username-and-id
type: error
priority: P1
sort_order: 60
excerpt: >-
  Your phone didn't pass device verification. Rooted phones and most custom ROMs can't. Phones without Google Play need the direct download version.
keywords: [couldn't verify device, verification failed, rooted, custom rom, device verification isn't available, app safety check failed, google play services not available, integrity, can't get username]
related: [device-verification, which-phones, choose-version, contact-support]
flags: [F13, F29]
status: draft
last_checked: 2026-11-03
---

You see this when your phone doesn't pass device verification, the quick check the app runs when you choose a username. The exact message tells you why.

## "We couldn't verify this device. Rooted devices and custom ROMs aren't supported."

Polkadot can't run on rooted phones, phones with an unlocked bootloader, or custom ROMs other than GrapheneOS. To use Polkadot, use a phone running Android 10 or later, or GrapheneOS, with a locked bootloader. See [Which phones can use Polkadot?](../01-getting-started/which-phones.md)

## "Google Play services aren't available on this device, so it can't be verified."

You have the Google Play version on a phone without Google Play services. The message goes on to say "Contact support for a build that works without them." Install the direct download version instead, from [direct download link], or email us at [help@pcf.network](mailto:help@pcf.network) for help. <!-- REVIEW F13: direct download link. -->

## "Device verification is temporarily unavailable. Try again in a moment."

The check couldn't run right now. Wait a minute, then tap **Get username** again.

## "Device verification isn't available"

The full message is "Free username claims require device verification, but this device doesn't support the required verification method." Check that your phone is on the list in [Which phones can use Polkadot?](../01-getting-started/which-phones.md) If it is, contact us.

## "App safety check failed"

The full message is "We couldn't confirm that this app is safe to use on this device". This can happen on a phone that's been modified, or with a copy of the app that didn't come from Google Play or the official download. Install Polkadot again from Google Play or the official download, then try again. 

## Still need help?

Email us at [help@pcf.network](mailto:help@pcf.network), or in the app tap **Settings** > **Legal & Support** > **Contact us**. Tell us your app version (it's at the bottom of **Settings**) and the exact message you saw.

## Related

- [What is device verification?](device-verification.md)
- [Google Play or direct download: which version is for you?](../01-getting-started/choose-version.md)
- [Contact support](../09-troubleshooting/contact-support.md)
