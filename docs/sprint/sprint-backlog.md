# Sprint 1 Backlog

## Sprint Goal
Deliver a usable MVP for clinic staff and pet owners covering appointment management, pet and owner records, basic care tracking, owner access, and reminder/emergency workflows.

## Selected Stories

### 1. Appointment Scheduling
**Story:** As a receptionist, I want to create and update appointments so that the clinic schedule stays organized.

**Story Points:** 8

**Implementation Tasks:**
- Create appointment data model and validation rules
- Build appointment creation form for staff
- Implement appointment update and edit flow
- Prevent double-booking for conflicting time slots
- Display appointments in a calendar or list view
- Add basic appointment status handling

### 2. Pet and Owner Records
**Story:** As a receptionist, I want to create and update pet records so that clinical staff can access accurate patient details.

**Story Points:** 5

**Implementation Tasks:**
- Create pet and owner profile data structures
- Build pet creation and editing screens
- Link pets to owners and store core profile data
- Add basic validation for required fields
- Provide staff access to view pet and owner records

### 3. Clinical Care Tracking
**Story:** As a veterinarian, I want to record vaccinations and other care events so that preventive care is documented.

**Story Points:** 8

**Implementation Tasks:**
- Create care event models for vaccinations, deworming, weight, and medical history
- Build forms for entering care records
- Display care history in chronological order
- Support weight entry and basic trend viewing
- Add validation for care event dates and notes

### 4. Owner Portal Access
**Story:** As a pet owner, I want to access a mobile-friendly portal so that I can view my pet's information from my phone.

**Story Points:** 13

**Implementation Tasks:**
- Define owner authentication and access flow
- Build mobile-friendly dashboard for owner login and pet selection
- Create pet profile view for owners with clinic-approved summaries
- Display upcoming appointments and reminders in the portal
- Ensure the experience is responsive for mobile screens

### 5. Communications and Reminders
**Story:** As a pet owner, I want reminder notifications so that I do not miss important vaccinations, preventive care, or appointments.

**Story Points:** 8

**Implementation Tasks:**
- Define reminder rules for appointments and preventive care events
- Create reminder generation workflow
- Support reminder delivery through configured channels
- Implement emergency contact action that initiates a call
- Show reminder status and history for staff review

## Sprint Notes
- This sprint focuses on delivering the MVP scope with the most critical clinic and owner workflows.
- Some items depend on business decisions around authentication, reminder channels, and portal visibility.
- The scope is intentionally limited to core workflows and does not include advanced reporting or broader integrations.
