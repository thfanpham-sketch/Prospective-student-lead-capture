📌 Prospective Student Lead Capture – Business Analysis Objectives
🎯 Purpose:
Demonstrate the future-state process and requirements for capturing prospective student leads.

📖 Case Study:
Prospective students browse course pages on the University’s website and want to express interest in studying. The Marketing team needs this information to include students in lead nurture campaigns (e.g., Open Day).

❗ Problem Statement:

No online lead capture form exists; Marketing only learns about prospects at events (reactive process).
Marketing cannot proactively nurture leads before events.
Contact information collection is inconsistent, making campaign inclusion difficult.


✅ Business Requirements
Goal:
Implement an online Lead Capture form to allow future students to provide their contact information.
Objectives:

Capture key contact information (name, email, course interest).
Capture opt-in status for marketing communications.
Record this information in the University’s CRM (Salesforce).


🛠 Activities Completed:


Stakeholder Identification
Primary: Prospective Students, Marketing Team, CRM Admin
Secondary: Web Team, Compliance, Admissions


Requirements Clarification
Functional: Form submission, validation, duplicate prevention, confirmation email, Salesforce integration, export capability.
Non-functional: Performance, security, availability, usability, compliance.


Mind Map
Expanded requirements visually for stakeholder review.


Process Modeling
Created Level 1 (high-level) and Level 2 (detailed swimlane) diagrams for future-state EOI process.


User Story & Acceptance Criteria
Defined user story for prospective student with Gherkin-style acceptance criteria.
Prioritized requirements using MoSCoW.



📋 User Story
As a prospective student
I want to submit my contact details and course interest through an online Expression of Interest (EOI) form
So that I can receive relevant information and updates about studying at the University, including upcoming events like Open Day.
Acceptance Criteria (Gherkin Style)
Given the student is browsing a course page on the University website
And the EOI form is available on the page
When the student enters their name, email, and selects a course
And opts in to receive marketing communications
And clicks "Submit"
Then the system validates mandatory fields and checks for duplicates
And if valid, stores the data in Salesforce
And sends a confirmation email to the student
But if invalid, sends an error email and prompts the student to correct and resubmit


🔍 Priority (MoSCoW)

Must-Have: Capture name, email, course interest; validate fields; store lead in Salesforce; send confirmation email.
Should-Have: Mobile-friendly form; dropdown for course selection.
Could-Have: Multi-language support; progress indicator.
Won’t-Have: Chatbot integration (for now).


📝 Status
Draft (to be reviewed by stakeholders)
Estimate: Medium (depends on API integration complexity)
Notes:

Ensure compliance with privacy laws.
Risk: Incorrect API mapping could delay Salesforce integration.
Backup and recovery required for data integrity.

