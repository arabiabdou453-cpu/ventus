# Ventus - CAD & MDT Dispatch, Cura ePCR & Operations Platform

[![GitHub Pages](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-brightgreen?style=for-the-badge&logo=github)](https://arabiabdou453-cpu.github.io/ventus/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)](LICENSE)
[![React](https://img.shields.io/badge/React-18-61DAFB?style=for-the-badge&logo=react)](https://react.dev/)
[![TailwindCSS](https://img.shields.io/badge/Tailwind-CSS-38B2AC?style=for-the-badge&logo=tailwind-css)](https://tailwindcss.com/)
[![Standards](https://img.shields.io/badge/Compliance-NHS%20DSPT%20%7C%20ICO%20%7C%20CQC%20Ready-purple?style=for-the-badge)](https://www.dsptoolkit.nhs.uk/)

A modern, high-performance command-and-control platform engineered for private ambulance services, event medical teams, non-emergency patient transport services (PTS), and vehicle recovery operations.

---

## 🌟 Live Demo

- **Public Live Application:** [https://arabiabdou453-cpu.github.io/ventus/](https://arabiabdou453-cpu.github.io/ventus/)
- **Source Repository:** [https://github.com/arabiabdou453-cpu/ventus](https://github.com/arabiabdou453-cpu/ventus)

---

## 🚀 Key Modules & Capabilities

```
+---------------------------------------------------------------------------------------+
|                               Ventus Unified Ecosystem                                |
+---------------------------------------------------------------------------------------+
         │                                   │                               │
         ▼                                   ▼                               ▼
+───────────────────────────+   +───────────────────────────+   +───────────────────────────+
|      CAD & Dispatch       |   |      Cura ePCR Suite      |   |      MDT Crew App         |
| • Spatial Map Tracking    |   | • Digital Patient Records |   | • Touch Vehicle Console   |
| • Rapid Incident Intake   |   | • Clinical Observations   |   | • Job Status Sync (Enroute|
| • Live Unit Telemetry     |   | • Safeguarding Referrals  |   |   Arrived, Clear)         |
| • Control Wallboards      |   | • Minor Injury Analytics  |   | • GPS Turn-by-Turn Nav    |
+───────────────────────────+   +───────────────────────────+   +───────────────────────────+
         │                                   │                               │
         └───────────────────────────────────┼───────────────────────────────┘
                                             ▼
+---------------------------------------------------------------------------------------+
|                               Business & Operations Suite                             |
|  • Scheduling & Timesheets  • Fleet VDI Readiness  • Inventory Command  • CRM Billing |
+---------------------------------------------------------------------------------------+
```

### 1. CAD Dispatch & Control Room
- **Live Map Visualization:** High-accuracy spatial tracking of ambulances, response cars, and mobile crew members with live status indication.
- **Incident Intake Wizard:** Structured call logging with automatic priority classification, address geocoding, and patient pre-arrival info.
- **Response Wallboard:** Full-screen operational dashboard designed for command center projection with real-time response KPIs.

### 2. Cura Electronic Patient Care Record (ePCR)
- **Digital Patient Care Documentation:** Secure clinical intake capturing vitals, primary survey, patient history, medication administered, and interventions.
- **Event Medical Support:** Tailored workflows for mass-gathering events, marathons, festivals, and rapid minor injury triage.
- **Governance & Safeguarding:** Built-in safeguarding referral pipelines, clinical audit timelines, and incident logging compliant with UK health governance standards.

### 3. Mobile Data Terminal (MDT) Crew App
- **Crew Touch Console:** Intuitive tablet-friendly interface designed for ruggedized vehicle docks.
- **Real-Time Job Workflow:** Instant job dispatch notifications, one-tap status updates (Acknowledge, Mobile, At Scene, Conveying, Cleared), and direct crew messaging.

### 4. Operations & Business Management Suite
- **Fleet VDI & Asset Readiness:** Vehicle defect logging, daily vehicle inspection checks, kit serial management, and calibration trackers.
- **Scheduling & Employee Portal:** Shift rosters, crew availability, qualifications tracking, and automated timesheet reconciliation.
- **Billing & Accounts Export:** Automatic generation of invoice-ready line items from completed CAD missions for direct accounting export.

---

## 🏥 Sector Specializations

| Sector | Key Platform Features |
|:---|:---|
| **Private Ambulance** | Emergency and urgent care dispatch, clinical handover forms, patient conveyance records, blue-light incident logging. |
| **Event Medical** | Event marathon / venue dashboards, multi-site command, rapid walk-in triage, live minor-injury analytics. |
| **Patient Transport (PTS)** | Scheduled journey planning, multi-patient route optimization, mobility requirement matching, NHS trust reporting. |
| **Vehicle Recovery** | Breakdown job intake, roadside recovery dispatch, vehicle condition reporting, tow telemetry. |

---

## 🛠️ Quick Start Guide

### Prerequisites
- Node.js (v18.0 or higher recommended)
- Git

### Installation & Local Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com/arabiabdou453-cpu/ventus.git
   cd ventus
   ```

2. **Start the local server:**
   ```bash
   npm start
   ```

3. **Open the browser:**
   ```
   http://localhost:3000
   ```

*(The included zero-dependency Node.js server automatically handles static assets and Single Page Application client-side routing fallback.)*

---

## 📁 Repository Structure

```
ventus/
├── assets/                        # Compiled modular JS chunks, CSS & high-res UI media
│   ├── index-D6zDdEgd.js          # Core application bundle with adaptive base routing
│   ├── index-BcJwEf5k.css         # Tailwind & modern design design-system stylesheet
│   ├── CadDispatchMdt-*.js        # CAD & MDT dispatch module chunk
│   ├── CuraEpcr-*.js              # Cura electronic patient care records module chunk
│   ├── BusinessSuite-*.js         # Full enterprise management module chunk
│   ├── Pricing-*.js               # Pricing calculator and plans chunk
│   └── screenshot-*.png/.webp     # Authentic UI screenshots and platform previews
├── 404.html                       # GitHub Pages SPA router redirect handler
├── favicon.ico / .png / .webp     # Brand favicons and web-app manifest icons
├── index.html                     # Main application entry point with SEO shell
├── package.json                   # Project metadata and zero-dependency scripts
├── server.js                      # High-efficiency SPA-aware HTTP static server
├── LICENSE                        # MIT License
└── README.md                      # Comprehensive project documentation
```

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
