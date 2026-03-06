# NexTime - Smart Group Coordination Ecosystem

## Overview
NexTime is an coordination support system designed as a **"productivity layer"** integrated into existing communication platforms. The project focuses on eliminating overlaping in group scheduling and post-event accountability.

The project is built upon three strategic pillars:
* **Visual synchronization:** Visualizing individual schedule intersections via a Heatmap algorithm while ensuring absolute privacy (Provides privacy options for users.).
* **Driven automation:** Automating checklist creation and financial/tasks tracking through a specialized prompt engine.
* **Seamless accountability:** Constructing a workflow from planning and voting to task/payment completion.

---

## Project architecture
The source code is organized into a modular structure to optimize scalability and integration:
(The structure can be updated to suit future processes)

### 1. Logic & Algorithm Layer
* **Schedule intersection engine:** A specialized algorithm that calculates time overlaps among multiple users, supporting both recurring weekly schedules and one-time monthly events.
* **Prompt parser:** A Natural Language Processing engine that extracts entities (Date, Title, Amount, Personnel) from chat strings to generate actionable data.
* **Privacy guard logic:** Manages identity visibility, allowing users to mask specific event titles while showing busy status in group views.

### 2. User Interaction Layer (UI/UX)
* **Heatmap visualization UI:** A color-coded density map that displays group availability at a glance, eliminating the need for manual message reading.
* **Floating quick-access bar:** A mobile-optimized floating component providing one-touch access to personal schedules and quick event adding.
* **Smart voting interface:** A data-driven polling system that suggests optimal time slots based on real-time schedule intersections.

### 3. Data & Management Layer
* **State persistence:** Real-time synchronization of group status and checklist progress via Backend-as-a-Service (BaaS).
* **Accountability Tracker:** Manages the lifecycle of tasks and payments with real-time progress bars and admin settlement reviews.

---

## Key Features
* **Overlay schedule:** Check the general availability and book your appointment quickly.
* **Prompt-to-action(checklist):** Converts conversations into interactive checklists instantly using smart syntax.
* **Privacy-first Design:** Displays busy blocks without compromising the confidentiality of personal event details.

---

## Milestones roadmap (Scrum)

| Milestone | Deadline | Primary focus |
| :--- | :--- | :--- |
| **[M1] Project setup & Wiki** | 07/03/2026 | Foundation, market research, and wiki documentation. |
| **[M2] UI/UX & Behance** | 02/04/2026 | High-fidelity design, prototype, and Behance showcase. |
| **[M3] MVP development** | 20/04/2026 | Core feature implementation and backend integration. |
| **[M4] Testing & Final report** | 10/05/2026 | QA, deployment, and final project documentation. |

---

## Development & Resources
* 📑 **Project documentation (Wiki):** Comprehensive research, BMC, MVP features, and User Flows.
* 🏗️ **Scrum board (Management):** Real-time tracking of development progress and milestones.
* 💻 **Source code repository:** The main codebase and technical documentation.

---

## Authors (L02-BugFree Team)
Project Manager: Nguyen Hao Khang - Leader (khang.nguyen720005@hcmut.edu.vn)

Member 2: Nguyen Phan Quoc Anh

Member 3: Nguyen Phan Viet Anh

Member 4: Nguyen Khanh Trinh

Member 5: Le Anh Tu

---
> For inquiries or contributions, please contact us via GitHub Issues or the Team Leader's email.
