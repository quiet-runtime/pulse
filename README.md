<p align="center"><img src="img/pulsar-icon.png" width="96" height="96" alt=""></p>

<h1 align="center">PULSE · PULSATE · PULSAR</h1>

<p align="center"><b>Full-band stereo for X Spaces.</b><br>
From one strip in Chrome to a full console on Windows and macOS.</p>

<p align="center"><a href="../../releases/latest"><b>Download PULSE 1.0.6</b></a> · <a href="#pulsate">PULSATE</a> · <a href="#pulsar">PULSAR is coming to Windows and macOS</a></p>

<table>
<tr>
<th width="24%">PULSE</th>
<th width="26%">PULSATE</th>
<th width="50%">PULSAR</th>
</tr>
<tr>
<td align="center"><a href="#pulse"><img src="img/pulse-strip.png" alt="The PULSE strip, on air."></a></td>
<td align="center"><b>Multichannel mixer</b><br>Channel strips<br>Built-in player<br>MIDI control</td>
<td align="center"><a href="#pulsar"><img src="img/pulsar-desk.jpg" alt="PULSAR's Studio with two turntables."></a></td>
</tr>
<tr>
<td>One strip, one tab, and your mic stays out unless you let it in.</td>
<td>A multichannel mixer in Chrome, with a channel strip per source and a built-in player.</td>
<td>The whole console on your computer, with your own Room view.</td>
</tr>
<tr>
<td><b>Chrome</b><br>Version 1.0.6</td>
<td><b>Chrome</b><br>In development</td>
<td><b>Windows, macOS</b><br>Coming</td>
</tr>
</table>

The website in this repository runs the real PULSAR Studio in your browser: its Mixer, Turntables, Racks and audio engine, with AI-made sample music and voices.

---

## PULSE

**Share a tab's audio into your Space, in stereo.** That is the whole job, so PULSE stays one strip.

<img align="right" width="240" src="img/pulse-strip.png" alt="The PULSE strip: Your voice is off, the time bar, the meter and fader, previous, pause and next keys, mute, the stereo Width knob and Stop, in clear glass.">

- **Share a tab.** Chrome's own picker asks which tab, and the audio joins the connection X already opened for your Space.
- **Run its player.** Previous, play, pause, next and a time bar, right on the strip.
- **Ride the level.** The fader sets the tab's volume; the meter shows the signal as it leaves the fader.
- **Open up the stereo.** The Width knob runs from mono at −100 to wider at +100, and is off at 0.
- **Mute with one key.** M takes the tab off the air and mutes it in the tab too.
- **Your microphone stays out.** Only the tab goes out, until you press the Voice key to talk over it.
- **Know when you're live.** On air shows only once the audio is really leaving your browser. Stop gives X its microphone back.

### Get started

1. Download the zip from [Releases](../../releases/latest) and unzip it.
2. In Chrome, open `chrome://extensions`, turn on Developer mode and choose **Load unpacked**.
3. Go on stage in a Space as a host or speaker. The strip appears at the bottom left.
4. Press **Share a tab** and choose the tab in Chrome's picker.

Unmute in X to go on air. A mute in X, yours or a host's, silences everything you send, tab included. PULSE sends full-band stereo; what each listener's X app plays is up to X.

---

## PULSATE

**A multichannel mixer for X Spaces, built into Chrome.** PULSE carries one tab. PULSATE mixes several sources at once, each on a channel strip of its own, into one stereo signal for your Space.

<table>
<tr><td width="26%"><b>Channel strips</b></td><td>Trim, compressor, 4-band EQ, filter and an effects send on every strip, with mute, solo and duck.</td></tr>
<tr><td><b>Built-in player</b></td><td>Queue your own tracks and play them without opening another tab. Previous, play and next sit on the player's strip, and the music ducks while you speak.</td></tr>
<tr><td><b>Comfort features</b></td><td>Colour themes and interface scale, meters on every strip with a loudness target, and MIDI control of the knobs.</td></tr>
</table>

PULSATE is in development. It is a separate build from PULSE, and its details may change before release.

---

<p align="center"><img src="img/pulsar-icon.png" width="96" height="96" alt=""></p>

## PULSAR

**PULSE is one channel. PULSAR is the whole console.** A desktop app for Windows and macOS with its own view of your Space, two turntables, a full channel section on every strip, racks of effects and MIDI control.

<p align="center"><img src="img/pulsar-desk.jpg" alt="PULSAR's Mixer: Voice, two Feeds, Player, Master and Room strips with channel knobs, above two turntables with platters, hot cues and waveforms."><br>
<sub>PULSAR's Studio in a test build, two test tracks in sync.</sub></p>

### The channel section

<p align="center"><img src="img/pulsar-channel.jpg" alt="PULSAR's Mixer: Voice, Feed A, Feed B, Player, Master and Room strips, each with trim, compressor, four EQ bands, filter and send, under the shared effects bar."></p>

Every strip has trim, a compressor, a 4-band EQ or a 3-band isolator, a filter or colour effect, and a send to the shared effects: a filter with resonance, a colour effect such as Air, and a reverb with its own return. Voice adds CRUSH, WARBLE and ECHO of its own. Master holds the ceiling and a true-peak limiter, and Room is for monitoring only, never sent. Mute, solo and duck sit on every strip, with tap tempo and a crossfader between the two Feeds. Voice is solo-safe by default, so soloing music never takes you off the air.

### Your Room and two turntables

<table>
<tr>
<td width="50%"><img src="img/pulsar-room.jpg" alt="PULSAR's Room view beside the Mixer: the host, the speakers and listeners, and a private note on a listener."></td>
<td width="50%"><img src="img/pulsar-turntables.jpg" alt="PULSAR's two turntables under the Mixer, with platters, hot cues and waveforms."></td>
</tr>
<tr>
<td><b>Your own Room view.</b> Sign in on X's own page, inside the app. Create and schedule Spaces, see the stage, handle requests to speak, and react.</td>
<td><b>Turntables that perform.</b> Three-band waveforms, CUE, eight hot cues, loops, beat jump, tempo that keeps the key, key shift, beat sync, jog and a crossfader.</td>
</tr>
</table>

### Racks of effects

<p align="center"><img src="img/pulsar-presets.jpg" alt="Presets for talking over music: Duck under Voice, Carve room for Voice, Multiband duck, Mid-side duck, Low-quality track rescue, Clarity and Music leveler."></p>

<p align="center"><img src="img/pulsar-racks.jpg" alt="PULSAR's processors, grouped as tone, dynamics, under voice, colour and width, motion and pitch, and space."></p>

A rack on any strip chains processors in any order. They are grouped the way a chain runs: repair and level, tone, dynamics, under voice, colour and width, motion and pitch, space and output, then echoes, filters and lo-fi. Ready-made presets cover what a Space needs. Music can duck or carve room for your voice, a low-quality track can be rescued, and there is sound design such as Club punch, Ambient wash, Ping-pong under Voice and Quarter-note wobble.

### MIDI on the controls

<p align="center"><img src="img/pulsar-midi.jpg" alt="PULSAR in MIDI learn: every mappable control outlined, with CC numbers on the Voice and Feed A faders."></p>

Click a control, then move one on your controller. Several controllers can work at once, with pickup (soft takeover), feedback, and mappings you can export and import.

### Your look

<p align="center"><img src="img/pulsar-appearance.jpg" alt="PULSAR's Appearance settings: five materials and eight colour schemes, with scale and motion."></p>

Five window materials, from solid to Liquid Glass and Windows' own Mica. Eight colour schemes, including true black for OLED screens and high contrast. Interface scale from 90 to 125 %, and reduced motion.

### A record of every Space

<p align="center"><img src="img/pulsar-record.jpg" alt="A Space record: recordings, bitrate sent, network to X's server, loss, app load, loudness and peak, strip levels, audience, time per role and events."></p>

After each Space: bitrate, round trip and jitter to X's server, loss, loudness and true peak, the audience over time and your time per role. REC keeps what you heard and what you sent.

- **Any source, isolated.** A desktop app, an audio device, a web page, YouTube or a local file, each on one of six Feeds, with crosstalk held to −100 dBFS.
- **It reads the music.** Beat This! beat grids, downbeats, S-KEY musical key and song sections, worked out on your own machine.
- **Clean at full scale.** An 826-run audit of the channel section at 0 dBFS found every path at or under 0.0 dBFS.

**Want it first?** Press **Watch** on this repository and choose **Custom → Releases**.

## Engineering, in brief

- **Transmit:** Opus (RFC 7587), 48 kHz stereo, 128 kbps by default, `usedtx=0`, `cbr=0`. Only the Opus `fmtp` line changes, and only on connections that send audio.
- **No lossy hop** before X's encoder. Sources are mixed at 48 kHz in 32-bit float and cross between contexts on the audio threads.
- **Loudness:** ITU-R BS.1770-4 and EBU R128. **Limiter:** true peak at 8× oversampling.
- **Claims come from measurements:** On air, stereo and bitrate are read from the sender's own statistics, and quality is measured at the receiving side of a loopback peer.

## Privacy and licence

PULSE has no servers, no accounts and no analytics, and records nothing. It stores its settings and runs on x.com and twitter.com; the player keys and M ask once for access to the tab you share. Read the [privacy policy](PRIVACY.md).

PULSE is free to use. Its code is not open source: the licence in the download lets you install and use it, not copy, change or redistribute it. The libraries inside it keep their own licences, listed in its third-party notices. This repository's content is covered by its [licence](LICENSE.md).

PULSE, PULSATE and PULSAR are independent products. Not affiliated with or endorsed by X Corp.
