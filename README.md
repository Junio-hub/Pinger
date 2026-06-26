# Pinger

A lightweight, high-performance, and cross-platform CLI tool designed to monitor network latency using both **ICMP (Ping)** and **TCP handshake** methods. Packed with beautiful terminal colors and smart ASN/ISP lookup.

---

## Features

* **Dual Mode:** Seamlessly switch between standard ICMP pings and advanced TCP connection testing.
* **Smart ASN Lookup:** Automatically identifies the ISP, Autonomous System Number (ASN), and country of the target IP using an optimized internal database.
* **Live Metrics:** Real-time tracking of Average/Max latency ($RTT$), packet loss to diagnose network stability instantly.
* **True Cross-Platform:** Native support for both Windows and Linux/Unix environments.
* **Zero Bloat:** Pure C code with no external heavyweight dependencies.

---

## Preview

<p align="center">
  <img src="https://raw.githubusercontent.com/Junio-hub/Pinger/main/preview.png" alt="Pinger CLI Preview" width="700">
</p>

---

### Building from Source

```gitclone
git clone [https://github.com/Junio-hub/Pinger.git](https://github.com/Junio-hub/Pinger.git)
