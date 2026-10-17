# Voice-Command Car

Communication-theory course project: a car driven directly by spoken commands.

- **Arduino Uno** + **Elechouse VR3** speaker-dependent voice-recognition module (pre-trained commands: *go, back, left, right*)
- The Arduino reads the index of the recognised command over serial and drives the motors through an **L298N** H-bridge (see the truth table in `media/`)
- `hardware/voice_control_car.fzz` - Fritzing wiring (open with Fritzing); `media/wiring_diagram.png` is the exported view

The report and slides are not published here (they contain personal data of the team).
