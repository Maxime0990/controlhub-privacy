---
title: ControlHub privacy policy
---

<!--
  Template copy. The published copy (with the effective date, name and contact filled in) lives
  in the public repo controlhub-privacy: https://maxime0990.github.io/controlhub-privacy/
  Change both together, and keep them in step with ui/DisclosureScreen.kt,
  ui/MediaDisclosureScreen.kt and the Play Console declaration.
-->

# ControlHub privacy policy

**Effective date:** {{EFFECTIVE_DATE}}

ControlHub is an Android app that adds a short pause to endless videos in apps you choose,
such as YouTube. This policy explains what the app accesses, what it does with it, and what it
never does. In short: **ControlHub doesn't collect, store or share any personal data. Everything
it does happens on your phone.**

## Who makes ControlHub

ControlHub is made by an independent developer, {{DEVELOPER_NAME}}. You can reach them at
{{CONTACT_EMAIL}}.

## The Accessibility Service

ControlHub uses Android's Accessibility Service, which you switch on yourself in your phone's
settings after reading an explanation in the app and tapping **Agree**. Android describes
Accessibility Services in general terms, but ControlHub only uses:

- **Which app is open on your screen**, so it knows when you're in an app you've switched on in
  ControlHub, and can show the cooldown screen on top of it.

ControlHub does **not** read the text, images, videos, messages, passwords or anything else
shown on your screen. Its Accessibility Service is configured so that it can't retrieve screen
content at all.

## Notification access and audio players

To notice when a new video starts playing, ControlHub uses two more things. You switch on
Notification access yourself in your phone's settings, after reading a separate explanation in
the app and tapping **Agree**.

- **What's playing in an app you've switched on** (Notification access). Android only shares
  "what's playing" with apps that have Notification access. ControlHub uses the playing video's
  title, compared in your phone's memory only to notice that a new video started, and whether it
  is playing or paused. Titles are never saved, logged or sent.
- **When any app starts a new audio player.** Android tells every app this without a
  permission. It doesn't say which app or what is playing; ControlHub only notes the moment.

ControlHub **never reads your notifications**. Android groups "what's playing" under Notification
access, but ControlHub ignores notifications completely.

## How that information is used

Only to count the videos you start while an app you've switched on is open, and to show a
cooldown screen when you reach the limit you've set. The count is kept in your phone's memory
while the app runs and starts over after a break. It is never written to storage, and nothing
about which apps you use or what you watch is recorded.

## What is stored on your phone

ControlHub saves only its own settings, on your phone: which apps you've switched on, your
cooldown rules (for example the number of videos and the cooldown length), and whether you've
agreed to the explanations of the Accessibility Service and of Notification access. Uninstalling the app, or clearing its
storage in Android's settings, deletes them.

## What is collected or shared

Nothing. ControlHub:

- has **no internet permission**, so it can't send anything anywhere;
- contains **no advertising, analytics or tracking** code;
- **doesn't share** any information with the developer or anyone else.

If you've allowed your phone to share usage and diagnostics with Google, Android and Google Play
may send crash reports about apps, including ControlHub, to Google under Google's own privacy
policy. The developer may see these crash reports in anonymous form to fix bugs. ControlHub
itself sends nothing.

## Your choices

- You can switch ControlHub's Accessibility Service off at any time in **Settings →
  Accessibility → ControlHub**. ControlHub then stops working until you switch it on again.
- You can switch ControlHub's Notification access off at any time in Android's notification
  settings. Cooldowns then pause, and ControlHub tells you why.
- You can turn ControlHub off for each app in the app itself.
- You can uninstall ControlHub at any time, which deletes its settings.

## Children

ControlHub isn't directed at children under 13 and doesn't knowingly collect any information
from anyone, including children.

## Changes to this policy

If what ControlHub accesses or does ever changes, this page will be updated first, with a new
effective date, and the explanation in the app will change to match.

## Contact

Questions about this policy: {{CONTACT_EMAIL}}.
