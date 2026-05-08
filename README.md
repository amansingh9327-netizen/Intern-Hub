# 🎓 InternHub – Internship Application Portal

A complete, production-quality internship application portal inspired by Unstop.
Built with pure HTML, CSS, and JavaScript — **no frameworks, no dependencies, no build step.**

---

## 📁 Project Structure

```
InternHub/
├── InternHub_Final.html     → Main portal (all-in-one single file)
├── README.md                → This file
├── HOW_TO_RUN.md            → Step-by-step setup guide
└── screenshots/
    ├── landing.png          → Landing page preview
    ├── apply.png            → Application form
    └── admin.png            → Admin dashboard
```

---

## 🚀 Quick Start

### Option 1 — Just Double Click
Double-click `InternHub_Final.html` → Opens directly in your browser. Done!

### Option 2 — VS Code + Live Server (Recommended)
1. Open folder in VS Code
2. Install **Live Server** extension (by Ritwick Dey)
3. Right-click `InternHub_Final.html` → **Open with Live Server**
4. Visit `http://127.0.0.1:5500`

---

## 🔑 Admin Credentials

| Field    | Value      |
|----------|------------|
| Username | `admin`    |
| Password | `admin123` |

> You can change the password from the Admin → Settings tab.

---

## ✨ Features

### 👨‍🎓 Applicant Side
| Feature | Details |
|---|---|
| Landing Page | Unstop-inspired UI, category grid, opportunity cards, animated stats |
| Application Form | Full validation, skill tag builder, drag-and-drop resume upload |
| Cover Letter | Character counter (600 max), min length validation |
| Success Page | Unique Application ID shown after submission |
| Track Status | Enter App ID to check Pending / Selected / Rejected with timeline |

### 🛡️ Admin Panel
| Feature | Details |
|---|---|
| Secure Login | Session-based authentication |
| Dashboard | KPI cards (Pending, Selected, Rejected, Total) |
| Applications Table | Sortable, searchable, filterable table |
| Search & Filter | Real-time search by name, email, skill, department + status/dept dropdowns |
| Quick Actions | ✓ Select or ✕ Reject directly from table row |
| Detail Modal | Full application view with inline status update |
| Analytics | Donut chart, department bars, skill bars, 7-day activity chart |
| CSV Export | Download filtered applicants as `.csv` |
| Settings | Change password, portal toggles, danger zone |

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Markup | HTML5 (Semantic) |
| Styling | Pure CSS3 (Variables, Grid, Flexbox, Animations) |
| Logic | Vanilla JavaScript (ES6+) |
| Storage | localStorage (browser-side persistence) |
| Icons | Font Awesome 6.5 (CDN) |
| Fonts | Plus Jakarta Sans (Google Fonts CDN) |

---

## 📚 Skills Demonstrated (Internship Task)

| Requirement | Implementation |
|---|---|
| **CRUD** | Create (form submit), Read (table/modal), Update (status change), Delete (danger zone) |
| **Authentication** | Session-based admin login with credential validation & change password |
| **Admin Panel** | Full dashboard with stats, filters, analytics, CSV export |
| **Database** | localStorage as browser-side persistent data store |
| **Search & Filter** | Multi-field real-time search + status/dept dropdowns + sort |
| **File Upload** | Drag-and-drop + click-to-browse with type/size validation |
| **Data Visualization** | SVG donut chart, animated bar charts, 7-day time series |
| **Form Validation** | Client-side validation with inline error messages |
| **Responsive Design** | Mobile-friendly with CSS Grid breakpoints |

---

## 🎨 Design System

| Property | Value |
|---|---|
| Primary Color | `#4F46E5` (Indigo) |
| Accent Color | `#06B6D4` (Cyan) |
| Font | Plus Jakarta Sans |
| Theme | Light / White background (Unstop-inspired) |
| Border Radius | 8px – 24px (layered) |
| Layout | Icon Rail + Top Nav + Content Area |

---

## 💾 Data Storage

- Uses **localStorage** to persist applications across page reloads
- **12 demo applicants** are pre-seeded on first load
- Data survives browser refresh but is local to that browser/device
- Use **Export CSV** in admin to back up data externally

---

## 📞 Support

If you encounter any issues:
1. Make sure you're opening the file in a **modern browser** (Chrome, Firefox, Edge)
2. Check that **JavaScript is enabled** in your browser
3. For Live Server issues, ensure the extension is installed and active

---

*Built for the InternHub Internship Task · 2025*
