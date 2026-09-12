# Build Log

## 2026-09-12 — Project Initialization

### Completed

- Created and published the GitHub repository
- Defined the initial system requirements
- Documented the proposed system architecture
- Separated the shift light and fuel display into distinct modules
- Planned an OBD-II pass-through via Y-splitter for continued diagnostic access

### Thoughts

- Use passive broadcast CAN data for low-latency RPM information
- Mount the shift light on the instrument-cluster hood
- Mount the range and MPG display separately
- Use one central controller to process vehicle data
- Preserve an accessible OBD-II diagnostic connection
- Still just trying to figure out github/nvim notation

### Next Steps

- Configure the Feather M4 CAN Express
- Establish USB communication with the MacBook
- Capture CAN traffic from the BRZ
- Validate the engine RPM signal
