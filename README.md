# 🪔 Navrang Garba Night 2026 - Event Management System

A premium, highly secure event management and ticketing web application built for **ASR Media's Navrang Garba Night 2026**. This project provides a seamless digital registration experience for guests and a robust QR-code scanning portal for event security staff to prevent proxy attendance.

![Project Status](https://img.shields.io/badge/Status-Active-success)
![Version](https://img.shields.io/badge/Version-1.0-blue)
![Developer](https://img.shields.io/badge/Developer-Sanjeev_Kumar-orange)

---

## ✨ Features

### For Guests:
* **One-Click Registration:** Seamless login using Google OAuth.
* **Instant Digital Passes:** Automatically generates a unique, secure QR Code ticket directly on the user's device upon registration.
* **Premium UI/UX:** Features a fully responsive, 3D Glassmorphism interface with custom "Firecracker" particle animations and scroll-triggered tilt effects.

### For Event Admins:
* **Gate Control Terminal:** A hidden, password-protected portal for event security.
* **Live QR Scanning:** Integrated camera scanner to read guest passes instantly.
* **Anti-Proxy Security:** Real-time database checks verify if a guest is "Registered" or if the ticket has "Already been used," preventing duplicate entries.
* **Live Analytics:** On-screen counter tracking successful session check-ins.

---

## 🛠️ Tech Stack

**Frontend:**
* HTML5 & CSS3 (Custom Glassmorphism Design)
* Vanilla JavaScript
* [Vanilla-Tilt.js](https://micku7zu.github.io/vanilla-tilt.js/) (3D Hover Effects)
* [QRCode.js](https://davidshimjs.github.io/qrcodejs/) (Ticket Generation)
* [HTML5-QRCode](https://github.com/mebjas/html5-qrcode) (Admin Camera Scanner)

**Backend / Database:**
* **Firebase Authentication:** Google Sign-In Provider
* **Firebase Cloud Firestore:** Real-time NoSQL database for ticket verification and status updates.

---

## 🚀 How to Run Locally

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/SanjeevKumar-24/Navrang-Garba-Event-System.git](https://github.com/SanjeevKumar-24/Navrang-Garba-Event-System.git)
