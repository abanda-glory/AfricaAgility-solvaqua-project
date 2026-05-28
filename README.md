# 🌊 SolvAqua

**Water, Made Visible**

SolvAqua is a Progressive Web App (PWA) + USSD hybrid platform designed to help communities report, track, and resolve water-related issues in real time. It connects citizens, operators, and partners through a unified system powered by phone-number identity and cross-channel reporting.

---

## 🚀 Project Overview

SolvAqua solves the problem of slow, untracked, and disconnected water issue reporting by enabling:

- 📍 Real-time water point status visibility
- 📝 Issue reporting (PWA + USSD)
- 🔄 Live issue tracking and verification loop
- 🔔 Community alerts & announcements
- 🧑‍💼 Operator & admin dashboard
- 📡 Offline reporting via USSD integration
- 🔗 Cross-channel identity using phone numbers

---

## 🧩 System Architecture

- **Progressive Web App (PWA)** → Community users & guests  
- **USSD Interface** → Offline reporting users  
- **Admin & Operator Dashboard** → Internal management system  
- **API Layer** → Partner integrations and external access  

---

## 👥 User Types

### Community Users
- View water point statuses
- Report issues
- Track submitted reports
- Receive alerts and updates

### Guests
- Read-only access to water status and issues
- Can submit reports after lightweight onboarding

### Operators / Admins
- Manage issues and water points
- Publish alerts and announcements
- Assign technicians
- Monitor analytics

### Partners (NGOs / Government / API Users)
- Read-only dashboards or API access
- Scoped to assigned communities

---

## ⚙️ Key Features

### 💧 Water Point Monitoring
- Availability status: Available / Limited / Unavailable
- Condition status: Safe / Caution / Maintenance
- Real-time updates from operators

---

### 📝 Issue Reporting (PWA + USSD)
- Report water-related issues per water point
- Categories: No water, low pressure, contamination, pipe burst, pump fault, other
- Severity levels: Low / Medium / High
- Offline queue support (PWA)
- SMS-based reporting (USSD)

---

### 🔄 Issue Tracking System
- Lifecycle: Reported → In Progress → Resolved
- Personal “My Reports” history
- Operator notes and updates
- Dispute & verification loop after resolution

---

### 🔔 Alerts & Announcements
- Community-wide alerts via push notifications
- Water point-specific announcements
- Severity-based alert system (Informational / Warning / Critical)

---

### 📡 USSD Integration
- Offline step-by-step reporting flow:
  - Community selection
  - Water point selection
  - Issue category
  - Severity
  - Confirmation
- SMS-based status updates for non-smartphone users

---

### 🧑‍💼 Admin & Operator Dashboard
- Issue management & assignment
- Water point status control
- Alerts & announcement publishing
- Analytics:
  - Issue volume trends
  - Category breakdown
  - Channel comparison (PWA vs USSD)
  - Resolution rate tracking

---

### 🔗 Cross-Channel Identity
- Phone number is the single identity anchor
- Links PWA, guest sessions, and USSD reports
- Unified “My Reports” experience across all channels

---

## 🧱 Tech Stack (MVP)

- Frontend: React / Next.js (PWA)
- Backend: Node.js + Express
- Database: MongoDB
- Messaging: SMS Gateway + Push Notifications
- USSD: Telco Gateway integration

---

## 📁 Project Structure

```bash
solvaqua/
│
├── client/        # PWA frontend
├── server/        # Backend API
├── dashboard/     # Admin panel
├── docs/          # PRD & documentation
├── ussd/          # USSD flow logic
└── README.md
