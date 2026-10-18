# Recovery

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
![Status](https://img.shields.io/badge/status-active-green.svg)

Design logs, calculations, test and flight records for the parachute and ejection systems of the Indian Students Rocketry Association's rockets. Every rocket we build has to come back down safely; this repo documents how we try to make that happen, mission by mission.

We share this openly because recovery is one of the least-documented parts of student rocketry. A lot of teams figure out motors and avionics, then lose the rocket on descent anyway.

We're a student rocketry association from Anand, Gujarat, building towards 100 km, one mission at a time.

---

## Missions

A **mission** is one rocket. Mission numbers match the [Propulsion](https://github.com/Indian-Students-Rocketry-Assocation/Propulsion) and [Electronics](https://github.com/Indian-Students-Rocketry-Assocation/Electronics) repos.

| Mission | Rocket | Status | Recovery |
|---|---|---|---|
| M001-SRM | SRM | Flew 2024-10-20. Motor exploded on ignition | Not recorded |
| M002-HomiSI | Homi Shatam I | Flew 2025-03-11. Motor exploded within 1 s | Not recorded |
| M003-HomiSII | Homi Shatam II | In development, not yet flown | Servo ejection at apogee (MG90S, flight computer in [Electronics](https://github.com/Indian-Students-Rocketry-Assocation/Electronics/tree/main/Missions/M003-HomiSII)). Never tested with a packed chute |

**Nothing is committed here yet.** No recovery records survive from M001 or M002, and the M003 parachute and ejection mechanism are not yet documented. Mission folders will be added as that work is written up.

## Layout

```
Missions/
  M00N-<Rocket>/
    README.md            mission overview: what flew, what happened
    Parachute/           sizing, material, Cd used, deployment tests
    Ejection/            mechanism design, ground tests
Resources/
  ParachuteSizing/       sizing method and the Cd values we use
  Packing/               how we fold and pack chutes
```

Each mission `README.md` should say honestly what was tested, what wasn't, and what happened in flight.

---

## Contributing

Recovery has more edge cases than any other system on the rocket. Small details in packing, deployment timing and mechanism design matter, and most of them are learned the hard way. If you've solved a problem we're still working through, we'd like to hear from you.

[💬 Discussions](../../discussions) · [🔗 All ISRA repos](https://github.com/Indian-Students-Rocketry-Assocation)

## License

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/): use, adapt and build on this for any purpose, with credit to the Indian Students Rocketry Association. See [LICENSE](LICENSE).
