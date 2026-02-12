# CamPhish – Browser Permission Security Awareness Lab

> ⚠️ This project is strictly for cybersecurity education and controlled lab environments only.  
> Do NOT use against individuals without explicit written authorization.

---

## Overview

CamPhish is a **cybersecurity awareness and research demonstration project** that illustrates how browser permission prompts (camera and location access) can be abused through social engineering techniques.

The purpose of this project is to help:

- Students understand browser security risks  
- Security researchers demonstrate permission-based attacks  
- Organizations train employees about phishing awareness  
- Penetration testers simulate controlled attack scenarios (with authorization)

This project is NOT intended for unauthorized surveillance or illegal activities.

---

## Educational Objective

Modern browsers request explicit permission before accessing:

- 📷 Camera
- 🎤 Microphone
- 📍 GPS Location

However, attackers can trick users into granting permission through deceptive webpages.

This project demonstrates:

- How social engineering influences permission acceptance
- How browser APIs expose camera and geolocation data
- Why user awareness is critical in cybersecurity

---

## Demonstration Templates

The project includes sample web templates used to simulate realistic user engagement scenarios:

- Festival Greeting Page
- Live Streaming Page
- Online Meeting Page (Beta)

These templates are meant for **controlled demonstrations only**.

---

## Technical Components (For Learning)

- HTML (Frontend interface simulation)
- PHP (Server-side logging simulation)
- Shell scripting (Automation & cleanup)
- Tunneling tools (For lab-based remote testing)

---

## Lab Environment Setup (Authorized Testing Only)

> ⚠️ Use only in a controlled environment such as:
> - Your own devices
> - Virtual machines
> - Explicitly authorized penetration testing targets

Requirements:
- PHP
- wget
- unzip

Example setup (Linux environment):

```bash
sudo apt-get install php wget unzip
