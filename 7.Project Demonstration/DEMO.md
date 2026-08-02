# 🎥 ISTR — Video Demonstration

**Intergalactic Space Travel Request System — Live Walkthrough**

[![Watch the Demo](https://img.shields.io/badge/▶_Watch-Video_Demo-1F4E79?style=for-the-badge&logo=googledrive&logoColor=white)](https://drive.google.com/file/d/1NNBMOQgZsXXhcP6I-Sp-B8n9KzTxQ-WG/view?usp=sharing)
![ServiceNow](https://img.shields.io/badge/Platform-ServiceNow-00C487?style=for-the-badge&logo=servicenow&logoColor=white)
![Status](https://img.shields.io/badge/Status-Final_Build-blue?style=for-the-badge)

---

## 📺 Watch the Demo

**[▶ Click here to watch the ISTR demonstration video](https://drive.google.com/file/d/1NNBMOQgZsXXhcP6I-Sp-B8n9KzTxQ-WG/view?usp=sharing)**

> Hosted on Google Drive. If the video doesn't preview directly, use **File → Download** or **Open in new window** from the Drive toolbar.

---

## 🧭 What This Demo Covers

This walkthrough shows the ISTR scoped application running end-to-end on a live ServiceNow Personal Developer Instance — not a mockup or slide deck.

| Stage | What's Shown |
|---|---|
| 🛰️ **Mission Submission** | Requester submits a mission through the Space Travel Request catalog item |
| 🔁 **Approval Routing** | The ISTR Approval Flow triggers automatically — Manager → Finance → conditional Mission Control |
| ⚠️ **Risk-Based Escalation** | High/Critical risk missions are shown routing to Mission Control; Low/Medium missions bypass it |
| 🔐 **Role-Based Access** | Access differences across `space.requester`, `space.approver`, `space.finance`, and `space.admin` |
| 🚀 **Launch Execution** | Admin-only "Launch Mission" UI Action firing once a request reaches Ready for Launch |
| 🧾 **Audit Trail** | State changes, approvals, rejections, and notifications logged in real time |

---

## ⏱️ Suggested Viewing Guide

| Time | Segment |
|---|---|
| 0:00 | Introduction & problem context |
| — | Mission request submission (Service Catalog) |
| — | Flow Designer — approval routing in action |
| — | Role-based access control walkthrough |
| — | Risk-based Mission Control escalation |
| — | Launch execution & audit log |
| — | Closing summary |

*(Update the timestamps above once the final cut is locked.)*

---

## 🔗 Related Documentation

- 📄 [ISTR Final Documentation](./ISTR_Final_Documentation.pdf) — full requirements, design, sprint delivery, and testing report
- 📘 [Project README](./README.md) — architecture, tech stack, and setup overview

---

<div align="center">

*Built on ServiceNow Flow Designer • Demonstrated live, not simulated 🛸*

</div>
