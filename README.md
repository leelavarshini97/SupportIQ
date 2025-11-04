# 🎯 SupportIQ – Mock API (Built using MockWave)

SupportIQ is an organized, mentorship-driven learning platform designed for technical support professionals. It helps mentors train new team members efficiently by structuring learning content and making repeated tasks easier to learn.

The platform concept includes:

1) Articles and Help Docs for foundational knowledge

2) Quizzes to reinforce learning

3) Previously handled repetitive tickets as practical examples

4) Progress tracking dashboards to monitor mentee growth

This mock API simulates the backend workflows, demonstrating how resources, users, and learning paths could interact to create a structured, self-paced learning experience.

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

