# Product Backlog

## MVP Priorities
- P0: Core appointment scheduling and calendar management
- P0: Pet and owner record management
- P0: Vaccination, deworming, medical history, and weight tracking
- P0: Mobile-friendly owner portal with pet profile access
- P0: Preventive care and appointment reminders for owners
- P0: One-tap emergency contact from the owner experience
- P1: Advanced reporting and administrative enhancements

## Epics and User Stories

### Epic 1: Appointment Scheduling
**Goal:** Enable staff to schedule and manage appointments effectively.

- As a receptionist, I want to create and update appointments so that the clinic schedule stays organized.
- As a receptionist, I want to avoid double-booking so that clients receive reliable service.
- As a clinic manager, I want to view upcoming appointments so that staff capacity is managed effectively.

**Acceptance Criteria**
- Given a new appointment request, when a receptionist creates it, then the system stores the appointment with date, time, pet, owner, and reason.
- Given an existing appointment, when the receptionist attempts to create a conflicting time slot, then the system prevents the overlap.
- Given an appointment is created, when staff open the schedule, then they can view it in a clear calendar view.

### Epic 2: Pet and Owner Records
**Goal:** Maintain accurate pet and owner information in one place.

- As a receptionist, I want to create and update pet records so that clinical staff can access accurate patient details.
- As a veterinarian, I want to review owner and pet information quickly so that care can be delivered efficiently.
- As a clinic manager, I want a single record for each pet and owner so that information is consistent.

**Acceptance Criteria**
- Given a new pet visit, when the staff enters pet details, then the system stores the pet profile with identifying information.
- Given an owner profile exists, when pet records are added, then the owner can be linked to the pet.
- Given a record is updated, when staff view the profile, then the latest information is shown.

### Epic 3: Clinical Care Tracking
**Goal:** Track essential health information over time.

- As a veterinarian, I want to record vaccinations so that preventive care is documented.
- As a veterinarian, I want to record deworming events so that parasite prevention history is preserved.
- As a veterinarian, I want to track pet weight over time so that health trends are visible.
- As a clinic manager, I want to view medical history so that treatment decisions are informed.

**Acceptance Criteria**
- Given a vaccination is administered, when the record is entered, then the system stores the date, vaccine type, and notes.
- Given a deworming treatment is administered, when the record is entered, then the system stores the date, product, and notes.
- Given a pet has multiple weight entries, when the history is viewed, then the system presents the trend over time.
- Given a pet has prior visits, when medical history is reviewed, then the system lists relevant records in chronological order.

### Epic 4: Owner Portal Access
**Goal:** Give pet owners a mobile-friendly way to view their pet's information.

- As a pet owner, I want to access a mobile-friendly portal so that I can view my pet's information from my phone.
- As a pet owner, I want to see my pet's complete profile so that I can review health history and upcoming care.
- As a pet owner, I want to view upcoming appointments so that I can plan visits and reminders.

**Acceptance Criteria**
- Given an owner has portal access, when they sign in, then they can view a mobile-friendly dashboard with their pets.
- Given a pet is selected, when the owner opens the profile, then they can view a clinic-approved summary of medical history, vaccination records, deworming history, weight history, and upcoming appointments.
- Given the owner is viewing a pet profile, when they open the appointments section, then they can see scheduled upcoming visits.

### Epic 5: Communications and Reminders
**Goal:** Help clinics and owners stay aligned on upcoming care.

- As a clinic manager, I want preventive care reminders to be sent automatically so that clients attend follow-up appointments.
- As a pet owner, I want reminder notifications so that I do not miss important vaccinations, preventive care, or appointments.
- As a pet owner, I want a quick emergency contact action so that I can reach the clinic promptly if needed.

**Acceptance Criteria**
- Given a preventive care event is due, when the reminder rules are met, then the system generates a reminder.
- Given a reminder is created, when the client is notified, then the message includes the relevant care item, date, and channel used.
- Given an owner selects the emergency contact action, when the action is triggered, then the device initiates a call to the clinic's dedicated emergency line.
- Given a reminder is sent, when staff review the reminder log, then the status is visible.
