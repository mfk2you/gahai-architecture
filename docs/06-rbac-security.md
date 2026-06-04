# Gahai HMS RBAC & Security Architecture

## Overview

Security is a foundational component of Gahai HMS.

The platform uses a role-based access control (RBAC) architecture with fine-grained permissions, audit logging, financial authority controls, and future device trust integration.

---

## Security Objectives

* Protect patient data
* Enforce least privilege access
* Prevent unauthorized financial actions
* Maintain complete auditability
* Support multi-tenant isolation

---

## Authorization Layers

### Tenant

Highest organizational boundary.

### Branch

Location-based security boundary.

### Department

Operational security boundary.

### Role

Defines job function.

Examples:

* Receptionist
* Doctor
* Nurse
* Cashier
* Manager
* Owner

### Permission

Fine-grained action control.

Examples:

* patient.view
* patient.edit
* billing.payment_create
* inventory.adjust
* workflow.approve

---

## Financial Authority

Financial operations require authority levels.

Examples:

* Cash Collection
* Refund Approval
* Discount Approval
* Credit Note Approval

---

## Audit Requirements

Every critical action records:

* User
* Role
* Date
* Time
* Branch
* Previous Value
* New Value

---

## Future Enhancements

* Device Trust
* Biometric Authentication
* MFA
* Risk-Based Access Controls

---

## Design Principles

* Zero Trust Mindset
* Least Privilege
* Full Auditability
* Tenant Isolation
