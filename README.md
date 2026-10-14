# Budget Go-Kart: Fast on €150

A weekend build with one goal: **get as much speed as possible out of the smallest budget.** The frame comes from an old pedal Kettcar, the engine is a 212 cc four-stroke, and everything was built and debugged by two people in their spare time.

<!-- Add once available:
![Finished kart](images/hero.jpg)
-->

## At a Glance

| | |
|---|---|
| **Goal** | Fastest possible kart on a minimal budget |
| **Budget** | ~€150 |
| **Team** | 2 people |
| **Build time** | Occasional weekends |
| **Frame** | Reused Kettcar chassis |
| **Engine** | 212 cc, 4-stroke, 7.5 hp |
| **Drive** | Centrifugal clutch (10 T) → chain → 38 T rear sprocket (3.8 : 1) |
| **Top speed** | ~70 km/h (GPS verification pending) |
| **Weight** | TBD |
| **Status** | Running; rear axle and chain being reworked |

## Key Engineering Problem

The rear axle originally ran directly in the Kettcar frame. Under engine load it wore into the frame material. The fix: **two pillow block bearings** mounted at the rear, so the axle is carried by proper bearings instead of the frame tubing. Details in [docs/problems-and-solutions.md](docs/problems-and-solutions.md).

## Documentation

| Document | Content |
|---|---|
| [docs/specifications.md](docs/specifications.md) | Technical data and drivetrain calculations |
| [docs/build-log.md](docs/build-log.md) | How the kart was built |
| [docs/problems-and-solutions.md](docs/problems-and-solutions.md) | Failures, root causes, fixes |
| [docs/bill-of-materials.md](docs/bill-of-materials.md) | Parts and cost |
| [docs/measurements.md](docs/measurements.md) | Weight, speed, runtime tests |
| [docs/safety.md](docs/safety.md) | Brakes, steering, protective measures |
| [images/](images/README.md) | Photo list |
| [cad/](cad/README.md) | Drawings and CAD files |

## Open Items

- [ ] Rework rear axle
- [ ] Fix chain
- [ ] Measure weight
- [ ] Verify top speed with GPS
- [ ] Add photos and video
- [ ] Complete bill of materials
- [ ] Document brakes and safety setup

## Author

Built by [Your Name] together with a friend. Part of my engineering portfolio, along with an industrial-component 3D printer and an ESP32 universal remote.

[LinkedIn](https://www.linkedin.com/in/your-profile) · [GitHub](https://github.com/your-username)

## License

See [LICENSE](LICENSE).
