# Shadowsocks Global Proxy Setup

This repository demonstrates a **Shadowsocks global proxy setup** for bypassing network restrictions on PC and Android devices. It includes a dummy configuration file and a clear architecture overview.

---

## Project Overview

- **Purpose:** Connect your PC or Android device to the Internet securely via a VPS running Shadowsocks.
- **Mode:** Global proxy (all traffic routed through VPS).
- **Supported Devices:** Windows, macOS, Linux, Android.

---

## Architecture Diagram

```mermaid
graph TD;
    A[PC / Android] --> B[Shadowsocks Client];
    B --> C[VPS: Shadowsocks Server];
    C --> D[Internet];
