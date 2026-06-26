# Recovery 

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
![Status](https://img.shields.io/badge/status-active-green.svg)

Design logs, calculations, and flight records for our parachute systems and ejection mechanisms. Every rocket we build has to come back down safely — this repo documents how we make that happen, mission by mission.

We share this openly because recovery is one of the least-documented aspects of student rocketry. A lot of teams figure out motors and avionics from available resources, then lose the rocket on descent anyway. We want to change that.

We're a student rocketry association from Anand, Gujarat, building towards 100 km — one mission at a time.

---

## What's in here

```
recovery/
├── missions/
│   ├── M001-HomiSII/
│   │   ├── parachute/
│   │   │   ├── design.md              # Sizing calculations, material, Cd values used
│   │   │   ├── deployment-tests.md    # Ground deployment tests before flight
│   │   │   └── flight-log.md          # How recovery actually performed
│   │   ├── ejection-system/
│   │   │   ├── design.md              # Mechanism design, spring/piston specs, shear pin sizing, release trigger
│   │   │   ├── ground-tests.md        # Actuation tests, deployment force measurements, release threshold tests
│   │   │   └── flight-log.md          # Deployment altitude, mechanism condition post-flight, recovery outcome
│   │   └── M001-recovery-summary.md   # Overall outcome — what worked, what didn't
│   └── M002/
└── resources/
    ├── parachute-sizing/              # Sizing methodology and Cd values we use
    ├── packing-procedure/             # How we fold and pack chutes, step by step
    └── safety-protocols/              # Ejection system handling protocols
```

## Contributing

Recovery has more edge cases than any other system on the rocket. Small details in packing technique, charge sizing, and deployment timing matter enormously — and most of them are learned the hard way. If you've solved a problem we're still working through, or have data that would sharpen our methodology, we'd genuinely like to hear from you.

[💬 Discussions](../../discussions)

---

## License

This work is licensed under [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).

You are free to use, adapt, and build upon this documentation for any purpose as long as you give appropriate credit to [Association Name]. See [LICENSE](LICENSE) for full terms.

---

## About Us

We're a student rocketry association from Anand, Gujarat. This repository is part of our commitment to open-source rocketry education. Everything we learn, we share.

[🔗 All Repos](https://github.com/[org-name]) · [💬 Discussions](../../discussions)
