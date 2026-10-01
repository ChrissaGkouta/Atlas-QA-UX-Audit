# Atlas-Internship-Portal-QA-UX-Audit-Case-Study

## 📌 Executive Summary
A comprehensive Quality Assurance (QA) and User Experience (UX/UI) audit performed on Greece’s national internship portal (**Atlas**). This project demonstrates manual testing methodologies, structured defect tracking using Jira, accessibility evaluations, and UX redesign proposals.

---

## 🛠️ Test Plan & Strategy
* **Objective:** Verify functional correctness, input validation, filtering logic, and UI usability of the search and filtering modules.
* **In Scope:** Keyword search, group code validation, filter combinations, sorting mechanisms, pagination, and accessibility (WCAG).
* **Out of Scope:** Authentication systems (TaxisNet) and administrative backend operations.
* **Tools Used:** 
  * *Test Management:* Google Sheets
  * *Bug Tracking:* Jira (Kanban Workflow)
  * *Browser Testing & Auditing:* Chrome DevTools, WAVE Accessibility Extension

---

## 📊 Test Cases & Traceability
The test suite covers positive and negative scenarios, linking execution results directly to reported defects.
* 🔗 [View Full Test Cases Spreadsheet (Google Sheets)](https://docs.google.com/spreadsheets/d/18HZgiVMgW8ek0KXBHI-Pi0ZaZLR4FYDyXMYbGR1ariA/edit?usp=sharing)

---

## 🐛 Defect Tracking & Jira Board
All identified functional bugs and UI/UX enhancements were logged and categorized using **Jira** following standard agile practices.

### Jira Board Overview

<img width="1895" height="850" alt="Στιγμιότυπο οθόνης (180)" src="https://github.com/user-attachments/assets/b89620b2-4a96-49e3-97d7-d9119ff50182" />
<img width="1260" height="779" alt="Στιγμιότυπο οθόνης (182)" src="https://github.com/user-attachments/assets/d0d052da-739b-4bed-b376-b2e1a6e3ccdb" />
<img width="1269" height="781" alt="Στιγμιότυπο οθόνης (181)" src="https://github.com/user-attachments/assets/eafd7af0-3da3-4754-a727-e9e96997496f" />




### Summary of Reported Issues:
1. **ATLAS-1 (Bug - Medium):** Search by Group Code triggers prematurely before full input.
2. **ATLAS-2 (Bug - High):** Keyword search for "QA" returns irrelevant positions.
3. **ATLAS-3 (Bug - Medium):** Employer search displays organizations with 0 active positions.
4. **ATLAS-4 (Bug - Medium):** Sorting by Date / Group Code fails to reorder results.
5. **ATLAS-5 to ATLAS-9 (Stories/Improvements):** Pagination scroll fixes, duration filter integration, multi-tag selectors, and date-range picker enhancements.

---

## 🎨 UI/UX Redesign & Next Steps
Based on the audit findings, an interactive high-fidelity prototype was designed in **Figma** to resolve usability bottlenecks.
* 🔗 [Figma Prototype Link](https://www.figma.com/design/pXMvvM1wncABghat1gASP4/Untitled?node-id=0-1&t=WYN7JeA4AItXi6Kk-1)

<img width="1440" height="1024" alt="Untitled" src="https://github.com/user-attachments/assets/278064ff-07cb-4706-9f53-28de5d657839" />





