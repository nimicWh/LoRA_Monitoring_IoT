# LoRa IoT Platform

An Internet of Things (IoT) project demonstrating long-range wireless communication using LoRa technology and The Things Network.

> **Project Year:** 2017
> **Status:** Completed (Archived Project)

## Overview

This project was developed in **2017** to evaluate the capabilities of **LoRa (Long Range)** communication for low-power IoT applications.

The project explored wireless communication between LoRa devices and cloud platforms while evaluating signal coverage, network reliability, and long-range communication performance.

This project was originally shared on my X (formerly Twitter) account:

**https://x.com/NimicMe**

---

## About LoRa

LoRa (Long Range) is a wireless radio communication technology that provides long-range, low-power communication for Internet of Things (IoT) devices.

Unlike Wi-Fi or Bluetooth, LoRa is designed for transmitting small amounts of data over several kilometres while consuming very little power.

Key characteristics include:

* Long-range wireless communication
* Low power consumption
* Chirp Spread Spectrum (CSS) modulation
* Frequency hopping to improve resilience against interference
* Operates in the license-free ISM frequency bands

Operating frequencies vary by region. For example, Singapore uses the **923 MHz ISM band**.

---

## Project

* Evaluate long-range LoRa communication
* Deploy IoT devices on a LoRaWAN network
* Test cloud connectivity through The Things Network
* Compare LoRa with other LPWAN technologies such as Sigfox
* Gain hands-on experience with Pycom development boards

---

## Project Architecture

```text
Sensors
    │
    ▼
Pycom LoPy / FiPy
    │
    ▼
LoRaWAN Gateway
    │
    ▼
The Things Network (TTN)
```

---


## 1. Pycom LoPy Development Board

The project used the **Pycom LoPy** development board, which provides LoRa connectivity for rapid IoT prototyping and development.

<img width="1536" height="2048" alt="pycom1" src="https://github.com/user-attachments/assets/46f2658d-9daf-426f-9ff7-45084c0c226f" />

---

## 2. The Things Network (TTN)

The LoPy device successfully transmitted data through a LoRaWAN gateway to **The Things Network (TTN)**, demonstrating end-to-end communication over the LoRa network.

<img width="2048" height="1536" alt="pycomgateway" src="https://github.com/user-attachments/assets/87e524c9-d224-488d-af3a-5f6082c0a9c9" />

<img width="2048" height="1536" alt="pycomgateway1" src="https://github.com/user-attachments/assets/07b2a855-9bc4-4061-82c6-077139d07425" />

---

## 3. Pycom FiPy Development Board

The project also explored the **Pycom FiPy**, a versatile multi-network IoT development board supporting multiple wireless communication technologies on a single platform.

Supported connectivity includes:

* LoRa
* Sigfox
* NB-IoT
* LTE-M
* Wi-Fi
* Bluetooth

<img width="675" height="900" alt="FiPy Board" src="https://github.com/user-attachments/assets/7a3768a8-8e6f-4b4b-8c86-ea08043b1ce2" />

---

# Technologies Used

* LoRa
* LoRaWAN
* Pycom LoPy
* Pycom FiPy
* The Things Network (TTN)
* Chirp Spread Spectrum (CSS)
* ISM 923 MHz Band

---

# Outcomes

* Understanding LoRa and LoRaWAN architecture
* Configuring LoRaWAN devices and gateways
* Deploying IoT devices using Pycom hardware
* Evaluating long-range wireless communication performance
* Comparing LPWAN technologies including LoRa and Sigfox
* Building cloud-connected IoT solutions

---

# Comparison with Sigfox

| Feature     | LoRa / LoRaWAN                            | Sigfox                                   |
| ----------- | ----------------------------------------- | ---------------------------------------- |
| Network     | Open standard                             | Proprietary                              |
| Deployment  | Private or public                         | Public operator network                  |
| Modulation  | Chirp Spread Spectrum (CSS)               | Ultra Narrow Band (UNB)                  |
| Flexibility | High                                      | Limited                                  |
| Typical Use | Smart cities, industrial IoT, agriculture | Asset tracking, environmental monitoring |

---

## Notes

Although this project was completed in **2017**, it provided practical experience with LPWAN technologies and cloud-connected IoT systems. The knowledge gained remains applicable to modern IoT deployments using LoRaWAN and related low-power wireless technologies.
