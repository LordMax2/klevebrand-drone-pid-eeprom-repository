# Klevebrand Drone PID EEPROM Repository

C++ library for storing and loading PID tuning values in EEPROM — part of the Klevebrand drone ecosystem.

Works hand-in-hand with [Klevebrand All-Drone Controller](https://github.com/LordMax2/klevebrand-all-drone-controller) to save the self-tuned PID gains persistently, so your drone remembers its best settings even after power-off.

- Lightweight EEPROM read/write for PID parameters
- Simple API to save/load gains (Kp, Ki, Kd, etc.)
- Built for microcontrollers (PlatformIO support)
- Keeps your auto-tuned stability across reboots

Just include it, and let the core controller use persistent storage for even better long-term performance.

MIT License
