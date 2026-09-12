<p align="center">
  <img src="https://raw.githubusercontent.com/Kyntex-org/Kyntex/main/assets/logo/Kytex%20Logo.png" alt="Kyntex — Wearable Sensing Technology" width="760">
</p>

Kyntex is an independent wearable-sensing project exploring how embedded
systems and long-session motion data can give athletes clearer feedback about
training activity and device fit.

## What we are building

The current prototype combines motion sensing, band-fit monitoring, Bluetooth
Low Energy telemetry, and companion applications for the web and iOS. The
engineering work emphasizes reliable data capture, explainable metrics, and a
path from development hardware toward a production-ready embedded platform.

The project is led by Ben Harris, Kyntex co-founder and technical lead. Public
materials are organized for engineering review while production firmware,
calibration details, and sensitive hardware data remain private.

Longer-term research may investigate tendon-response measurements. That work is
experimental and is not a capability of the current prototype.

## Engineering focus

- Nordic nRF54L15 firmware using nRF Connect SDK and Zephyr
- versioned BLE telemetry with recording-integrity metadata
- durable, bounded storage for long training sessions
- native SwiftUI and dependency-free web applications
- responsible separation between engineering metrics and medical claims

## Repositories

- [**Kyntex**](https://github.com/Kyntex-org/Kyntex) — product overview,
  system architecture, hardware documentation, and development roadmap
- [**Kyntex Technical Public**](https://github.com/Kyntex-org/Kyntex-Technical-Public)
  — interactive software portfolio and hardware-free dashboard demonstration

## Hardware portfolio

Kyntex includes a fabricated custom NINA-B302/nRF52 PCB. Initial bring-up has
verified power and J-Link/SWD access, while several sensor interfaces remain in
active debugging. Review the public
[hardware design documentation](https://github.com/Kyntex-org/Kyntex/blob/main/docs/hardware/README.md)
or the
[Altium documentation workspace](https://github.com/Kyntex-org/Kyntex/blob/main/docs/hardware/altium/README.md).

Active production work is maintained privately while it is under development.
Public repositories contain deliberately selected, non-proprietary material.

## Project status

Kyntex is an engineering prototype, not a medical device. It is not intended to
diagnose, treat, prevent, or predict injury.

Created and maintained by [Ben Harris](https://github.com/BenHarris11).
