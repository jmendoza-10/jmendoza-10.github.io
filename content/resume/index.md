---
title: "Resume"
layout: "single"
url: "/resume/"
summary: "Staff Software Engineer — Embedded Systems, Connectivity, Defense & Aerospace"
ShowToc: true
TocOpen: true
---

## About

Staff Software Engineer with 13 years of experience spanning defense, aerospace, and automotive industries. Background ranges from real-time waveform processing on military radios and aerospace DO-178C avionics to vehicle connectivity and autonomous vehicle telematics. Most recently focused on the 4G/5G connectivity software stack from cellular modem up to cloud transport, where maintaining an always-on connection is the goal at the lowest power consumption — on the order of 10s of mAs.

---

## Experience

### Staff Software Engineer
**General Motors Co.** · Phoenix, AZ · July 2017 — March 2026

- Wrote middleware software interfacing with Qualcomm SA525 5G Modem APIs to establish cellular data connectivity for the vehicle, designed as an always-on data connection in low power modes. Supported cloud transport protocols for remote commands and emergency notifications.
- Team lead of 10+ senior and junior software engineers developing Connectivity Hub Module (CHM) Cellular, Wi-Fi, and Bluetooth capabilities and integration with the Infotainment ECU.
- Co-inventor on U.S. Patent Application No. 19/547,483 — *Method and System to Reduce Packet Latency for Wireless Communications with Vehicles* (recorded February 2026).
- Wrote middleware software that established 4G/5G cellular network connectivity for the OnStar Telematics Module (Gen12) and supported emergency calls with extensive connection retry logic for establishing an OnStar advisor connection.
- Developed software stack for the Multi Carrier Telematics Module (MCTM) on Cruise Autonomous Vehicles, splitting data packets across 3 Qualcomm SA415M 4G modems and re-ordering them on the backend of IPSec tunnels, achieving ~45 MB theoretical upload throughput.
- Implemented a GStreamer pipeline with RTP transport and ALSA audio integration for the MCTM, enabling real-time media streaming from the autonomous vehicle to the backend operations center.
- Supported eCall and Next Generation eCall (NG eCall) emergency calling systems over IMS/LTE by understanding 3GPP system requirements (TS 26.267/TS 26.268) and implementing supporting application software for establishing emergency calls with priority bearer handling.
- Performed eCall and commercial data link testing using the Anritsu cell simulator for hardware-in-the-loop cellular network validation.
- Built a local web server to support vehicle controls for riders in-vehicle via an Android app UI.
- Six Sigma Black Belt certified (2020).

### Engineer II Software
**Honeywell Aerospace Inc.** · Phoenix, AZ · March 2016 — July 2017

- Embedded application design, development, and testing to log data from HTF ECUs for Cessna aircraft engine control units in C#.
- Engineering software development of HTF ECU for test development in C++.
- Product-line configuration management plan implementation for systems and software per ARP4754A, DO-178C, and DO-331.
- Product-line systems and software requirements implementation in DOORS.
- Six Sigma Green Belt certified (2016).

### Embedded Software Engineer II
**Raytheon Co.** · Tucson, AZ · May 2015 — March 2016

- Software integration testing in a classified lab housing Hardware-in-the-Loop (HIL) systems.
- Ran Formal Qualification Tests (FQTs) on the Small Diameter Bomb II using HIL testing and verification of full project requirements linked to Python scripts that indicated pass/fail for each requirement.
- Secret Clearance.

### Software Engineer I
**General Dynamics Mission Systems Inc.** · Scottsdale, AZ · May 2013 — May 2015

- Software development on BOWMAN ComBAT system. Software maintenance on HMS platform.
- Software design and implementation of the Integrated Waveform (IW) on the Digital Modular Radio (DMR) — a Software Defined Radio supporting a broad range of firmware protocols from SATCOM to handheld radios, featuring a GD proprietary crypto chip for converting communications from one waveform to another.
- Implemented multi-thread algorithms on VxWorks for real-time communication of IW.
- Development of network acquisition firmware to interface with an FPGA for signal processing.
- Developed overnight Software/Firmware testbench for energy detection testing.
- Wrote approximately 10K+ SLOC and reviewed 50K+ SLOC.

---

## Projects

### [Mission Control Dashboard](https://github.com/jmendoza-10/mission-control-dashboard)
Factorio-inspired 8-bit retro dashboard for monitoring AI agent scheduled tasks. Single-file HTML app with pixel art sprites, animated conveyor belts, CRT themes, 8-bit sound effects, day/night cycle, interactive task control with auto-stop timer, and a zero-dependency Python server for live status updates.

`HTML/CSS/JS` `Canvas API` `Web Audio API` `Pixel Art` `Python` `NES.css`

### [Axon Nervous System — POC](https://github.com/jmendoza-10/axon-nervous-system-poc)
WiFi CSI (Channel State Information) based presence and motion sensing proof of concept. ESP32-S3 boards extract 64-subcarrier channel state from WiFi signals to detect people through walls. Sensor nodes communicate over a Reticulum encrypted mesh network (X25519 + AES-128 E2E encryption) with store-and-forward multi-hop routing, transport abstraction across Wi-Fi and MQTT, and a real-time command dashboard with SHA-256 tamper-evident cryptographic evidence chain logging.

`C` `Python` `ESP32/ESP-IDF` `WiFi CSI` `Mesh/MANET Networking` `Encrypted Transport` `Raspberry Pi`

### [BitNet — Apple Silicon Fork](https://github.com/jmendoza-10/BitNet)
Fork of Microsoft's BitNet 1-bit LLM inference framework with fixes for Apple Silicon (M-series). Resolved LLVM interleaved load issues that caused garbled output on ARM Macs, documented multi-core build optimizations, and created a reproducible setup guide for the full inference pipeline.

`Python` `C++` `LLM Inference` `Apple Silicon` `ARM`

### [UDS over IP](https://github.com/jmendoza-10/uds_over_ip)
C++ implementation bridging UNIX domain sockets with TCP/IP network communication. Enables data relay between local UDS endpoints and remote IP clients using multithreaded socket programming.

`C++` `Sockets` `Networking` `Multithreading`

### [QR Code STL Generator](https://github.com/jmendoza-10/qr-code-stl-generator)
Tool to generate 3D-printable QR codes as STL files for multi-color printing. Encodes WiFi credentials or URLs and uses Blender for 3D object generation.

`Python` `Blender` `3D Printing`

---

## Education

- **M.S., Computer Engineering** — Arizona State University (2013–2016)
- **B.S.E., Computer Systems Engineering** — Arizona State University (2011–2013)
- **B.S.E., Mechanical Engineering (Energy & Environment)** — Arizona State University (2006–2012)

---

## Skills

`C/C++` `C#` `Python` `Lua` `Embedded Systems` `5G/LTE` `Wi-Fi/Bluetooth` `Mesh/MANET Networking` `RTP/Real-Time Media` `3GPP (eCall/NG eCall)` `QoS/Priority Bearers` `Encrypted Transport (AES/TLS)` `Low-Power Design` `Socket Programming` `Software Defined Radio` `Linux/Android` `ARM Architecture` `RTOS` `DO-178C` `Anritsu Cell Simulator` `Hardware-in-the-Loop` `Team Leadership` `Six Sigma Black Belt` `OpenCV` `Git`

---

## Patents

- **Method and System to Reduce Packet Latency for Wireless Communications with Vehicles** — U.S. Patent Application No. 19/547,483 · Recorded February 23, 2026

## Publications

- **Comparison of Four Different Types of Ferromagnetic Materials for Fault Current Limiter Applications** — IEEE Transactions on Power Delivery, February 2013
- **A Neodymium Permanent Magnet Fault Current Limiter for Use in the FREEDM Project** — IEEE PES Innovative Smart Grid Technologies, October 2012

---

## Languages

English · Spanish
