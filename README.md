# 🎯 SupportIQ – Mock API (Built using MockWave)

**SupportIQ** is a mentorship-based learning platform designed for technical support professionals to upskill efficiently.  
This mock API simulates the backend logic of the platform — including user management, learning modules, videos, FAQs, and progress tracking.

---

## 🚀 Overview

In a support environment, new joiners often face repetitive onboarding and knowledge gaps.  
**SupportIQ** simplifies this by allowing **mentors** to create structured training modules and **mentees** to learn at their own pace — through videos, help docs, FAQs, quizzes, and real-life ticket examples.

---

## 🧱 Core API Endpoints (Powered by MockWave)

| Module | Endpoint | Description |
|---------|-----------|-------------|
| 👥 Users | [`get-users`](https://admin.mockwave.io/mockwave/leela_751828/myprojects/supportiq/v1/get-users) | List all mentors and mentees |
| 📚 Resources | [`get-resources`](https://admin.mockwave.io/mockwave/leela_751828/myprojects/supportiq/v1/get-resources) | List all learning modules |
| 🎥 Videos | [`get-resources-videos`](https://admin.mockwave.io/mockwave/leela_751828/myprojects/supportiq/v1/get-resources-videos) | Videos linked to resources |
| 📘 Help Docs | [`get-resources-helpdocs`](https://admin.mockwave.io/mockwave/leela_751828/myprojects/supportiq/v1/get-resources-helpdocs) | Support documentation |
| ❓ FAQs | [`get-resources-faqs`](https://admin.mockwave.io/mockwave/leela_751828/myprojects/supportiq/v1/get-resources-faqs) | Common questions and answers |
| 🧩 Quizzes | [`get-resources-quizzes`](https://admin.mockwave.io/mockwave/leela_751828/myprojects/supportiq/v1/get-resources-quizzes) | Assessment questions |
| 🎟️ Tickets | [`get-resources-tickets`](https://admin.mockwave.io/mockwave/leela_751828/myprojects/supportiq/v1/get-resources-tickets) | Example customer tickets |
| 📈 Progress | [`get-resources-progress`](https://admin.mockwave.io/mockwave/leela_751828/myprojects/supportiq/v1/get-resources-progress) | Track mentee learning progress |

---

## 🧠 Data Model Summary

**Users**
- Mentors: Create resources and track mentee progress.  
- Mentees: Access training modules and complete assessments.

**Resources**
- Each resource contains:
  - 🎥 *Videos* — training clips and demos  
  - 📘 *Help Docs* — support guides and SOPs  
  - ❓ *FAQs* — common questions  
  - 🧩 *Quizzes* — concept validation tests  
  - 🎟️ *Tickets* — real-world case studies  

**Progress**
- Tracks each mentee’s completion percentage per resource.

---

## 🧰 Tech Stack

| Tool | Purpose |
|------|----------|
| **MockWave** | API creation and testing |
| **JSON** | Data structure |
| **GitHub** | Documentation and version control |

---

## 💡 Key Highlights

✅ Clean RESTful structure (GET endpoints for modules)  
✅ Demonstrates backend design thinking  
✅ Showcases product mindset — modular, mentor-led learning  
✅ Ready for integration into a simple frontend or dashboard  
