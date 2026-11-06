# PULSE privacy

Applies to PULSE 1.0.6. Updated 6 November 2026.

## Purpose

PULSE shares one browser tab's audio into an X Space where you are a host or speaker. An X account is required; PULSE has no separate account.

## Access to X pages

PULSE runs on x.com and twitter.com to display its panel, determine the Space and your stage/mute state, and connect shared audio to X's existing browser audio connection.

## Audio

Chrome asks you to choose a source tab for each share. PULSE uses its audio track and stops the capture's video track. Your microphone is excluded from the shared mix until you enable Voice. Audio is sent through X's existing Space connection, not to a developer-operated audio server. PULSE does not record it. X's policies and any recording by X or other participants apply once audio is shared.

## Optional player access

Player controls and M can request scripting permission and access to all sites. This permission is broader than the selected tab. PULSE inspects candidate audible tabs and their audio/video players to identify the source, and may mark candidate tabs using Chrome's Capture Handle API. It reads player state such as playback position, duration, volume and mute state, and can change playback, position, volume and mute. If the selected tab cannot be identified, a fallback can select another audible tab. You may decline optional access and still share audio; source-player controls will then be unavailable. Chrome's extension settings let you review or remove the access.

## Local settings

PULSE stores the tab level, Width setting and panel position in extension storage on this device. Uninstalling the extension removes those settings.

## Developer data collection

PULSE has no analytics or advertising endpoint and does not send audio, browsing history or telemetry to the developer. Audio shared into a Space still travels through X.

## Stopping

Stop ends the capture and restores X's microphone connection. A normal Stop with Voice off mutes X first. Crash or connection-stall recovery can return to X's normal microphone behavior.

## Support

For questions or problems, [open a GitHub issue](https://github.com/quiet-runtime/pulse/issues).
