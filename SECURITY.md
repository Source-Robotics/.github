# Security policy

## Reporting a problem

Please report security problems privately, not in a public issue, discussion or Discord channel:

- **On GitHub:** open the repository's **Security** tab and choose **Report a vulnerability**. Only the maintainers
  see the report.
- **By email:** info@source-robotics.com.

Name the product and its hardware version, the firmware or software version, the steps that show the problem and
what it could lead to. One problem per report.

Report a safety hazard in a design the same way, for example a fault that can make a robot move on its own, so we
can warn the people who have one before it is public.

## What this covers

The firmware of PAROL6, the grippers and the motor drivers, the bootloader, the Python libraries, the PAROL6
commander, RCB-Runtime and [Motor GUI](https://motorgui.com/). Sim2Bot has its own policy, in
[sim2bot-python](https://github.com/Source-Robotics/sim2bot-python/blob/main/SECURITY.md). For the shop at
source-robotics.com, email us.

Not a vulnerability: the CAN, UART and USB links accept commands from whatever is connected to them. That is how
they are built; keep them on hardware you control.

## Supported versions

The latest release of each firmware, library and program. Fixes go into the next release.

## What happens next

- We confirm your report within three days and keep you informed until it is fixed.
- We keep the report and your details confidential.
- When it is fixed, we credit you in the release notes or the advisory, if you want.

## Safe harbor

We will not take legal action against research done in good faith: on hardware and systems you own or may test,
without harm to people, hardware or data, and with reasonable time for us to fix the problem before you publish
it.

## Safety and liability

Building and running a robot has risks of its own. See the [safety and liability disclaimer](SAFETY_AND_LIABILITY.md),
the `SAFETY_WARNING_AND_DISCLAIMER.md` in each product's repository and the safety chapter of its
[manual](https://docs.source-robotics.com/).
