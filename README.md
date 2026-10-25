# Pycom Radio Controller for ICOM IC-9700, IC-7610 and IC-7300MK2 | Remote Control Software

[![Pycom Radio Controller interface](https://pycom.stevendodd.net/images/cover-image.jpg)](https://pycom.stevendodd.net/)

> Remote Control Of Your ICOM IC-9700, IC-7610 and IC-7300MK2 With AI-Assisted Operating

[Get Started](https://pycom.stevendodd.net/getting-started.html)

---

## Remote Operation Designed For Practical Amateur Radio Use

Pycom Radio Controller provides direct CI-V based control of the ICOM IC-9700, IC-7610 and IC-7300MK2, allowing operators to manage frequency, mode, memories, tones and more from a connected computer. Full remote control of your station can be achieved allowing you to operate your radio from wherever you may be.

The application is designed for voice and digital satellite operations providing full duplex control via a built-in rigctl server alongside integrations with popular amateur radio satellite tooling.

---

| Core Features | Documentation |
| --- | --- |
| - Full remote control<br>- First class satellite operations<br>- Call sign look up and logging<br>- Built in enhanced memory functionality<br>- Real time meters and waterfall<br>- Remote RC-28 integration<br>- Automatic signal detection and AI identification<br>- AI noise reduction (local neural network)<br>- Voice control and live transcription | - [Logbook](https://pycom.stevendodd.net/log-book.html) - What's new, NEWS, Random stuff<br>- [Radio Setup](https://pycom.stevendodd.net/radio-setup.html)<br>- [Installation](https://pycom.stevendodd.net/getting-started.html)<br>- [Doppler Control](https://pycom.stevendodd.net/doppler.html)<br>- [Signal Detection](https://pycom.stevendodd.net/signal-detection.html)<br>- [AI Signal Classification](https://pycom.stevendodd.net/signal-identification.html)<br>- [AI Noise Reduction](https://pycom.stevendodd.net/ai-nr.html)<br>- [Transcribe & Voice Commands](https://pycom.stevendodd.net/transcribe.html)<br>- [Downloads](https://pycom.stevendodd.net/download.html) |

---

## Interface Overview

Pycom Radio Controller has been developed to keep important operating controls immediately available without compromising on operability. Tuning, managing and making QSOs is easily achievable.

Documentation pages provide configuration guidance, radio setup details, and operating examples for supported workflows.

![Pycom Radio Controller main operating interface](https://pycom.stevendodd.net/images/interface.png)

---

## AI-First Features

Pycom Radio Controller embraces AI-first operating, with intelligence built into every stage of the receive path. All features can run entirely on your computer — the noise-reduction neural network, the signal classifier, the wake word and voice command grammar can all be local. Speech transcription and LLM callsign identification can alternatively be offloaded to a cloud provider.

### AI Noise Reduction

Real-time neural-network denoising of received audio, running entirely on your computer — no cloud, no audio leaves your machine. Works alongside the radio's own NR with a simple strength slider.

[Learn more about AI NR](https://pycom.stevendodd.net/ai-nr.html)

### AI Signal Identification

Automatic detection and neural-network classification of signal types — CW, FT8, FM, SSB and more. Train or fine-tune the model on your own captures to improve accuracy on the bands you use.

[Learn more about AI identification](https://pycom.stevendodd.net/signal-identification.html)

### Voice Commands

Speak to your radio — tap the capture key or say the wake word, then tune to frequencies, set modes, apply memories or key PTT using natural language transcribed by Whisper.

[Learn more about voice control](https://pycom.stevendodd.net/voice-commands.html)

### Live Transcription + LLM

Real-time speech-to-text of received audio, with an optional LLM cleanup pass that extracts callsigns, RST reports and names from noisy radio audio — local via Ollama or in the cloud.

[Learn more about Transcribe](https://pycom.stevendodd.net/transcribe.html)

---

## Built Around Real Satellite Operating Requirements

Built into the software alongside the Hamlib rigctld server is support for popular satellite tooling, such as WSJT-X, Gpredict, CSN Technologies S.A.T controller and SatPC32. This enables full duplex remote doppler control from programs you already use.

### Full Duplex Doppler Control

Full duplex operation for linear transponders — track OSCAR birds, hear yourself on the downlink and tune across the passband with doppler correction handled for you.

[Learn more about doppler control](https://pycom.stevendodd.net/doppler.html)

### Built-in Rigctld Server

A Hamlib-compatible rigctld server is built in, letting Gpredict and other trackers drive doppler. A PTT & Read Only mode lets WSJT-X share control alongside satellite tracking.

[Learn more about rigctld](https://pycom.stevendodd.net/rigctld.html)

### CSN S.A.T Integration

Pair Pycom with the CSN Technologies S.A.T controller: the radio is configured and doppler correction applied automatically, detecting satellite changes as you track.

[Learn more about S.A.T tracking](https://pycom.stevendodd.net/csnsat.html)

### SatPC32 CAT Pass-through

Windows users get experimental SatPC32 CAT control via a com0com virtual COM port pair — doppler from a tool many satellite operators already use.

[Learn more about SatPC32](https://pycom.stevendodd.net/satpc32.html)

### Data Modes with WSJT-X

FT8, FT4 and WSPR through the same rigctld server, with dedicated settings for use alongside doppler control — from full duplex FM satellites to grid expeditions.

[Learn more about WSJT-X](https://pycom.stevendodd.net/wsjtx.html)

---

## See It In Action

Watch demos, tutorials and live operating videos - from full duplex satellite contacts to AI noise reduction and voice control.

| | | |
| --- | --- | --- |
| [![Icom 9700/7610 Base Station DX from your Phone](https://img.youtube.com/vi/I7889exDB2k/hqdefault.jpg)](https://www.youtube.com/watch?v=I7889exDB2k) | [![Okay radio; set frequency - Voice Control](https://img.youtube.com/vi/UMa1hFtvraE/hqdefault.jpg)](https://www.youtube.com/watch?v=UMa1hFtvraE) | [![Built in Local AI Noise Reduction - pre-trained streaming speech-enhancement](https://img.youtube.com/vi/lw1PA1HDOTk/hqdefault.jpg)](https://www.youtube.com/watch?v=lw1PA1HDOTk) |

[More Videos](https://pycom.stevendodd.net/videos.html)

---

## Ready To Get On The Air?

Download Pycom Radio Controller, connect your IC-9700, IC-7610 and IC-7300MK2 over the network, and explore everything from full duplex satellite operation to AI-assisted operating. Enjoy an enhanced remote operating experience.

[Get Started](https://pycom.stevendodd.net/getting-started.html)

---

*Pycom Radio Controller by Steven Dodd (M0SNZ)*
