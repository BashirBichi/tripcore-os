# TripCore

TripCore is a travel business operating system for tour operators, travel agencies and destination businesses.

## Current build

The current frontend is intentionally free of seeded demo business records. Users can create, edit and delete their own workspace records through the interface.

Functional modules:

- Customers
- Trips & Tours
- Tour Packages
- Bookings
- Payments & Invoices
- Expenses
- Hotels / Accommodation
- Visa & Travel Documents
- Transport
- Staff & Tasks
- Marketing / Leads
- Reports
- Notifications
- Workspace settings

## Current persistence

This build uses browser localStorage as a temporary persistence layer so the interface can be tested without a backend.

Data is stored under the `tripcore.v1` key and is isolated to the current browser profile.

## Next production layer

The next implementation phase should replace localStorage with authenticated multi-tenant backend storage and PostgreSQL persistence, while keeping the current workflow and UI contract.

## Prototype reference

The original visual prototype remains under `prototype/TripCore_Travel_Business_Prototype.html`.
