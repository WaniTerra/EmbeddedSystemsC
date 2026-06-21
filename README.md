# Embedded Systems & C Portfolio

This repository contains a collection of low-level systems programming, avionics simulations, and physics engine mechanics written entirely in C.

* **Core** : A custom 16-bit virtual CPU emulator simulating RAM, registers, and the Fetch-Decode-Execute cycle using pure C bitwise operations.
* **RocketSystem** : A multithreaded client-server architecture using POSIX threads and custom ring buffers for real-time UDP telemetry transmission.
* **RocketRadarSystem** : A 2D kinematics and radar targeting engine featuring object pooling and AABB collision detection via SDL2.
* **PhysicEngine** : A custom 2D physics engine built from scratch focusing on Newtonian kinematics and freefall simulation.
* **UDPRadarSystem** : An IPC-based distributed avionics simulation utilizing UDP sockets, byte-level struct packing, and XOR checksums.
* **UARTRadarSystem** : A serial port (UART) simulation utilizing state machines to parse continuous byte-streams and validate data integrity.
