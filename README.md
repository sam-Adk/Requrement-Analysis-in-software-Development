# Requrement Analysis in software Development


This repository is created as part of a learning project to understand the importance of **Requirement Analysis** in the Software Development Lifecycle (SDLC).  
It contains structured documentation, diagrams, and examples demonstrating how requirement analysis ensures successful software projects.

---

## What is Requirement Analysis?
Requirement Analysis is the process of identifying, gathering, and documenting the needs and expectations of stakeholders for a software system.  
It ensures that the final product meets user needs and aligns with business goals.  

Key points:
- Acts as the foundation of the SDLC.  
- Minimizes misunderstandings between stakeholders and developers.  
- Helps define scope, functionality, and constraints of the system.  

---

## Why is Requirement Analysis Important?
Requirement Analysis is critical in SDLC because:
1. **Prevents Costly Errors**  
   Early identification of requirements avoids expensive fixes later in development.  

2. **Ensures Stakeholder Alignment**  
   Provides a clear understanding of user needs and business goals.  

3. **Improves Quality and Usability**  
   Well-defined requirements result in software that is reliable, user-friendly, and fit for purpose.  

---

## Key Activities in Requirement Analysis
The five main activities include:

- **Requirement Gathering** – Collecting needs from stakeholders.  
- **Requirement Elicitation** – Engaging with stakeholders through interviews, surveys, and workshops.  
- **Requirement Documentation** – Recording requirements clearly (e.g., SRS documents).  
- **Requirement Analysis and Modeling** – Breaking down requirements and modeling them into diagrams or specifications.  
- **Requirement Validation** – Verifying that requirements are complete, feasible, and aligned with objectives.  

---

## Types of Requirements

### Functional Requirements
Define **what the system should do**.  
Examples for a booking management system:
- Users can create, update, or cancel a booking.  
- The system sends confirmation emails after a booking.  
- Admins can manage availability and pricing.  

### Non-functional Requirements
Define **how the system should perform**.  
Examples:
- The system should support up to 10,000 concurrent users.  
- Response time for booking confirmation must be under 2 seconds.  
- The application must be available 99.9% of the time.  

---

## Use Case Diagrams
Use Case Diagrams visually represent the interactions between **actors** (users or systems) and **use cases** (system functions).  

**Benefits:**
- Easy to understand for both technical and non-technical stakeholders.  
- Helps identify all required functionalities.  

![Booking System Use Case Diagram](./alx-booking-uc.png)  

---

## Acceptance Criteria
Acceptance Criteria define the conditions that a feature must meet to be accepted by stakeholders.  

**Importance:**
- Prevents ambiguity by setting clear expectations.  
- Serves as a reference point for testing.  

**Example (Checkout Feature in Booking System):**
- The system must allow users to securely enter payment details.  
- The system must confirm successful payment and generate a booking reference.  
- The system must send a confirmation email to the user within 1 minute.  

---
