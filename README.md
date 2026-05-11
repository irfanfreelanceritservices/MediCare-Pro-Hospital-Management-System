# 🏥 MediCare Pro — Hospital Management System

<div align="center">

![MediCare Pro Banner](https://img.shields.io/badge/MediCare-Pro-00c9a7?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0xMiAyQzYuNDggMiAyIDYuNDggMiAxMnM0LjQ4IDEwIDEwIDEwIDEwLTQuNDggMTAtMTBTMTcuNTIgMiAxMiAyek0xMyAxN2gtMnYtNkg5di0yaDJ2LTJoMnYyaDJ2Mmgtmm00LTVoMnY2eiIvPjwvc3ZnPg==)
![Version](https://img.shields.io/badge/Version-1.0.0-blue?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**A modern, responsive Hospital Management System built with pure HTML, CSS & JavaScript.**  
Designed for clinics and hospitals to streamline patient care, appointments, and administration.

[🚀 Live Demo](#) · [📸 Screenshots](#screenshots) · [✨ Features](#features) · [🛠 Installation](#installation)

</div>

---

## 📋 Table of Contents

- [Overview](#overview)
- [Screenshots](#screenshots)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Modules](#modules)
- [Color System](#color-system)
- [Responsive Design](#responsive-design)
- [Roadmap](#roadmap)
- [Contributing](#contributing)
- [License](#license)

---

## 🌟 Overview

**MediCare Pro** is a fully functional, single-page Hospital Management System designed to solve real-world healthcare administration challenges. Built for Pakistan's growing healthcare sector, it provides hospital staff with an intuitive interface to manage daily operations — from patient check-ins to billing.

### Why MediCare Pro?

- 🇵🇰 **Pakistan-centric** — PKR currency, local context, Urdu-ready structure
- ⚡ **Zero Dependencies** — no frameworks, no build tools, pure web standards
- 📱 **Mobile First** — works on tablets used at hospital reception desks
- 🎨 **Professional UI** — dark theme optimized for long working hours
- 🔒 **Offline Ready** — works without internet after first load

---

## 📸 Screenshots

> *(Add your screenshots here after taking them)*

| Dashboard | Appointments | Patient Records |
|-----------|-------------|-----------------|
| ![Dashboard]() | ![Appointments]() | ![Patients]() |

| Doctors | Pharmacy | Billing |
|---------|----------|---------|
| ![Doctors]() | ![Pharmacy]() | ![Billing]() |

---

## ✨ Features

### 📊 Dashboard
- Real-time statistics cards (Patients, Appointments, Beds, Revenue)
- Weekly patient visit chart (Outpatient vs Inpatient)
- Recent appointments table
- Live activity feed with color-coded events
- Animated counters and hover effects

### 📅 Appointment Management
- Full appointment list with time slots
- Filter by status: All / Pending / Confirmed
- One-click confirm or cancel appointments
- Color-coded appointment type indicators
- Export to PDF option

### 🧑‍⚕️ Patient Records
- Complete patient database with diagnosis info
- Ward assignment tracking
- Status management (Confirmed / Pending / Completed / Cancelled)
- Quick view action per patient
- Add new patient functionality

### 👨‍⚕️ Doctor Profiles
- Doctor cards with specialty, patient count, and experience
- Real-time availability status (Available / Busy)
- Visual profile grid layout
- Add new doctor functionality

### 💊 Pharmacy Inventory
- Medicine stock tracking
- Low stock and out-of-stock alerts
- Category-based medicine listing
- Price management

### 💳 Billing & Invoicing
- Monthly revenue summary (Collected / Pending / Overdue)
- Invoice list with status tracking
- Generate new invoice option
- Service-wise billing breakdown

### 🔔 UX Features
- Animated toast notifications
- Live search across patients and doctors
- Sticky navigation with active state
- Responsive sidebar with mobile support
- Smooth section transitions

---

## 🛠 Tech Stack

| Technology | Purpose | Version |
|------------|---------|---------|
| **HTML5** | Structure & Semantics | Latest |
| **CSS3** | Styling, Animations, Grid/Flexbox | Latest |
| **Vanilla JavaScript** | DOM Manipulation, Data Rendering | ES6+ |
| **Google Fonts** | Typography (DM Serif Display + DM Sans) | Latest |
| **CSS Custom Properties** | Design token system | - |
| **CSS Grid & Flexbox** | Responsive layouts | - |

> **No npm. No node_modules. No build step.** Just open `index.html` and it works.

---

## 📁 Project Structure

```
medicare-pro-hms/
│
├── index.html          # Main application — all sections & JS logic
├── styles.css          # Full stylesheet — variables, components, utilities
├── README.md           # Project documentation (this file)
│
├── assets/             # (optional — add as you extend)
│   ├── images/
│   │   ├── logo.png
│   │   └── screenshots/
│   └── icons/
│
└── docs/               # (optional — extended documentation)
    └── api-reference.md
```

### Key Design Decisions

- **Single HTML file** — all app logic lives in `index.html` for easy deployment
- **Separate CSS file** — `styles.css` follows a design token system using CSS variables
- **No framework** — demonstrates strong fundamentals valued by enterprise clients
- **Data as JS arrays** — easy to swap with a real backend API later

---

## 🚀 Installation

### Option 1: Direct Download

```bash
# Clone the repository
git clone https://github.com/yourusername/medicare-pro-hms.git

# Enter project directory
cd medicare-pro-hms

# Open in browser (no server needed!)
open index.html
# or on Windows:
start index.html
```

### Option 2: Live Server (Recommended for Development)

```bash
# If you have VS Code with Live Server extension:
# Right click index.html → Open with Live Server

# Or use Python's built-in server:
python -m http.server 8000
# Then visit: http://localhost:8000
```

### Option 3: Deploy Online (Free)

| Platform | Steps |
|----------|-------|
| **GitHub Pages** | Settings → Pages → Deploy from main branch |
| **Netlify** | Drag & drop project folder at netlify.com |
| **Vercel** | `vercel --prod` from project root |

---

## 💻 Usage

### Navigation
- Click any sidebar item to switch between modules
- Dashboard loads by default on startup
- Active section is highlighted in the sidebar

### Search
- Use the top search bar to find patients or doctors
- Results appear as toast notifications (extendable to full search results)

### Appointments
- Click **Confirm** to approve a pending appointment
- Click **Cancel** to remove an appointment
- Use filter buttons to sort by status

### Adding Data
- All **"+ Add"** buttons are connected to toast notifications
- To add real data: replace the JS arrays at the top of `index.html` with API calls

---

## 🗂 Modules

### Module 1: Dashboard
```
Components: StatCard × 4, WeeklyChart, RecentAppointments table, ActivityFeed
Data: patients[], appointments[], weekData[], activity[]
```

### Module 2: Appointments
```
Components: FilterBar, AppointmentList, ConfirmAction, CancelAction
Data: appointments[]
Filters: all | pending | confirmed | completed | cancelled
```

### Module 3: Patients
```
Components: DataTable, StatusBadge, ActionButton
Data: patients[]
Fields: ID, Name, Age, Gender, Diagnosis, Ward, Status
```

### Module 4: Doctors
```
Components: DoctorCard × 6, AvailabilityBadge
Data: doctors[]
Fields: Name, Specialty, Patient Count, Experience, Availability
```

### Module 5: Pharmacy
```
Components: DataTable, StockAlert, StatusBadge
Data: medicines[]
Fields: Name, Category, Stock, Price, Status
```

### Module 6: Billing
```
Components: RevenueSummary × 3, InvoiceTable
Data: invoices[]
Fields: Invoice#, Patient, Service, Amount, Date, Status
```

---

## 🎨 Color System

All colors are defined as CSS Custom Properties in `styles.css`:

```css
:root {
  /* Backgrounds */
  --bg:        #0b1120;   /* Main background */
  --surface:   #111827;   /* Card/sidebar surface */
  --surface2:  #1a2540;   /* Hover states */
  --surface3:  #1f2d4a;   /* Active states */

  /* Brand Colors */
  --accent:    #00c9a7;   /* Primary green — confirm/success */
  --accent2:   #3b82f6;   /* Blue — info/inpatient */
  --danger:    #f43f5e;   /* Red — alerts/cancel */
  --warn:      #f59e0b;   /* Yellow — pending/warnings */
  --purple:    #8b5cf6;   /* Purple — special highlights */
  --cyan:      #06b6d4;   /* Cyan — accent variant */

  /* Text */
  --text:      #e2e8f0;   /* Primary text */
  --text-dim:  #94a3b8;   /* Secondary text */
  --muted:     #64748b;   /* Placeholder / labels */
}
```

### To customize colors — just edit these variables in `styles.css`. All components update automatically.

---

## 📱 Responsive Design

| Breakpoint | Layout |
|------------|--------|
| `> 1200px` | 4-column stats, 3-column doctors, sidebar visible |
| `900–1200px` | 2-column stats, 2-column doctors |
| `768–900px` | Compact sidebar, adjusted padding |
| `< 768px`  | Sidebar hidden (hamburger), single column |
| `< 480px`  | Mobile optimized typography & spacing |

---

## 🗺 Roadmap

### Version 1.1
- [ ] Hamburger menu for mobile sidebar toggle
- [ ] Dark/Light theme toggle
- [ ] Print-friendly invoice view
- [ ] Search results dropdown

### Version 1.2
- [ ] LocalStorage data persistence
- [ ] Add/Edit/Delete functionality with forms
- [ ] Patient admission & discharge workflow
- [ ] Doctor schedule calendar view

### Version 2.0 (Backend Integration)
- [ ] Node.js + Express REST API
- [ ] MongoDB database
- [ ] JWT authentication (Admin / Doctor / Receptionist roles)
- [ ] Real-time updates via WebSockets
- [ ] SMS notifications via Twilio

### Version 3.0 (SaaS)
- [ ] Multi-hospital support
- [ ] Analytics & reporting dashboard
- [ ] Mobile app (React Native)
- [ ] Telemedicine video call integration

---

## 🤝 Contributing

Contributions are welcome! Here's how:

```bash
# 1. Fork the repository
# 2. Create your feature branch
git checkout -b feature/add-calendar-view

# 3. Make your changes
# 4. Commit with a clear message
git commit -m "feat: add weekly calendar view for appointments"

# 5. Push to your branch
git push origin feature/add-calendar-view

# 6. Open a Pull Request
```

### Contribution Guidelines
- Follow existing code style (no frameworks, keep it vanilla)
- Add comments for complex logic
- Test on mobile and desktop before submitting
- Update README if you add new features

---

## 👨‍💻 About the Developer

Built by **Irfan Freelancer IT Services** — a web developer based in Pakistan passionate about building practical software solutions for local industries.

- 🌐 Portfolio: [irfanfreelanceritservices.github.io](#)
- 💼 LinkedIn: [https://www.linkedin.com/in/irfanfreelanceritservices?utm_source=share_via&utm_content=profile&utm_medium=member_android](#)
- 📧 Email: irfanwahgapk@gmail.com 

> *Open to freelance projects, collaborations, and full-time opportunities in Pakistan's tech ecosystem.*

---

## 📄 License

```
MIT License

Copyright (c) 2026 IRFAN FREELANCER IT SERVICES 

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
```

---

<div align="center">

**⭐ If this project helped you, please give it a star on GitHub!**

Made with ❤️ in Pakistan 🇵🇰 | Irfan Freelancer IT Services 

</div>
