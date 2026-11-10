# IoT Simulator (Free)

A concept for a full-surface, offline-first IoT simulator that can run anywhere with Podman.

## Status

**Archived concept.** This repository contains the idea only; there is no implementation yet. It is archived so the account stays focused on active projects.

## The idea

The goal was a self-contained simulator covering devices, protocols, telemetry, and dashboards so students and testers could practise IoT work without cloud accounts or physical hardware. Everything would run locally in containers.

## If you want to build it

Open an issue or start a new repository from this README. A useful first milestone would be:

1. A device registry with simulated sensors and actuators.
2. MQTT and HTTP ingestion endpoints.
3. A small dashboard showing live telemetry.
4. A Podman Compose file that starts the whole stack offline.

## License

GPL-3.0. See `LICENSE`.