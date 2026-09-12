# System Requirements

## Goal

Build a modular CAN-based telemetry system for a 2014 Subaru BRZ.

## Components

- Gauge-hood RPM shift light
- Separate range and average-MPG display
- Central CAN telemetry controller
- OBD-II diagnostic pass-through

## Requirements

- No visible controls
- Low-latency RPM indication
- Automatic brightness adjustment
- Removable, non-destructive mounting
- External diagnostic tools must remain usable
- Invalid or stale RPM data must turn the shift lights off
- The system must not interfere with normal vehicle operation

## Open Questions

- Which fuel-related signals are available?
- What is the update rate of the RPM CAN frame?
- Where should the fuel display be mounted?
- Can transmission mode and selected gear be decoded?
