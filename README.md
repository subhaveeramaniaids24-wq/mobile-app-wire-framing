# 📱 Student Attendance Management System — Mobile App Wireframing

UI/UX internship task: complete low-fidelity wireframing exercise for a mobile app that lets
students mark, track, and get alerts about their class attendance.

---

## 📌 Problem Statement

Manual attendance tracking is time-consuming and error-prone, and students often have no
real-time visibility into their attendance percentage until it's too late (e.g. blocked from
exams due to shortage). This project designs a mobile app that lets students mark attendance
in seconds (via QR scan), view a live attendance percentage, and receive proactive shortage
alerts.

## 👥 Target Users

- **Primary:** College/school students who mark and track their own attendance
- **Secondary:** Faculty/coordinators verifying records
- **Tertiary:** Admins needing consolidated reports

## 🔍 UX Process

This project follows the **Design Thinking** framework:

1. **Empathize** — informal interviews + review of common attendance-app complaints
2. **Define** — core problem: no real-time visibility + slow manual marking
3. **Ideate** — brainstormed QR check-in, live % widget, shortage alerts, subject-wise history
4. **Prototype** — low-fidelity grayscale wireframes for all core screens
5. **Test** — planned usability walkthroughs on a clickable Figma prototype

Full write-up (personas, research, wireframe rationale) is in
[`Student_Attendance_Wireframing_Report.pdf`](./Student_Attendance_Wireframing_Report.pdf).

## 🧑‍🎓 Personas

| Persona | Summary |
|---|---|
| **Aarthi Suresh (20)** — The Anxious Achiever | Wants an early warning system before attendance becomes a problem |
| **Rahul Menon (19)** — The Busy Multitasker | Wants attendance marking to take seconds, not minutes |

## 🗺️ User Flow

```
Start → Splash Screen → Session Active? 
   ├─ No  → Login → Enter Credentials → Valid? → (No → Error/Retry) → Dashboard
   └─ Yes → Dashboard
Dashboard → [Mark Attendance (QR Scan) | Attendance History | Notifications | Profile]
```

See `/wireframes/0_user_flow_diagram.png` for the full diagram.

## 🖼️ Screens (Low-Fidelity Wireframes)

| # | Screen | Description |
|---|--------|-------------|
| 1 | Splash Screen | App logo, name, loading state |
| 2 | Login | Student ID/password login + QR quick-login |
| 3 | Student Dashboard | Live attendance %, quick actions, subject-wise summary |
| 4 | Attendance History | Filterable date-wise present/absent log |
| 5 | QR Scan / Mark Attendance | Camera viewfinder to check in, manual fallback |
| 6 | Notifications | Shortage alerts, confirmations, timetable updates |
| 7 | Profile | Student info, settings, logout |

All wireframe PNGs are in [`/wireframes`](./wireframes), grayscale, 360×760, ready to be rebuilt
as Figma frames.

## 🧩 Figma Structure

```
Page: Research        → Personas, Pain Points
Page: Flow             → User Flow Diagram
Page: Wireframes-LoFi  → 01 Splash Screen
                         02 Login
                         03 Student Dashboard
                         04 Attendance History
                         05 QR Scan / Mark Attendance
                         06 Notifications
                         07 Profile
Page: Components       → Bottom Nav, Buttons, Cards, Input Fields
```

Frame naming convention: `[Order] - [Screen Name] - Lo-Fi` (e.g. `03 - Student Dashboard - Lo-Fi`).

## 📂 Repository Structure

```
├── README.md
├── Student_Attendance_Wireframing_Report.pdf   # Full case-study document
└── wireframes/
    ├── 0_user_flow_diagram.png
    ├── 1_splash_screen.png
    ├── 2_login.png
    ├── 3_student_dashboard.png
    ├── 4_attendance_history.png
    ├── 5_qr_scan_mark_attendance.png
    ├── 6_notifications.png
    └── 7_profile.png
```

## 🛠️ Tools

- Figma (intended rebuild target for interactive wireframes)
- Design Thinking methodology

## 📄 License

For educational / internship submission purposes.
