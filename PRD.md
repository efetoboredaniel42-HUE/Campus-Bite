# Product Requirements Document (PRD)

# CampusBite — Campus Food Ordering and Queue Management System

**Course:** BU-209 Backend Engineering  
**Assignment:** Week 4 — Product Requirements Document  
**Version:** 1.0 (Draft for team validation)  
**Research status:** Field research still needs to be completed and recorded by the team.

## 1. Product Overview

CampusBite is a proposed digital food-ordering and queue-management platform for university students and campus food vendors. It is intended to let students view participating vendors and their menus, submit orders and check order progress, while vendors manage incoming orders and update their status. The initial version focuses on ordering for collection rather than delivery.

## 2. Problem Statement

Students may have limited time between lectures and other activities to purchase food. At busy times, physically ordering and waiting for meals may take longer than students can comfortably afford. Vendors may also have difficulty organizing multiple orders and communicating their progress, particularly during peak periods.

These are initial problem hypotheses. The team must validate their frequency, severity and impact through interviews, surveys and direct observation on the selected campus before treating them as established findings.

## 3. Background and Context

Food demand on campuses can concentrate around breaks, lunch periods and the end of lectures. A traditional process may require a customer to visit a vendor, place an order, wait for preparation and collect the meal. Customers may have limited information about the orders ahead of them or the vendor's current workload. CampusBite proposes testing a digital process to address these potential friction points.

## 4. Research Objectives

The research will:
- Identify the difficulties students face when purchasing food on campus.
- Understand how often and when waiting occurs.
- Document the current ordering process at selected vendors.
- Understand how vendors manage orders and busy periods.
- Explore student and vendor willingness to use a digital ordering system.
- Identify the most useful features and barriers to adoption.
- Inform the MVP scope and requirements.

## 5. Research Methodology

### 5.1 Methods

The team proposes short semi-structured interviews with students and vendors, a brief student survey and direct observation of queues at selected food vendors during busy and less-busy periods. The team should record dates, locations, participant counts and anonymized responses.

### 5.2 Proposed Participants

- 10–15 students who purchase food on campus.
- 2–3 campus food vendors.
- Observations at one or more vendor locations during different periods.

These are proposed sample sizes, not completed research.

### 5.3 Student Interview Questions

1. How often do you buy food on campus?
2. Where do you usually buy food?
3. How long do you typically wait at busy times?
4. Have you ever left a queue without buying food because of the wait?
5. Have you ever been late for an activity because of food-purchasing delays?
6. What do you currently do when a vendor is too busy?
7. Would you consider placing an order ahead of time and collecting it?
8. What would make you trust or avoid such a service?

### 5.4 Vendor Interview Questions

1. When are your busiest periods?
2. How do you currently receive and organize orders?
3. What difficulties arise when many customers arrive at once?
4. Do customers ask about or complain about waiting times?
5. Would digital orders help or complicate your workflow?
6. What features would be necessary for you to use a digital ordering platform?
7. What concerns would you have about digital orders?

### 5.5 Observation Template

Record the observation date and time, vendor/location, approximate number of people waiting, time taken to place an order, estimated preparation/collection time, observed issues and any relevant context. Do not present estimates as precise measurements.

## 6. Research Findings and Evidence

**Status: To be completed with the team's actual field evidence.**

Record findings here after conducting interviews, surveys and observations. Include the number and type of participants, key themes, anonymized quotations where consented, observations and any survey results. Distinguish participant reports from the team's observations. Do not invent results.

Suggested synthesis:
- Student pain points and how frequently they were reported.
- Vendor pain points and workflow constraints.
- Current workarounds.
- Features participants prioritized.
- Concerns, barriers and contradictory feedback.
- Evidence that supports, weakens or changes the initial problem hypothesis.

## 7. Target Users

### 7.1 Students (Primary)

Students who purchase meals from participating campus vendors and may have limited time. Their potential needs include browsing menus, ordering, receiving confirmation and knowing when food is ready.

### 7.2 Vendors (Secondary)

Food vendors who prepare meals and handle customer orders. Their potential needs include viewing incoming orders, accepting or rejecting orders, updating statuses and managing item availability.

### 7.3 Administrator

A platform administrator responsible for basic account and vendor management, responding to reports and overseeing platform operations.

## 8. User Personas (Hypotheses to Validate)

### Persona A: Time-Constrained Student

- **Goal:** Purchase food while minimizing time spent in a queue.
- **Potential pain points:** Limited breaks, uncertain waits and crowded vendors.
- **Potential benefit:** Submit an order ahead of collection and check progress.

### Persona B: Campus Food Vendor

- **Goal:** Prepare and serve orders while managing demand.
- **Potential pain points:** Many simultaneous customers, order confusion and workload.
- **Potential benefit:** A simple order dashboard and consistent status updates.

### Persona C: Administrator

- **Goal:** Maintain basic platform operations and participating vendor accounts.
- **Potential pain points:** Account issues, reports and oversight.
- **Potential benefit:** Centralized account and vendor management.

## 9. Existing Alternatives and Potential Limitations

### 9.1 Physical Queues

Customers order and wait in person. Potential limitations to investigate include congestion, time spent waiting and limited visibility into workload or order progress.

### 9.2 Phone Calls and Messaging

Customers may contact vendors directly. Potential limitations to investigate include missed messages, unclear order records and inconsistent status communication.

### 9.3 General Delivery Services

Some customers may use general food-delivery services. Potential campus-specific limitations to investigate include fees, vendor coverage, delivery logistics and whether delivery is necessary for customers already on campus.

These are hypotheses and must be verified locally; this section does not claim that all existing services have these limitations.

## 10. Proposed Solution

CampusBite would connect students with participating campus vendors through a lightweight digital ordering platform. Students would browse vendors and menus, select items, submit orders and view status updates. Vendors would manage orders through a dashboard, accept or reject orders, mark orders as preparing and ready, and complete orders upon collection. The pilot would focus on pickup.

## 11. Goals and Non-Goals

### 11.1 Goals

- Make it possible to place an order without first standing in line to order.
- Improve order organization for participating vendors.
- Provide clear order status information.
- Maintain a record of orders and their statuses.
- Test whether students and vendors find the service useful.

### 11.2 Non-Goals for the MVP

- Campus-wide delivery or courier management.
- GPS tracking.
- Multi-campus support.
- Loyalty programs or complex promotions.
- AI-based recommendations.
- Advanced analytics.
- Integrations with third-party delivery services.

## 12. Minimum Viable Product (MVP)

The MVP will test the core ordering and order-management flow with a small number of participating vendors.

### 12.1 Student Capabilities

- Register and log in.
- Browse participating vendors.
- View menus, prices and item availability.
- Add items to a cart and adjust quantities.
- Submit an order.
- View order status.
- Review past orders.

### 12.2 Vendor Capabilities

- Log in to a vendor account.
- View incoming orders.
- Accept or reject orders.
- Update an order's status.
- Mark an order ready for collection and completed.
- Add, edit or remove menu items.
- Mark menu items unavailable.

### 12.3 Administrator Capabilities

- View and manage accounts.
- Review and approve participating vendors.
- Disable accounts when necessary.
- Review basic platform activity and reported issues.

### 12.4 Order Statuses

- Pending
- Accepted
- Rejected
- Preparing
- Ready for collection
- Completed
- Cancelled

## 13. Functional Requirements

- **FR-01 Registration:** The system shall allow students to register accounts using required information.
- **FR-02 Authentication:** The system shall allow registered users to log in and log out.
- **FR-03 Vendor discovery:** The system shall display participating vendors.
- **FR-04 Menus:** The system shall display vendors' menu items, prices and availability.
- **FR-05 Cart:** The system shall allow users to select items and quantities before submission.
- **FR-06 Order submission:** The system shall allow authenticated students to submit orders to a vendor.
- **FR-07 Order decision:** The system shall allow vendors to accept or reject incoming orders.
- **FR-08 Status updates:** The system shall allow vendors to update order statuses.
- **FR-09 Order tracking:** The system shall allow students to view the current status of their own orders.
- **FR-10 Menu management:** Authorized vendors shall be able to add, edit and remove menu items.
- **FR-11 Availability:** Vendors shall be able to mark items available or unavailable.
- **FR-12 Order history:** Students shall be able to view their previous orders.
- **FR-13 Vendor administration:** Administrators shall be able to manage vendor accounts and approvals.
- **FR-14 Completion:** Vendors shall be able to mark an order completed after collection.
- **FR-15 Cancellation:** The system shall support cancellation according to rules defined before implementation.

## 14. Non-Functional Requirements

- **Performance:** Common actions should respond within a reasonable time under normal conditions; measurable targets will be set and tested during implementation.
- **Security:** Protect credentials, restrict access by role, validate input and prevent unauthorized access to or modification of orders.
- **Reliability:** Persist submitted orders and avoid accidental loss or duplication.
- **Usability:** Provide a clear, straightforward interface for students and vendors.
- **Scalability:** Allow the platform to accommodate additional vendors and users as usage grows.
- **Maintainability:** Structure the system so that future changes can be implemented and tested.
- **Data integrity:** Maintain consistent order details, quantities, prices and statuses.

## 15. User Stories

- **US-01:** As a student, I want to create an account so that I can use the platform.
- **US-02:** As a student, I want to browse vendors so that I can choose where to order.
- **US-03:** As a student, I want to view menus and prices so that I can decide what to buy.
- **US-04:** As a student, I want to submit an order digitally so that I can order without first standing in line.
- **US-05:** As a student, I want to view my order status so that I know when my food is ready.
- **US-06:** As a student, I want to review previous orders so that I can see my order history.
- **US-07:** As a vendor, I want to see incoming orders so that I can organize preparation.
- **US-08:** As a vendor, I want to accept or reject orders so that I can manage my capacity.
- **US-09:** As a vendor, I want to update statuses so that students know the progress of their orders.
- **US-10:** As a vendor, I want to manage menu items so that the menu reflects what is available.
- **US-11:** As an administrator, I want to approve vendors so that participating vendors can be reviewed.
- **US-12:** As an administrator, I want to manage accounts so that I can maintain the platform.

## 16. User Flows

### Student Flow

1. Open the platform and log in.
2. Browse vendors and select one.
3. View menu and item availability.
4. Select items and quantities.
5. Review cart and submit order.
6. Wait for vendor acceptance and status updates.
7. View ready-for-collection status.
8. Collect the order.
9. Vendor marks the order completed.

### Vendor Flow

1. Log in.
2. View incoming orders.
3. Accept or reject an order.
4. Prepare accepted order.
5. Update status to preparing and then ready.
6. Complete the order after collection.

## 17. Scope

### In Scope

Registration and authentication; vendor browsing; menus and availability; cart; order submission; order management; order status tracking; vendor menu management; basic administration; order history.

### Out of Scope

Delivery; GPS tracking; multiple campuses; advanced payment integrations; AI recommendations; loyalty schemes; advanced analytics; third-party restaurant integrations.

## 18. Risks and Constraints

- **Vendor adoption:** Vendors may not want to change their workflow. Mitigation: keep the workflow simple and validate willingness through interviews.
- **Connectivity:** Users may experience unstable internet. Mitigation: keep the initial experience lightweight and avoid unnecessary requests.
- **Order accuracy:** Errors may occur in item selection or quantities. Mitigation: provide a clear order summary before submission.
- **Vendor capacity:** Vendors may be overwhelmed by incoming orders. Mitigation: allow rejection and item availability updates.
- **User adoption:** Students may prefer the current process. Mitigation: test the MVP and use feedback to adjust.
- **Cancellation:** Late cancellations may waste vendor effort. Mitigation: define and communicate cancellation rules.
- **Operational burden:** Digital ordering may add work for vendors. Mitigation: test the vendor workflow and minimize steps.

## 19. Success Metrics

Measure during a pilot:
- Registered students and participating vendors.
- Active users.
- Orders submitted, accepted, rejected, cancelled and completed.
- Time from submission to vendor acceptance.
- Time from acceptance to ready status.
- Comparable observed waiting times before and during the pilot, if measured consistently.
- Student and vendor satisfaction feedback.
- Failed submissions, duplicate orders and order-related issues.

Targets should be set after baseline research and pilot testing rather than invented in advance.

## 20. Future Improvements

Potential future features include online payment, notifications, estimated preparation times, scheduled ordering, vendor analytics, customer reviews, promotions and delivery. These should be prioritized based on pilot evidence and user feedback.

## 21. Preliminary Technical Considerations

Without choosing a programming language or framework, the product will need to manage user accounts, vendor details, menu items, orders, order statuses, authentication, role-based authorization, input validation and access to the system. The technical design and technology choices should be made after validating the problem and requirements.

## 22. Conclusion

CampusBite proposes a digital ordering and queue-management process for campus food vendors. It aims to give students a way to browse menus, submit orders and track progress, while giving vendors a structured way to manage incoming orders. The team must first validate the problem with actual campus research and then test the MVP with a small group of students and vendors. The project should be judged by evidence of usability, adoption and measurable improvements in the ordering process.
