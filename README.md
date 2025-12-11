# Space LEAF Hybrid Vehicle Sim

A Node + TypeScript simulation of a hybrid submersible/spacecraft with:
- Autopilot micro-corrections and diagonal vector control
- Ultimate avoidance maneuver
- Spatial awareness and outer-part retraction
- Gyroscopic bubble stabilization with redundancy and cross-rotation blending
- Secure satellite relay, GPS heartbeat, distress beacon signature
- Airlock validation, resource telemetry, and voice report pipeline
- Long-horizon (15-year) stress-test CLI

## Requirements
- Node 18+
- npm

## Install
npm install

## Build
npm run build

## Test
npm test

## Run simulation (prints KPIs)
npm run sim

## Structure
See src/ for modular subsystems and tests/ for unit test stubs.

## Notes
- Crypto and hardware drivers are stubbed for simulation purposes.
- Beacon Signature 1.0 is included for recognizable distress signaling.
- Extend Vehicle with real hardware integrations as needed.
