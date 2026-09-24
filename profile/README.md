<p align="center">
  <img src="https://raw.githubusercontent.com/Kyntex-org/.github/main/profile/assets/kyntex-logo.jpg" alt="Kyntex" width="720">
</p>

Kyntex is an independent wearable-sensing project built on one conviction:
training data is only worth showing if it can be trusted. Most wearables render
attractive charts without answering whether the device was fitted correctly, or
whether the session was captured without silent data loss. Kyntex is engineered
from the sensor up to answer both.

## What Kyntex is

A working, end-to-end wearable system: Nordic nRF54L15 firmware on Zephyr RTOS,
a custom versioned BLE protocol carrying recording-integrity metadata, and two
companion applications — a native SwiftUI iOS app and a dependency-free Web
Bluetooth dashboard. The prototype senses motion and band fit, classifies
activity on-device, and preserves long sessions durably for later analysis.

Engineered by [Ben Harris](https://github.com/BenHarris11), co-founder and sole
engineer — firmware, protocol, applications, and custom PCB design. Public
materials are organized for engineering review, while production firmware,
calibration values, and sensitive hardware data remain private.

The longer-term research direction is tendon-response sensing: using the band to
say something useful about tissue behavior, not just body movement. That work is
experimental and is not a capability of the current prototype.

## Engineering focus

- Nordic nRF54L15 firmware using nRF Connect SDK and Zephyr
- versioned BLE telemetry with recording-integrity metadata
- durable, bounded storage for long training sessions
- native SwiftUI, ActivityKit, CoreBluetooth, and dependency-free web applications
- guided personal calibration with separate motion and landing-impact load
- responsible separation between engineering metrics and medical claims

## Repositories

- [**Kyntex**](https://github.com/Kyntex-org/Kyntex) — product overview,
  system architecture, hardware documentation, and development roadmap
- [**Kyntex Technical Public**](https://github.com/Kyntex-org/Kyntex-Technical-Public)
  — tested embedded-C portfolio, hardware-free dashboard demonstration,
  [system architecture](https://github.com/Kyntex-org/Kyntex-Technical-Public/blob/main/docs/system-architecture.md),
  and [iOS companion case study](https://github.com/Kyntex-org/Kyntex-Technical-Public/blob/main/docs/ios-companion.md)

## Current companion experience

The native iOS prototype uses a restrained black, white, and blue interface
centered on the new Kyntex mark. It provides a useful movement and impact
summary from the first recorded session, then adds personal-baseline context
after enough quality sessions are available. The app includes guided setup and
personal calibration, automatic session capture, visible band battery and fit,
lock-screen/Dynamic Island Live Activity, session recaps, and longer-term
history. Knee Load and Impact Exposure are presented as training proxies rather
than direct measurements of joint force or injury risk.

## Hardware portfolio

Kyntex includes a fabricated custom NINA-B302/nRF52 PCB, designed in KiCad and
Altium. Initial bring-up has verified power and J-Link/SWD access, while several
sensor interfaces remain in active debugging. Review the public
[hardware design documentation](https://github.com/Kyntex-org/Kyntex/blob/main/docs/hardware/README.md)
or the
[Altium documentation workspace](https://github.com/Kyntex-org/Kyntex/blob/main/docs/hardware/altium/README.md).

Active production work is maintained privately while it is under development.
Public repositories contain deliberately selected, non-proprietary material.

## Project status

Kyntex is an active engineering prototype being driven toward a real product.
The software stack works end to end today, including signed Bluetooth firmware
updates. Hardware refinement and multi-subject metric validation remain active
work and are documented as such rather than implied to be finished.

Kyntex is not a medical device and is not intended to diagnose, treat, prevent,
or predict injury.

Created and maintained by [Ben Harris](https://github.com/BenHarris11).
