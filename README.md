<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.svg">
  <img src="assets/header-light.svg" alt="Fauzan Azhima, Information Technology student at Universitas Jenderal Achmad Yani Yogyakarta" width="100%">
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/typing-dark.svg">
  <img src="assets/typing-light.svg" alt="What I build: a SaaS laundry POS, CNN waste detection, ESP32 LoRa water gate, Wazuh SIEM lab" width="75%">
</picture>

I'm an Information Technology student who likes taking a project the whole way: from the database and the API, to the app people tap on, to the server it runs on. Lately that has meant a point-of-sale SaaS for laundry businesses, a computer vision model for spotting waste piles, and an IoT water gate for a farmers' group.

## What I work on

<table>
<tr>
<td width="50%" valign="top">

**Full-stack web & mobile**<br>
React and Tailwind on the front, NestJS or Express with PostgreSQL behind it. I package the same web app for Android with Capacitor and for desktop with Tauri, and wire in payments through Midtrans.

</td>
<td width="50%" valign="top">

**Computer vision**<br>
Training image classifiers with TensorFlow/Keras (MobileNet), explaining predictions with Grad-CAM heatmaps, and experimenting with YOLO for detection. Served through Flask and Docker.

</td>
</tr>
<tr>
<td width="50%" valign="top">

**IoT & embedded**<br>
ESP32 nodes that talk over LoRa, sync with Firebase Realtime Database, and drive motors with the safety logic (limit switches, timeouts, fault lock) kept on the device itself.

</td>
<td width="50%" valign="top">

**Security & infrastructure**<br>
Linux servers on VPS, Nginx, Cloudflare Tunnel, and a Wazuh SIEM lab that monitors a web server and an MDM platform. I designed the lab's network topology.

</td>
</tr>
</table>

## Featured projects

<table>
<tr>
<td width="50%" valign="top">

### CuciKuy · Laundry POS
Multi-tenant SaaS for laundry shops with owner and cashier roles, branch management, and subscription tiers enforced at the API level. Runs on web, Android, and desktop from one codebase.

`React` `NestJS` `TypeORM` `PostgreSQL` `Capacitor` `Tauri` `Midtrans`

<sub>Source is private. Happy to demo on request.</sub>

</td>
<td width="50%" valign="top">

### [Waste Vision](https://github.com/FauzanAzhimaa/waste-detection)
Classifies an area as clean, light pile, or heavy pile, highlights the reason with a Grad-CAM heatmap, and suggests a handling priority per location. Includes training scripts, evaluation, and deployment notes.

`TensorFlow` `Keras` `Grad-CAM` `YOLO` `Flask` `Docker`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### Smart Water Gate
IoT control and monitoring for an irrigation gate. One ESP32 acts as the Wi-Fi/Firebase gateway, the other drives the motor over LoRa. Supports auto and manual modes with a live web dashboard.

`ESP32` `LoRa` `Firebase` `Web dashboard`

</td>
<td width="50%" valign="top">

### Minimarket Management System
Point of sale with admin and cashier roles, batch stock tracking with expiry dates, sales reports, and Telegram alerts for products about to expire.

`Python` `Flask` `MongoDB` `Telegram Bot`

<sub>Source is private. Happy to demo on request.</sub>

</td>
</tr>
</table>

<details>
<summary><b>Earlier projects</b></summary>
<br>

- [Web Kuliner Masakan Nusantara](https://github.com/FauzanAzhimaa/Web-Kuliner-Masakan-Nusantara): a multi-page website about Indonesian regional dishes. HTML, CSS, JavaScript.
- [Restaurant Code With GUI](https://github.com/FauzanAzhimaa/Restaurant-Code-With-GUI): a restaurant ordering app with a Tkinter interface and a JSON menu.

</details>

## Tech stack

**Languages**<br>
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript">
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript">
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
<img src="https://img.shields.io/badge/HTML-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML">
<img src="https://img.shields.io/badge/CSS-1572B6?style=flat-square&logo=css3&logoColor=white" alt="CSS">

**Web, mobile & desktop**<br>
<img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React">
<img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white" alt="Vite">
<img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind CSS">
<img src="https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white" alt="NestJS">
<img src="https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white" alt="Express">
<img src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white" alt="Flask">
<img src="https://img.shields.io/badge/Capacitor-119EFF?style=flat-square&logo=capacitor&logoColor=white" alt="Capacitor">
<img src="https://img.shields.io/badge/Tauri-24C8DB?style=flat-square&logo=tauri&logoColor=white" alt="Tauri">

**Data & AI**<br>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL">
<img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" alt="MongoDB">
<img src="https://img.shields.io/badge/Firebase-DD2C00?style=flat-square&logo=firebase&logoColor=white" alt="Firebase">
<img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white" alt="TensorFlow">
<img src="https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white" alt="Keras">

**IoT, infra & security**<br>
<img src="https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white" alt="ESP32">
<img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux">
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker">
<img src="https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white" alt="Nginx">
<img src="https://img.shields.io/badge/Wazuh-3595F6?style=flat-square&logo=wazuh&logoColor=white" alt="Wazuh">
<img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git">

## Get in touch

Happy to talk about any of the projects above, or something new you'd like to build.

<a href="mailto:fauzanazhm22@gmail.com"><img src="https://img.shields.io/badge/Email-fauzanazhm22%40gmail.com-1f2937?style=flat-square&logo=gmail&logoColor=white" alt="Email fauzanazhm22@gmail.com"></a>
