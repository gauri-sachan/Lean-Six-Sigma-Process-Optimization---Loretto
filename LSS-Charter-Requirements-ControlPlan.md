# Laundry Process Optimization – Project Charter, Solution Requirements & Control Plan
**Loretto Health & Rehabilitation | Syracuse, NY | 2025**

---

## PART 1: PROJECT CHARTER

**Project Name:** Laundry Process Improvement at Loretto Health & Rehabilitation
**Business/Location:** Loretto Health & Rehabilitation, 700 E Brighton Ave, Syracuse, NY 13205
**Team Leader:** Gauri Sachan
**Champion:** Luan, Head of Housekeeping, Loretto
**Prepared By:**Gauri Sachan and Meghana Nair**
**Date (Last Revision):** December 04, 2025
**Project Start:** September 2025 | **Project Completion:** December 16, 2025

---

### Problem Statement
Laundry operations at Loretto Health & Rehabilitation were experiencing frequent delays and backlogs, machine breakdowns, and a lack of reliable data to confirm when laundry was picked up or delivered — resulting in limited process visibility and reactive management.

---

### Business Case
Efficient laundry operations are essential to resident hygiene, satisfaction, and overall operational effectiveness. Current inefficiencies in turnaround time, workload balance, and service consistency increase non-value-added time and operational strain. Improving visibility, staff utilization, and washing capacity through low-cost digital tools and data-driven decision-making will reduce delays, support proactive management, and deliver sustainable operational and service-quality benefits.

---

### Key Customers & Expectations

| Customer | Expectations |
|----------|-------------|
| Residents | Timely pickup and delivery, accurate delivery to correct rooms, minimal delays |
| Facility Administration | Reliable and consistent laundry service, visibility into laundry status |
| Laundry Management | Balanced staff workload, real-time performance data |

---

### Project Scope

**In Scope:**
- Laundry pickup and delivery activities
- Staff time utilization measurement
- Washing and drying machine performance
- Digital tracking using Google Forms
- Performance visualization using Tableau
- Pilot testing of improvement solutions

**Out of Scope:**
- Nursing or clinical operations
- Resident behavior changes
- Major facility infrastructure changes
- Linen laundry

---

### Team Members
Meghana Nair, Gauri Sachan, Kaavya Shastri, and Vaishnavi Sulakhe

---

### Risk Assessment

| Risk | Mitigation |
|------|-----------|
| Low adoption of the tracking system | Simple form design and staff training |
| Continued washing machine downtime | Preventive maintenance and additional machine recommendation |
| Limited data during pilot period | Extended monitoring post-implementation |

---

## PART 2: SOLUTION REQUIREMENTS DOCUMENT

### Overview
The Improve phase introduced three practical, low-cost solutions to address validated root causes. Each solution had defined functional requirements to ensure effectiveness and sustainability.

---

### Solution 1: Digital Laundry Tracking System (QR Code + Google Form)

**Purpose:** Standardize recording of laundry pickup and delivery activities to eliminate visibility gaps.

**Functional Requirements:**

| Requirement | Detail |
|-------------|--------|
| Trigger | QR code scanned by staff at each resident's bathroom door |
| Form Fields | Room number, Building (Cunningham/Fahey), Floor, Laundry Status, Staff Name, Auto-timestamp |
| Status Options | Picked Up / Delivered / No Access / Family Does Laundry / No Soiled Laundry |
| Completion Timing | Must be filled immediately after each pickup or delivery attempt |
| Data Storage | Automatically stored in centralized Google Sheets dataset |
| Accessibility | Mobile-friendly, no login required for staff |

**Non-Functional Requirements:**
- Must not disrupt daily staff workflows
- Must be simple enough to require minimal training
- Must capture consistent, time-stamped data across all shifts

**Form Link:** [Google Form](https://docs.google.com/forms/d/e/1FAIpQLScCL_8AGKDN62QNxb3OBTiDzfrWj4uTnw2KhqZb6MmOYOqbdw/viewform?usp=sharing&ouid=107874309815827761089)

---

### Solution 2: Tableau Performance Dashboard

**Purpose:** Transform raw tracking data into actionable performance insights for management.

**Functional Requirements:**

| Dashboard Component | Purpose |
|--------------------|---------|
| Completion (%) | Daily performance against predefined service targets |
| Pickup vs Delivery Status Distribution | Volume of items picked up, delivered, pending, or no access |
| Staff-Level Activity Summary | Tasks completed per staff member to support balanced allocation |
| No Access Breakdown | Floor and building level view of why/how much laundry was not collected |

**Non-Functional Requirements:**
- Connected directly to Google Form responses for near real-time updates
- Accessible to Laundry Manager and Facility Administration
- Must support misappropriation incident back-tracking (date, time, staff, delivery confirmation)

**Dashboard Link:** [Tableau Public](https://public.tableau.com/app/profile/kaavya.shastri/viz/LSS-Laundry/Dashboard1?publish=yes)

---

### Solution 3: Laundry Bag (Over-the-Door Hanging Bag)

**Purpose:** Reduce no-access situations by allowing staff to collect soiled laundry without requiring entry into resident bathrooms.

**Functional Requirements:**
- Bag hangs on outside of bathroom door
- Staff collects laundry via zipper at bottom — no room entry required
- Reduces misdelivery risk by keeping laundry associated with specific resident room

---

### Solution 4: Additional Washing Machine (Recommendation)

**Purpose:** Directly address the capacity bottleneck caused by Washing Machine 2 downtime.

**Expected Impact:**

| Impact Area | Expected Outcome |
|-------------|-----------------|
| Washing Capacity | Increased overall throughput |
| Backlog | Reduced accumulation during peak demand |
| Staff Productivity | Reduced idle time during machine downtime |
| Process Resilience | Reduced sensitivity to single-machine failure |

---

## PART 3: KPI & CONTROL PLAN

### Control Objectives
- Maintain visibility into laundry operations post-project
- Ensure consistent use of the digital tracking system
- Monitor process performance against defined targets
- Enable timely corrective action when performance deviates
- Support continuous improvement using data-driven insights

---

### Key Performance Indicators (KPIs)

| KPI | Definition | Target | Frequency | Owner |
|-----|-----------|--------|-----------|-------|
| Laundry Turnaround Time | Time from pickup to delivery | Within daily service window | Daily tracking, weekly review | Laundry Manager |
| Pickup & Delivery Completion Rate | % of laundry activities completed vs planned | ≥ 90% | Daily | Supervisor |
| Staff Utilization | Productive time vs total shift time | Balanced — no overload | Weekly | Laundry Manager |
| Machine Availability | % of scheduled machine uptime | ≥ 90% | Weekly | Maintenance / Laundry Manager |
| Tracking Compliance | % of pickups and deliveries logged in Google Form | ≥ 98% | Daily | Supervisor |

---

### Standard Operating Procedures (SOPs)

**SOP 1: Laundry Pickup and Delivery**
- Staff must log every pickup and delivery attempt using the Google Form
- Status must be accurately selected: Picked Up / Delivered / No Access / Family Laundry
- Entries must be completed immediately after task execution — no batching

**SOP 2: Machine Operation and Downtime**
- Machine issues must be reported immediately to supervisor
- Downtime events must be logged
- Preventive maintenance schedules must be followed

**SOP 3: Dashboard Review**
- Supervisors review Tableau dashboard daily
- Laundry Manager reviews weekly performance trends
- Escalation triggered when KPI thresholds are breached

---

### Control Plan

| Process Step | Measurement System | Target if Deviated | Escalation Plan | Control Action | Monitoring |
|--------------|-------------------|-------------------|-----------------|----------------|------------|
| Laundry Pickup | Pickup/delivery log | Minor deviations → Level 1: Laundry Mgmt, then Admin | Reassign staff & prioritize high backlog areas | Reassign staff & prioritize high backlog | Daily dashboard |
| Wash & Backlog Clearance | Sort and clear backlog daily | Minor deviations → Level 1 | Prioritize washing loads & increase focus on washing stage | Prioritize pickup/delivery | Daily dashboard |
| Laundry Delivery | Deliver laundry to resident | Minor deviations → Level 1 | Review pickup/delivery prioritization | Pickup/delivery prioritization | Daily dashboard |
| Tracking | Google Form compliance | Minor deviations → Level 1 | Review entry process, simplify if needed | Review and simplify entry process | Daily dashboard |

---

### Ownership & Long-Term Monitoring

**Primary Owner:** Laundry Manager, Loretto Health & Rehabilitation

**Responsibilities:**
- Ensure SOP compliance across all shifts
- Review Tableau dashboards regularly
- Lead corrective actions when KPIs deviate
- Identify continuous improvement opportunities and escalate to Administration

---

### Lessons Learned

- Process inefficiencies are most often caused by system design, not individual performance
- Visibility and data are essential for effective decision-making in healthcare operations
- Low-cost digital tools (Google Forms + Tableau) can drive meaningful operational change
- Sustainable improvement requires clear ownership, defined KPIs, and control mechanisms
- Addressing both information flow and physical capacity constraints leads to more stable processes
