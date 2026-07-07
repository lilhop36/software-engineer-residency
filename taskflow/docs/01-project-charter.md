# TaskFlow Project Charter

## 1. Problem Statement
Problem 1: Employees have no single, reliable place to see all their task deadlines — they rely on scattered emails, WhatsApp messages, and manual reminders.

Why it matters: Deadlines are missed regularly because notifications get buried or forgotten. This erodes client trust, triggers penalty clauses, and forces last‑minute firefighting that burns out your team.

Problem 2: Managers cannot see real‑time progress across projects — they only find out about delays after they've already happened, often through verbal updates or chasing individuals.

Why it matters: Without visibility, managers cannot reallocate resources, unblock stuck tasks, or adjust priorities proactively. Small delays compound into major schedule overruns, and leadership makes decisions based on gut feeling rather than facts — increasing the risk of project failure.

Problem 3: Project communication is split across emails, WhatsApp groups, and Excel files — information is fragmented, decisions are lost in long threads, and team members miss updates because they weren't copied.

Why it matters: Misalignment becomes the norm: two people work on conflicting versions of a task, questions get re‑asked wasting hours, and there's no audit trail of why decisions were made. This kills productivity, breeds frustration, and makes onboarding new members nearly impossible.

Problem 4: Generating status reports requires manually consolidating data from multiple spreadsheets, email chains, and chat histories — taking managers hours each week.

Why it matters: Reporting becomes a low‑value, high‑cost chore. Reports are always outdated by the time they're shared, so stakeholders get stale information. Managers spend more time documenting work than doing work, and the delay in reporting means critical issues are flagged too late to fix without extra cost.

Overarching problem (the root cause): The company relies on disconnected, manual tools that do not scale with team growth.

Why it matters: As you add more projects, clients, and employees, the chaos multiplies exponentially — not linearly. The overhead from coordination and error‑correction eats into margins, client satisfaction drops, and your team loses confidence in leadership's ability to deliver consistently. Eventually, this damages your reputation and shrinks future revenue.
Project Scope
Product Name: TaskFlow Central (working title)

1.2.1 Business Problem
TaskFlow Solutions currently manages projects using Excel, emails, and WhatsApp. As the company grows, this fragmented approach leads to missed deadlines, lack of real‑time progress visibility, and time‑consuming manual report generation. TaskFlow Central will centralise all task and project information into a single web‑based system, enabling transparent tracking, efficient collaboration, and instant reporting.

1.2.2 In Scope
TaskFlow Central is a responsive web application that provides the following capabilities:

User & Team Management – Create, edit, deactivate user accounts; assign users to teams; define roles (Admin, Manager, Member) with appropriate permissions.

Project Management – Create, edit, and close projects; assign project managers; set start/end dates and descriptions.

Task Management – Create tasks within projects; assign tasks to users; set priority (High/Medium/Low), status (To Do, In Progress, Done), and due dates; track task history.

Real‑time Dashboard – Display key project metrics (overall progress, tasks by status, upcoming deadlines) in a central dashboard visible to managers.

Collaboration – Task‑level comments/threads; automatic email notifications for task assignments, approaching deadlines, and status changes.

Reporting – Generate project status reports (summary and detailed) and individual performance reports (tasks completed, overdue) in PDF format.

Security – Secure login with password authentication; role‑based access control (e.g., only managers can create projects); data encryption in transit and at rest.

1.2.3 Out of Scope
The following are explicitly excluded from this release:

Native mobile apps (only responsive web design is included).

Data migration from existing spreadsheets or WhatsApp conversations.

Integration with third‑party tools (Slack, Jira, Outlook calendar, etc.).

Time tracking, timesheets, or billing modules.

Client/guest access to projects.

Advanced resource management or automatic workload balancing.

Custom branding beyond the company logo/colour scheme.

1.2.4 Constraints

The application must be accessible via modern web browsers (Chrome, Firefox, Edge, Safari) on desktops, tablets, and mobile phones.

Must support up to 500 concurrent users initially, with the architecture allowing horizontal scaling.

User interface must adhere to modern usability standards (clean, intuitive, responsive).

All user passwords must be stored using strong hashing (e.g., bcrypt).
 Assumptions

The client will provide clear role definitions and a list of initial projects/users before configuration.
Risks 
Several risks have been identified that could prevent the system from meeting its scope, quality, or adoption goals, and the requirements have been shaped accordingly. The most significant risk is scope creep: stakeholders may request features such as native mobile apps, billing, or client portals that are explicitly excluded from this release. To mitigate this, a detailed out-of-scope list has been agreed upon, and any future additions will require formal change control. A related risk is user adoption failure, as employees are accustomed to WhatsApp and Excel; the system addresses this with a deliberately simple and intuitive interface, supported by a management policy requiring all task updates to occur within the tool, along with early pilot testing. On the technical side, performance degradation under high load is a concern as the user base grows. This is mitigated by a horizontally scalable architecture and quantified non-functional requirements (e.g., dashboard load time under two seconds) that will be verified through load testing. Data security is treated as a critical risk, addressed by strong password hashing, HTTPS encryption, role-based access control, and a pre-launch penetration test. The risk of vague acceptance criteria has been neutralised by making all quality attributes measurable and tying them to concrete success metrics. Finally, while the client may later expect real-time integration with email or spreadsheets, this is explicitly out of scope; however, the system API is being designed to accommodate future extensions without architectural change.

Success Criteria 
The success of the TaskFlow Central system will be measured against objective, business-focused outcomes that directly address the original problems of missed deadlines, lack of real-time visibility, and time-consuming manual reporting. First, the overdue task rate must drop by at least forty percent within three months of launch, as measured by system logs, demonstrating that centralised task tracking genuinely improves deadline adherence. Second, project managers must be able to retrieve the real-time status of any project — including completion percentage, task distribution, and upcoming deadlines — in under ten seconds without consulting any external tool, confirming that the dashboard provides instant visibility. Third, generating a full project status report as a PDF must take less than one minute, and the data it contains must reflect the current state of tasks no older than five minutes, eliminating hours of manual collection. User adoption is considered a prerequisite for all other outcomes: within two months, at least eighty percent of active employees must log in at least three times per week, and managers must report a noticeable reduction in task-related communication via WhatsApp and email. The system must also meet its performance targets under load, with dashboard pages loading within two seconds and task creation completing within one second for up to two hundred concurrent users, and no medium-or-higher severity security vulnerabilities must remain at launch. These criteria form the formal acceptance gate; the project will be deemed successful once all of them are verified.

A cloud‑based deployment model is acceptable; the development team will recommend the hosting platform.

Users will have continuous internet connectivity during operation.

No legacy system integration is required.
