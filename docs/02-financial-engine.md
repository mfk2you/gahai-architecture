# Gahai HMS Financial Engine

## Overview

The Financial Engine provides a unified accounting and billing framework for all clinical and operational departments.

Departments do not manage balances.

The Financial Engine manages:

* Charges
* Payments
* Deposits
* Refunds
* Credit Notes
* Ledger Entries

---

## Core Principle

The Ledger is the financial truth.

Balances are calculated from ledger entries.

Balances are never manually edited.

---

## Core Objects

### Patient Account

Financial account for each patient.

### Charge

Represents money owed.

### Payment

Represents money received.

### Deposit

Represents prepaid funds.

### Refund

Represents money returned.

### Credit Note

Represents reductions in liability.

### Ledger Entry

Immutable accounting record.

---

## Supported Departments

* OPD
* IPD
* Dental
* Orthodontics
* Implants
* Pathology
* Pharmacy
* Inventory

---

## Goals

* Financial Consistency
* Auditability
* Revenue Protection
* Department Independence
