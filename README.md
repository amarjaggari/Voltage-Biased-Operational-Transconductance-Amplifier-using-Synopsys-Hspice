# Voltage-Biased-Operational-Transconductance-Amplifier-using-Synopsys-Hspice
Designed and characterized voltage biased operational Transconductance Amplifier (OTA) using Synopsys Hspice for well defined transconductance(Gm) and low power applications
# Voltage-Biased Operational Transconductance Amplifier (OTA)

A high-performance voltage-biased Operational Transconductance Amplifier designed for analog integrated circuits.

## 📋 Overview

This repository contains the complete design of a voltage-biased OTA including:
- Schematic design and simulation files
- Layout implementation
- Characterization scripts
- Application examples
- Documentation and theory

## ✨ Features

- **Wide tuning range** via bias voltage control
- **High output impedance**
- **Low power consumption**
- **Rail-to-rail operation** (optional)
- **Process-corner tolerant design**
- **Compact layout area**

## 🛠️ Technical Specifications

| Parameter | Value | Unit |
|-----------|-------|------|
| Transconductance (Gm) | 100u - 5m | S |
| Bandwidth | 100 - 500 | MHz |
| Power Supply | 1.8 - 3.3 | V |
| Power Consumption | 0.1 - 5 | mW |
| Output Swing | ±(VDD-0.3) | V |
| PSRR @ 1MHz | > 60 | dB |
| CMRR | > 70 | dB |

## 🚀 Quick Start

### Simulation
```bash
cd src/scripts
./simulate.sh
