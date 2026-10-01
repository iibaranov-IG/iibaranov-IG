# Igor Baranov

**Technical Director, Radio KP · Broadcast Audio & AoIP Engineer · BCL Founder**

I investigate and resolve failures where broadcast software, audio networks and equipment need to work together: AES67/PTP synchronization, Dante and Axia Livewire+, NMOS, MIDI reconnection, PTZ control, OSC feedback, routing and resilient operations.

I lead **Broadcast Control Lab (BCL)**, an independent engineering lab that turns real operational problems into reproducible checks, focused fixes and reviewable evidence.

[Public repair evidence](https://github.com/iibaranov-IG/iibaranov-IG-broadcast-control-lab-evidence) · [BCL website](https://bcl.tw1.su/)

## Products in testing

### BCL Voice Reconstructor

An offline REAPER workflow for editorial restoration and improvement of degraded remote and VoIP speech; it is not a live on-air processor. It creates a processed version while preserving the original, includes installation diagnostics, and produces an engineering report for every render.

**Pilot testers are welcome.** If you work with difficult remote interviews, archive audio, or broadcast contributions, [email me](mailto:iibaranov@gmail.com?subject=BCL%20Voice%20Reconstructor%20beta%20testing) with a short description of your workflow; I will send the current beta link.

### BCL Player 0.1 for macOS

A broadcast stream player for monitored audio delivery: primary and backup network sources, local fallback, persistent configuration, event log, live metering, presets and a Reference Processor.

This is currently a macOS release candidate. I welcome feedback from engineers able to test real streams and failover scenarios. [Request a test build](mailto:iibaranov@gmail.com?subject=BCL%20Player%20test%20build).

## Selected upstream repairs

| Project | Problem addressed | Upstream result |
| --- | --- | --- |
| Amical | Capture the active microphone channel on multichannel audio interfaces | [Merged #184](https://github.com/amicalhq/amical/pull/184) |
| PiPedal | Bluetooth MIDI fails to reconnect when the ALSA port appears after its client | [Merged #587](https://github.com/rerdavies/pipedal/pull/587) |
| RtAudio | Unix pthread flags appear in pkg-config metadata for MSVC consumers | [Merged #487](https://github.com/thestk/rtaudio/pull/487) |
| Liquidsoap | Last.fm rejects the default Audioscrobbler HTTP endpoint | [Merged #5404](https://github.com/savonet/liquidsoap/pull/5404) |
| FPP | Missing or malformed PTP management data can falsely indicate lock | [Merged #2942](https://github.com/FalconChristmas/fpp/pull/2942) |

[Browse published repair evidence and validation limits](https://github.com/iibaranov-IG/iibaranov-IG-broadcast-control-lab-evidence). Maintainer acceptance, release availability and real-device validation are separate milestones.

## Where I can help

- **Broadcast audio and AoIP:** Axia Livewire+, LWRP/LWCP, AES67, Dante and AMWA NMOS; interoperability, routing and operational diagnostics.
- **Equipment control:** MIDI/ALSA, OSC and VISCA over TCP/UDP; connection states, command/reply behavior and reproducible protocol checks.
- **Open-source engineering:** focused bug fixes, build and integration failures, regression tests and clear evidence for maintainers.
- **Broadcast facilities:** commissioning, failure analysis, redundancy and migration planning across mixed-vendor systems.

Field experience includes Telos Alliance / Axia, Barix, SOUND4 and AEQ systems. Specific device and platform coverage is agreed for each investigation.

## More open-source work

- [AMWA NMOS Testing: handle session-level SDP connection data](https://github.com/AMWA-TV/nmos-testing/pull/907)
- [AES67 Stream Monitor: build native audio modules on matching architectures](https://github.com/philhartung/aes67-monitor/pull/34)
- [Livewire LWRP module: expose all GPI and GPO variables](https://github.com/k2fc/companion-module-livewire-lwrp/pull/2)

## Collaboration

Available for scoped engineering work, integration investigations and product testing.

For a software failure, [email a BCL repair request](mailto:iibaranov@gmail.com?subject=BCL%20repair%20request) with the device model, software or firmware version, expected behavior, reproduction steps and your ability to test on the real setup. Remove credentials and private data from public reports.

For consulting, integration work or a scoped engineering investigation, [email iibaranov@gmail.com](mailto:iibaranov@gmail.com). We establish scope, available evidence and acceptance criteria before committing to a delivery.
