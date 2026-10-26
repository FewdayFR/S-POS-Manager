# 🖥️ S-POS Management

> Central backend server and management back-office for Self-Point-of-Sale (SPOS) kiosks, designed for events, associations, and local businesses.

---

## 🌟 Overview

**S-POS Management** is the central brain of the ecosystem. It acts as the backbone that connects all your self-service ordering kiosks (`s-pos-kiosk`) to a single administrative interface. 

Whether you are running a bar at a local community event, managing a student association foyer, or deploying a standalone ordering terminal, this backend gives you total control over your catalog, live order status, sales tracking, and webhook payment processing—all self-hosted on your own hardware or remote server.

---

## 🚀 Key Features

* **Centralized Catalog & Inventory Management:** Easily manage your products, categories, prices, and stock levels in real time.
* **Multi-Kiosk Coordination:** Synchronize multiple ordering terminals effortlessly.
* **Webhook Payment Integration:** Seamlessly handle payment confirmations and status updates sent by payment providers (such as SumUp integration workflows).
* **Real-time Order Dashboard:** Monitor incoming orders, track preparation statuses, and manage fulfillment directly from a clean web interface.
* **Self-Hosted & Open-Source:** Full data ownership, zero hidden cloud subscriptions, and easy deployment on local servers or VPS nodes.

---

## 📂 Project Structure

```text
s-pos-management/
├── api/                # REST API endpoints for kiosk synchronization
├── assets/             # Frontend styling, scripts, and product imagery
├── database/           # SQL schemas and migration scripts
├── includes/           # Core utility classes, database connections, and auth
├── webhook/            # Payment gateway webhook handlers (e.g., SumUp)
├── .env.example        # Environment configuration template
├── LICENSE             # MIT License file
└── README.md           # Project documentation
