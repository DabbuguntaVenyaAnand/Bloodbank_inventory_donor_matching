# Blood Bank Inventory & Emergency Donor Matcher

**Course:** Software Engineering  
**Problem Statement #12:** Blood Bank Inventory & Emergency Donor Matcher (Healthcare & Telemedicine)  

---

## Team Members & Collaborators
| Sl. No. | Student Name | SRN |
| 1 | **Dabbugunta Venya Anand** | PES1UG24AM074 |
| 2 | *Harish Ramesh Kumar* | *PES1UG24AM111* |
| 3 | *Bhogala Srika* | *PES1UG24AM067* |
| 4 | *Karthik S Prabhu* | *PES1UG25AM805* |

---

## Repository Structure
This repository serves as the shared workspace for the team's lab submissions across the semester as well as the final project development:

```text
Bloodbank_inventory_donor_matching/
├── Lab 1/
│   ├── DabbuguntaVenyaAnand_PES1UG24AM074_LAB1.pdf
│   ├── [Member2]_LAB1.pdf
│   ├── [Member3]_LAB1.pdf
│   └── [Member4]_LAB1.pdf
├── Lab 2/                          # (Upcoming Lab Submissions)
├── docs/                           # Architecture, SRS, and Design Documents
├── src/                            # Final Semester Project Development Source Code
└── README.md                       # Project & Lab Documentation
```

---

## 1. Problem Context & Overview

Blood banks require a real-time stock management and emergency response system that monitors blood component shelf lives and triggers geo-targeted emergency notifications to matching eligible donors during critical shortages.

Perishable blood products (whole blood, plasma, platelets) have strict expiration windows. In critical emergencies, delays in locating compatible blood units or eligible nearby donors can be fatal. This system addresses these challenges through:
- Automated real-time inventory tracking and expiration alerts.
- Automated compatibility verification (ABO and Rh(D) matching).
- Geo-targeted donor notification (within a 10 km radius) during critical shortages.
- Strict transactional consistency to prevent double-allocation of life-saving units.

### Target Stakeholders & Actors
- **Primary Actors:**
  - **Blood Bank Manager:** Manages inventory stock levels, reviews expiry warnings, prioritizes allocations, and initiates transfers.
  - **Emergency Requester / Verified Medical Centre:** Submits high-urgency or scheduled blood unit requests.
  - **Donor:** Registers/updates medical profile, receives emergency alerts, and confirms donation availability.
- **Supporting / External Actors:**
  - **SMS Gateway (External System):** Delivers emergency broadcasts and alerts to donors and managers.
  - **Partner Blood Bank Network (External System):** Receives surplus transfer notifications and coordinates inter-facility transfers.

---

## 2. Lab Submissions

### Lab 1: Requirements Engineering & UML Use-Case Modelling
- **Submission Directory:** [`Lab 1/`](./Lab%201/)

