# Metadata Model – Business Glossary Simulation

This file outlines the metadata structure and roles used in this mock business glossary project, inspired by Collibra's data governance model.

---

## Core Asset: Business Term

Each business term contains the following attributes:

- **Name**: The glossary term (e.g., "Customer ID")
- **Definition**: A clear, standardised explanation
- **Domain**: Logical grouping (e.g., "Customer Data")
- **Steward**: Responsible for managing the term
- **Status**: Lifecycle stage – Draft, In Review, Approved

---

## Relationships

- Each **Business Term** belongs to a **Domain**
- Each term is assigned a **Steward**
- Status reflects review & approval workflow

---

## Roles

| Role    | Description |
|---------|-------------|
| Steward | Oversees and manages the term definition and updates |
| Owner   | (Optional) Final approver or business sponsor for the domain |
| Reviewer | Participates in the approval workflow |

---

## Domains (Examples)

- Customer Data
- Financial Metrics
- Logistics Metrics
- Inventory
- Analytics

---

## Term Lifecycle

```text
Draft → In Review → Approved
