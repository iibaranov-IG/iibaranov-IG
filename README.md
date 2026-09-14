# Igor Baranov

**Broadcast Audio & AoIP Engineer — Open-Source Software Repair**

I help investigate failures where broadcast software, audio networks and equipment
need to work together: MIDI reconnection, PTZ control, OSC feedback, AES67/PTP
synchronization and audio-software integration.

I build [**Broadcast Control Lab (BCL)**](https://github.com/iibaranov-IG/broadcast-control-lab), an independent engineering lab
that turns concrete problems into reproducible checks, focused fixes and reviewable
evidence. My work also includes AoIP audits, routing, redundancy, commissioning and
migration planning for radio and broadcast environments.

[Explore BCL](https://github.com/iibaranov-IG/broadcast-control-lab) ·
[Bring a problem](https://github.com/iibaranov-IG/broadcast-control-lab/issues/new?template=repair-request.yml) ·
[Discuss engineering work](mailto:iibaranov@gmail.com) ·
[Support open-source work](#support-open-source-work)

## Repairs accepted by maintainers

Verified as merged on **14 September 2026**:

| Project | Problem addressed | Upstream result |
| --- | --- | --- |
| PiPedal | Bluetooth MIDI fails to reconnect when the ALSA port appears after its client | [Merged #587](https://github.com/rerdavies/pipedal/pull/587) |
| RtAudio | Unix pthread flags appear in pkg-config metadata for MSVC consumers | [Merged #487](https://github.com/thestk/rtaudio/pull/487) |
| Liquidsoap | Last.fm rejects the default Audioscrobbler HTTP endpoint | [Merged #5404](https://github.com/savonet/liquidsoap/pull/5404) |
| FPP | Missing or malformed PTP management data can falsely indicate lock | [Merged #2942](https://github.com/FalconChristmas/fpp/pull/2942) |

[Read the repair stories and validation limits](https://github.com/iibaranov-IG/broadcast-control-lab#repairs-accepted-by-upstream-maintainers).
Maintainer acceptance, release availability and real-device validation are separate
milestones. The FPP fix does not resolve the separate Pi 4/no-PHC clock issue.

## Where I can help

- **Broadcast audio and AoIP:** Axia Livewire+, LWRP/LWCP, AES67, Dante and AMWA NMOS; interoperability, routing and operational diagnostics.
- **Equipment control:** MIDI/ALSA, OSC and VISCA over TCP/UDP; connection states, command/reply behavior and reproducible protocol checks.
- **Open-source engineering:** focused bug fixes, build and integration failures, regression tests and clear evidence for maintainers.
- **Broadcast facilities:** commissioning, failure analysis, redundancy and migration planning across mixed-vendor systems.

Field experience includes Telos Alliance / Axia, Barix, SOUND4 and AEQ systems.
Specific device and platform coverage is agreed for each investigation.

## More open-source work

- [AMWA NMOS Testing: handle session-level SDP connection data](https://github.com/AMWA-TV/nmos-testing/pull/907)
- [AES67 Stream Monitor: build native audio modules on matching architectures](https://github.com/philhartung/aes67-monitor/pull/34)
- [Livewire LWRP module: expose all GPI and GPO variables](https://github.com/k2fc/companion-module-livewire-lwrp/pull/2)

## Collaboration

For a software failure, [open a BCL repair request](https://github.com/iibaranov-IG/broadcast-control-lab/issues/new?template=repair-request.yml)
with the device model, software/firmware version, expected behavior, reproduction
steps and your ability to test on the real setup. Remove credentials and private
data from public reports.

For consulting, integration work or a scoped engineering investigation,
[email iibaranov@gmail.com](mailto:iibaranov@gmail.com). We establish scope,
available evidence and acceptance criteria before committing to a delivery.

## Support open-source work

If this work has helped your broadcast facility, voluntary donations help fund test equipment, real-device validation, and maintenance.

- [Support via ЮMoney](https://yoomoney.ru/to/41001183423578)
- USDT — Ethereum (ERC-20) or BNB Smart Chain (BEP-20): `0xB04907EC7Fe04647def87C3e65fE3a281cC8cFDD`

Please select **ERC-20 or BEP-20 only** when sending. Other networks are not supported.

<img src="assets/usdt-erc20-qr.svg" alt="QR code for the USDT ERC-20 or BEP-20 address" width="180" />

For urgent commercial or operational requests, email [iibaranov@gmail.com](mailto:iibaranov@gmail.com). I reply promptly on business days.
