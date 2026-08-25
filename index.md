---
title: Netra — Privacy Policy
---

_Last updated: 23 August 2026_

Netra is a visual assistant for blind and low-vision people. It looks through
your camera and listens through your microphone so it can describe what is in
front of you. This policy says exactly what leaves your phone, what stays on it,
and why.

## What leaves your phone

**While a session is running**, Netra streams to Google's Gemini API:

- **Camera frames** — roughly one image per second, at reduced resolution.
- **Microphone audio** — continuously, so you can speak to it at any time.

This is what the app is. There is no version of Netra that describes your
surroundings without sending your surroundings somewhere. A session runs only
while you have started one; pausing stops both streams.

Google processes this data under the [Gemini API Terms](https://ai.google.dev/gemini-api/terms)
and the [Google Privacy Policy](https://policies.google.com/privacy). **Whether
Google retains it or uses it to improve their models depends on the API tier the
operator of this app is using** — the paid tier excludes it, the free tier does
not. If you are running your own build, this is your choice to make and you
should read those terms.

**If you sign in** (optional — everything works without it), Firebase
Authentication receives your email address, or your Google account identifier if
you use Google sign-in.

## What stays on your phone

- **People you memorise.** Faces are stored as a numeric fingerprint plus a
  reference image, in the app's private storage, and are excluded from cloud
  backup. They are never uploaded to us and we never see them. They are deleted
  when you remove the person or uninstall the app.
- **Your settings**, including speaking speed and which guidance you have on.
- **The transcript** of the current session, which is discarded when the session
  ends.

## What Netra does not do

- No advertising, no advertising identifiers, no ad networks.
- No analytics or crash-reporting SDK.
- No tracking across other apps or websites.
- Nothing is sold or shared with third parties for their own purposes.
- No recording. Frames and audio are streamed and not stored, by us, anywhere.

## A note about other people

Netra sees whoever is in front of you, and can be asked to remember them by
name. Those people have not agreed to anything. Their faces stay on your phone
and are never uploaded, which is a deliberate design decision rather than an
incidental one. Please use the feature considerately, and be aware that
recording or identifying people may be restricted where you live.

## Your choices

- **Stop sending anything**: pause the session, or revoke the camera and
  microphone permissions in system settings. The app still opens.
- **Delete a memorised person**: Settings → People → the person → delete.
- **Delete your account**: Settings → Delete account. This removes your sign-in
  permanently. Memorised people are on your device and are unaffected.
- **Delete everything**: uninstall the app.

## Children

Netra is not directed at children and we do not knowingly collect data from
them.

## Contact

Questions or requests about your data: **suchith.arella@gmail.com**

Changes to this policy will be published here with a new date at the top.
