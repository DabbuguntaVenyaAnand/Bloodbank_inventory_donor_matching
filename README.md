# Blood Bank Inventory & Emergency Donor Matcher

**Department of Computer Science and Engineering — PES University**  
**Course:** Software Engineering Lab  
**Lab 1:** Requirements Engineering & UML Use-Case Modelling  
**Problem Statement #12:** Blood Bank Inventory & Emergency Donor Matcher (Healthcare & Telemedicine)  
**Student Name:** Dabbugunta Venya Anand  
**SRN:** PES1UG24AM074  

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
