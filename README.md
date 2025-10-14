# 🎯 Business Analyst Case Study: Indirect Tax Reporting with ETRM - Phase 2
This is Phase 2 of my work on a fictional case study project (for portfolio purposes) where I worked on improving indirect tax reporting in an Energy Trading and Risk Management (ETRM) system for a large oil &amp; gas trading company. 

<img width="350" alt="image" src="https://github.com/user-attachments/assets/7e181ed1-0f25-4f3e-bec4-1f35baa8d7c3" />

---

## 📘 Table of Contents  
1. [Project Background](#1-project-background)  
2. [Business Requirements Document (BRD)](#2-the-business-requirements-document-brd)  
3. [Requirement Details](#3-digging-into-requirement-details)  
4. [Functional Requirements Document (FRD)](#4-building-the-functional-requirements-document-frd)  
5. [Starting with the Data](#5-starting-with-the-data)  
6. [Data Flow & Diagrams](#6-getting-more-into-data-and-diagrams)  
7. [Bringing Data to Life (Data Dictionary)](#7-bringing-data-to-life)  
8. [Report Functional Specification (RFS)](#8-bringing-the-report-to-life-report-functional-specification)  
9. [Tools & Methods](#9-tools--methods-used)  
10. [Deliverables](#10-key-deliverables-created)  
11. [Outcomes](#11-outcomes)  
12. [Learnings & Reflection](#12-key-learnings--reflection)  

---

## 1. Project Background  

In Phase 1, I led the project from defining the **problem and current-state analysis** — manual data handling, fragmented workflows, and compliance risks — to designing a **future-state solution** integrating a **low-code tax engine** for automated validation, reporting, and audit readiness.  

I established **measurable goals** (efficiency, compliance, agility), built a **business case with ROI and risk analysis**, and created artifacts such as process flows, stakeholder maps, and governance plans to ensure sustainable delivery.  

The project culminated in a **clear, data-driven recommendation** demonstrating **90% automation** and measurable **time and cost savings**.  

---

## 2. The Business Requirements Document (BRD)  

Having completed the Business Case, I used that foundation to develop the **Business Requirements Document (BRD)**.  


### 🧩 Key Activities
- Defined high-level business requirements aligned with the approved Business Case.  
- Identified dependencies affecting delivery or system behavior.  
- Created a high-level **use case diagram** to visualize user interactions.  
- Built a **gap analysis diagram** to highlight improvement areas.  
- Compiled a **glossary** for consistent terminology.  



> ✨ **Lesson Learned:** Traceability matters: linking each requirement back to a business objective prevents scope drift and ensures alignment.  

---

## 3. Digging into Requirement Details  

I transformed high-level goals into **detailed, testable functional and non-functional requirements**.  

### 🔍 Key Activities
- Developed detailed requirements tied to the BRD.  
- Defined measurable **acceptance criteria** for validation and testing.  
- Prioritized critical requirements.  
- Started a list of tax reports to be developed later.  


> ✨ **Lesson Learned:** Clarity drives collaboration. Testable requirements help align analysts, developers, and business users.  

---

## 4. Building the Functional Requirements Document (FRD)  

The **FRD** bridges business needs and technical design — defining what the system should do so every team shares the same vision.  

<details>
<summary>🧱 Key Sections Developed</summary>

- **Use Cases:** Described user interactions and alternate/exception flows.  
- **Data Requirements:** Defined entities like transactions, tax rules, and reports.  
- **Interface Requirements:** Outlined system integrations to avoid silos.  
- **Reporting Overview:** Identified key tax reports and where details reside.  
- **Tax Rules Overview:** Emphasized the importance of accuracy for compliance.  
- **Requirements Traceability Matrix (RTM):** Linked business and functional requirements.  

</details>

> ✨ **Lesson Learned:** A strong FRD connects strategy to execution — giving developers clarity, stakeholders confidence, and teams alignment.  

---

## 5. Starting with the Data  

Before finalizing report designs, I focused on **understanding the data** — the foundation for accurate, compliant reporting.  

<details>
<summary>📊 Key Activities</summary>

- Built a **high-level ERD** for the State Motor Fuel Tax Monthly Return.  
- Identified **9 key entities**, including Transactions, Movements, Tax Rules, and Jurisdictions.  
- Defined initial relationships between entities.  
- Scoped the model to one report to stay focused.  

</details>

> ✨ **Lesson Learned:** A good data model reduces rework and builds trust in the reports you deliver.  

---

## 6. Getting More into Data and Diagrams  

After the ERD, I created a **Data Flow Diagram (DFD)** to understand how data moves through the system — connecting processes, data stores, and external actors.  

> ✨ **Lesson Learned:** Visualizing data flow builds understanding — clarifying what each process consumes and produces.  

---

## 7. Bringing Data to Life  

I developed the **Data Dictionary**, bridging data structure and business context.  

<details>
<summary>📗 My Approach</summary>

- Started from the **report spec** to define required fields.  
- Worked **backward** to identify each field’s source table and data type.  
- Included **sample data** for each table to make it tangible and contextual.  

</details>

> ✨ **Lesson Learned:** Seeing sample data makes the abstract concrete — revealing format and consistency issues early.  

---

## 8. Bringing the Report to Life (Report Functional Specification)  

One of the most rewarding milestones — developing the **Report Functional Specification (RFS)** for the State Motor Fuel Tax Report.  

<details>
<summary>📘 Key Activities</summary>

- Defined **business purpose**, fields to display, and filter parameters.  
- Mapped each report field to its **source** and defined **join logic**.  
- Created a **mockup layout** with sample data for realism.  
- Documented:  
  - Access permissions & data sensitivity  
  - Assumptions, dependencies, and constraints  
  - High-level testing scenarios for validation  

</details>

> ✨ **Lesson Learned:** The RFS turns understanding into a buildable design — where business logic meets technical clarity.  

---

## 9. Tools & Methods Used  

| Tool | Purpose |
|------|----------|
| **Microsoft Word** | BRD, FRD, and RFS documentation |
| **Draw.io** | Diagrams – Use Case, Gap, ERD, DFD |
| **Excel** | RTM, Data Dictionary, and sample tables |

---

## 10. Key Deliverables Created  

- ✅ Business Requirements Document (BRD)  
- ✅ Use Case Diagram  
- ✅ Gap Analysis Diagram  
- ✅ Functional Requirements Document (FRD)  
- ✅ Requirements Traceability Matrix (RTM)  
- ✅ Entity Relationship Diagram (ERD)  
- ✅ Data Flow Diagram (DFD)  
- ✅ Data Dictionary  
- ✅ Report Functional Specification (RFS)  

---

## 11. Outcomes  

- Aligned business requirements with the Business Case.  
- Produced detailed, testable functional & non-functional requirements.  
- Defined acceptance criteria supporting UAT readiness.  
- Created ERD & DFD visualizing how tax data moves across systems.  
- Documented key data entities & examples for the State Motor Fuel Tax report.  
- Delivered a **developer-ready, stakeholder-approved blueprint** bridging business intent and technical execution.  

---

## 12. Key Learnings & Reflection  

- **Templates are guides, not rules.** Adapt to your project’s needs.  
- **Know when to stop analyzing.** Aim for “just enough” to move forward.  
- **Iterate and validate.** First drafts are conversation starters.  
- **Diagrams expose dependencies.** They reveal missing data or gaps early.  
- **Always start with business purpose.** The “why” shapes the “what.”  
- **Consistency builds trust.** A clear Data Dictionary aligns teams.  
- **Visuals drive alignment.** ERDs, DFDs, and mockups turn complexity into shared understanding.  

> 💡 **Final Reflection:**  
> This project strengthened my ability to **bridge business and technical perspectives** — turning regulatory complexity into structured clarity. It reaffirmed that strong business analysis isn’t about perfection, but about **communication, traceability, and confidence** in delivering solutions that work.  

---



