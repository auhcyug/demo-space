# Altea/Amadeus PSS Glossary

**Last Updated:** 2025-11-05

This glossary contains terms related to **Amadeus Altea Passenger Service System (PSS)** - the core reservation and departure control platform used across SIA.

---

## Overview

**Amadeus Altea PSS** is SIA's primary passenger service system, used by multiple departments including:
- Customer Services (reservations, check-in)
- Ground Operations (departure control)
- Sales & Revenue Management
- Operations Control Centre

**Altea PSS Components:**
- **RES** - Reservation System
- **INV** - Inventory Management
- **DCS** - Departure Control System (CM + FM)
- **CM** - Customer Management
- **FM** - Flight Management

**Category:** System-Specific (Technology Platform)

This is a cross-departmental system, not specific to any single department.

---

## Response Guidelines

**For comprehensive response guidelines on using Altea/Amadeus terms, see [`index.md`](index.md) - Response Guidelines section.**

---

## Amadeus Altea System Components

| Term | Full Form | Definition | Context |
|------|-----------|------------|---------|
| Amadeus, 1A | Analyse MAjor Database from EUropean Sources | Amadeus GDS (Global Distribution System) | GDS, reservations |
| 1A | Amadeus | Amadeus reservation/check-in system (GDS code) | Reservations, check-in, operations |
| Altea | - | Amadeus Passenger Service System (PSS) platform | Core reservation platform |
| PSS | Passenger Service System | Amadeus Altéa Passenger Service System (PSS = RES + INV + DCS) | Reservations, operations |
| CRS/RES | Central REServation System / Altea Reservation | Altea reservation system (RES is part of Altea PSS) | Reservations, booking |
| INV, Inv | Altea Inventory | Amadeus Altéa Inventory module; inventory management component of Altea PSS (distinguished from other Altea modules: RES, DCS, CM, FM) | Reservations, inventory management |
| DCS | Departure Control System / Altea Departure Control System | Altea system managing flight departures (DCS = CM + FM) | Operations, ground services |

---

## Altea Modules & Applications

| Term | Full Form | Definition | Context |
|------|-----------|------------|---------|
| ARD | Amadeus Reservations Desktop / Altéa Reservation Desktop | Altea reservation and customer management application | Reservations, customer management |
| CM | Altea Customer Management | Amadeus Altea customer management module | Reservations, customer management |
| FM | Altea Flight Management | Amadeus Altea flight management module | Flight operations, departure control |
| APP | Advanced Passenger Processing | Altea customer management function | Altea CM, operations |
| AGM | Altea Group Manager | Altea group management tool | Revenue management, operations |
| ACE | Altea Centre of Expertise | Altea center of excellence | Ground operations, expertise |
| WBS | Altea Web Services | Altea web services for integration | API, integration |

---

## Amadeus Platforms & Products

| Term | Full Form | Definition | Context |
|------|-----------|------------|---------|
| AAM | Amadeus Anytime Merchandising | Amadeus merchandising platform | Merchandising, ancillary services |
| ARP | Amadeus Retailing Platform | Platform for retailing and merchandising | Merchandising, e-commerce |
| ASW | Amadeus Sales Watcher | Amadeus sales monitoring tool | Sales, analytics |
| ARI | Amadeus Revenue Integrity | Rule-based system to detect and cancel duplicate bookings | Revenue management, booking integrity |
| ALSA | Amadeus Leisure Solutions Agreement | Amadeus leisure solutions contract | Amadeus partnership, systems |

---

## Ticketing & Pricing

| Term | Full Form | Definition | Context |
|------|-----------|------------|---------|
| TST | Transitional Stored Ticket | Contains the ticket price information in the Amadeus reservation system | Ticketing, pricing |
| TSM | Transitional Stored Miscellaneous | Contains ancillary add-ons (e.g., excess baggage, seat selection) | Ancillaries, pricing |
| SAT | Service, Issuance and Aftersales (Ticketing) | Amadeus electronic ticketing module (Reservation Issuance and Aftersales) | Ticketing, reservations |
| FA | Fare Element | Automatically created fare element for each passenger and new ticket | Ticketing, Amadeus |
| FH | Transaction Code | Transaction code to manually add ticket number when not automatically issued | Ticketing, Amadeus |
| FHA | Automated Ticket Number | Automated ticket number element | Ticketing, Amadeus |
| FHE | Electronic Ticket Number | Transaction code to manually associate ticket number when not automatically issued | Ticketing, Amadeus |
| TTP | Ticket/Transaction Process | Entry code for ticket issuance in Altea | Ticketing, Altea commands |
| TTM | Ticket/Transaction Message | Entry code for EMD issuance in Altea | Ticketing, Altea commands |

---

## KrisFlyer & Revenue Management

| Term | Full Form | Definition | Context |
|------|-----------|------------|---------|
| FFR | Frequent Flyer Redemption | Redemption booking (miles only) | KrisFlyer, bookings |
| FFK | Frequent Flyer Kommercial | Commercial booking used with miles (whole or partially) | KrisFlyer, hybrid bookings |

---

## Inventory & Data Management

| Term | Full Form | Definition | Context |
|------|-----------|------------|---------|
| IIP | Inventory Interface Platform | Amadeus system for inventory data synchronization | Reservations, inventory management |
| RDI | Reservation and Departure Control Interface | Amadeus interface for reservation and departure systems | Reservations, departure control |
| PODS | Passenger Operational-Data Distribution System | Captures transactional data from Altea for distribution to downstream internal or external applications | Customer service, data distribution |

---

## Booking & Customer Records

| Term | Full Form | Definition | Context |
|------|-----------|------------|---------|
| CPR | Customer & Product Record | Amadeus customer and product record | Booking, reservations |
| VCIP | Validating Carriers Preferences in Interline Scenario | Altea rule governing interaction with other airlines' products through Amadeus | Altea, interline operations |
| PNE | (Amadeus Component) | Amadeus system component (not used by SQ) | Amadeus systems |

---

## PNR Status Codes

| Code | Meaning | Context |
|------|---------|---------|
| RX | Reassociation of eticket on ARD | Ticket reassociation in Amadeus |

---

## Access Management

| Term | Full Form | Definition | Context |
|------|-----------|------------|---------|
| ACL | Access Control List | List of permissions for Altea system access | Altea access management, security |
| BU RFC | Business Unit Request for Change | Request for role/ACL changes in Altea systems | Change management, Altea access |

---

## Support & Maintenance

| Term | Full Form | Definition | Context |
|------|-----------|------------|---------|
| PTR | Problem Tracking Record | Issue tracking number for test environment issues (UAT); tickets raised to Amadeus for issues found in testing | UAT, testing, Amadeus support |

---

## Related Documentation

**SIA-Specific Terms:**
- `general.md` - General SIA-wide terms
- `customer-service.md` - Customer Services Department (uses Altea extensively)
- `aviation.md` - Aviation industry standards

**Systems & Processes:**
- `../systems-tools.md` - System documentation
- `../processes/altea-access-management.md` - Altea access request process
- `../key-contacts.md` - Customer Services and PSS team contacts

---

## Additional Information

**Amadeus Altea Suite:**
The Altea suite is composed of multiple integrated modules that work together to manage the complete passenger journey from reservation to departure.

**Primary Users at SIA:**
- Customer Services Department (CCS, PSS teams)
- Ground Operations
- Check-in Staff
- Revenue Management
- Sales Teams

**Official Documentation:**
For detailed Amadeus documentation, refer to internal Amadeus Confluence pages or contact the PSS team.

---

**Questions about Altea/Amadeus systems?** Contact the PSS (Passenger Servicing Systems) team within Customer Services Department.