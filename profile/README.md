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
  system architecture, and development roadmap
- [**Kyntex Technical Public**](https://github.com/Kyntex-org/Kyntex-Technical-Public)
  — interactive software portfolio and hardware-free dashboard demonstration

Active production work is maintained privately while it is under development.
Public repositories contain deliberately selected, non-proprietary material.

## Project status

Kyntex is an engineering prototype, not a medical device. It is not intended to
diagnose, treat, prevent, or predict injury.

Created and maintained by [Ben Harris](https://github.com/BenHarris11).
