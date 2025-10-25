# Requirement Analysis in Software Development
This repository serves as a centralized resource for understanding, documenting, and managing the process of **Requirement Analysis** within the software development lifecycle. 
The primary goal is to provide practical examples, templates, and guides for eliciting, analyzing, specifying, and validating software requirements to ensure the final product meets stakeholder needs and project objectives.
## What is Requirement Analysis?
## ما هو تحليل المتطلبات؟

Requirement Analysis (RA) is a crucial and foundational stage in the Software Development Lifecycle (SDLC). It is the process of defining, documenting, and managing the needs and expectations of stakeholders—including users, customers, and business sponsors—for a new or modified software product.

It acts as a bridge between the high-level business goals and the technical implementation details.

### Importance in the SDLC
### أهميته في دورة حياة تطوير البرمجيات (SDLC)

Requirement Analysis is considered the bedrock of a successful project, and its importance stems from the following:

1.  **Cost Reduction (تقليل التكلفة):** Identifying errors or misunderstandings in requirements early is significantly less expensive than fixing them after development or deployment.
2.  **Scope Management (إدارة النطاق):** Clearly defined requirements prevent "Scope Creep" (زحف النطاق)، which is the uncontrolled growth of a project's features and goals.
3.  **Foundation for Design and Testing (الأساس للتصميم والاختبار):** Requirements serve as the blueprint for the design phase and the criteria (test cases) against which the final software is validated.
4.  **Stakeholder Alignment (مواءمة أصحاب المصلحة):** The process ensures that all parties (business, development, and users) have a shared, unambiguous understanding of what the system is supposed to do.
## Why is Requirement Analysis Important?
## لماذا يعتبر تحليل المتطلبات مهما؟

Requirement Analysis is not just a preliminary step; it is the foundation that determines the success or failure of a software project. Its importance can be summarized in these critical areas:

### 1. Risk Mitigation and Cost Control (تخفيف المخاطر والتحكم في التكلفة)
* **Description:** The cost of fixing an error increases exponentially as the project progresses. By rigorously analyzing requirements early on, potential misunderstandings, feasibility issues, and missing features are identified and resolved when they are cheapest to correct, drastically reducing the overall project risk and rework.

### 2. Ensuring Stakeholder Satisfaction and Project Success (ضمان رضا أصحاب المصلحة ونجاح المشروع)
* **Description:** A clear and agreed-upon set of requirements ensures that the final product directly addresses the actual business problem and user needs. This shared understanding prevents building the wrong product ("building the product right vs. building the right product"), which is the primary cause of project failure and user dissatisfaction.

### 3. Clear Basis for Planning and Validation (أساس واضح للتخطيط والتحقق)
* **Description:** Requirements provide the essential criteria for every subsequent phase:
    * **Planning:** They allow project managers to accurately estimate resources, timelines, and budgets.
    * **Design:** They act as the blueprint for architects and developers.
    * **Testing:** They form the test cases and acceptance criteria used to validate that the delivered software works as intended.
## Key Activities in Requirement Analysis
## الأنشطة الرئيسية في تحليل المتطلبات

Requirement Analysis is an iterative process involving several distinct and critical activities. These five core activities ensure that the requirements are complete, correct, and understood by all stakeholders:

### 1. Requirement Gathering (جمع المتطلبات)
* **Description:** This initial phase involves collecting all raw information from various sources related to the system's needs, scope, and objectives. This often includes existing system documents, market research, and business strategy papers.

### 2. Requirement Elicitation (استنباط المتطلبات)
* **Description:** This is the active process of discovering and extracting requirements directly from stakeholders. Key techniques used here include interviews, brainstorming sessions, workshops (JAD), questionnaires, and observation of users. The goal is to articulate what the users and the business truly need.

### 3. Requirement Analysis and Modeling (تحليل المتطلبات والنمذجة)
* **Description:** The collected (elicited) requirements are examined for conflicts, ambiguities, incompleteness, and feasibility. Analysis techniques involve classifying requirements, prioritizing them, and translating them into models (e.g., Use Case diagrams, Data Flow Diagrams, Activity Diagrams) to visualize the system's structure and behavior.

### 4. Requirement Documentation (وثائق المتطلبات)
* **Description:** The analyzed and refined requirements are formally recorded in a structured document, typically the Software Requirements Specification (SRS) document. This document acts as the official contract between the stakeholders and the development team, detailing both functional and non-functional requirements.

### 5. Requirement Validation (التحقق من صحة المتطلبات)
[**Image:** alx-booking-uc.png]
* **Description:** This final check ensures that the documented requirements are correct, complete, consistent, and traceable back to the business objectives. Validation techniques include formal reviews, walkthroughs, prototyping, and creating test cases based on the requirements to confirm they meet stakeholder expectations before development begins.
## Types of Requirements
## أنواع المتطلبات

Software requirements are primarily categorized into two distinct types: Functional Requirements (what the system *must do*) and Non-functional Requirements (how well the system *must perform*).

### 1. Functional Requirements (FR)
### 1. المتطلبات الوظيفية (FR)

**Definition:** These define the specific functions, features, or behaviors that the system must exhibit to satisfy user needs and business objectives. They describe what the system does.

**Examples for a Booking Management Project:**

* **User Authentication:** The system MUST allow users to log in and log out securely using a username and password.
* **Booking Creation:** The system MUST allow a user to select a date, time, and service type, and create a new reservation.
* **Booking Modification:** The system MUST allow a user to view, reschedule, or cancel an existing reservation, subject to business rules.
* **Payment Processing:** The system MUST integrate with a payment gateway to process credit card payments for booked services.
* **Notification:** The system MUST send an email confirmation to the user immediately after a booking is successfully created.

***

### 2. Non-functional Requirements (NFR)
### 2. المتطلبات غير الوظيفية (NFR)

**Definition:** These define the quality attributes, constraints, and criteria for system operation. They describe *how* the system performs its functions (e.g., speed, security, usability).

**Examples for a Booking Management Project:**

* **Performance (الأداء):** The system MUST load any booking-related page in less than 3 seconds, even during peak usage times.
* **Security (الأمان):** All user passwords MUST be stored in the database using industry-standard hashing and encryption techniques.
* **Availability (التوفر):** The booking service MUST be available 99.9% of the time (excluding scheduled maintenance).
* **Usability (سهولة الاستخدام):** The booking interface MUST be intuitive, allowing a new user to complete a reservation in three steps or less.
* **Scalability (قابلية التوسع):** The system MUST be able to support up to 10,000 concurrent active user sessions without performance degradation.
## 5. Use Case Diagrams
## 5. مخططات حالة الاستخدام
## Acceptance Criteria

Acceptance Criteria are the specific conditions that a product or feature must meet to be accepted by the client or end user.  
They serve as a clear agreement between the development team and stakeholders, ensuring everyone understands what “done” means.  
Well-defined acceptance criteria help reduce misunderstandings, guide testing, and improve overall software quality.

### Importance of Acceptance Criteria
- They define clear expectations for each feature.
- They provide measurable outcomes for testing.
- They help ensure the final product meets user needs.
- They make communication between developers, testers, and clients easier.
![alx-booking-uc](alx-booking-uc.png)

### Example: Checkout Feature in a Booking Management System

**Feature:** Checkout Process

**Acceptance Criteria:**
1. The system must allow the user to review all selected bookings before final payment.  
2. The checkout page must display the total price, including taxes and fees.  
3. The user must be able to choose a payment method (credit card, PayPal, or mobile money).  
4. The system must confirm successful payment and display a “Booking Confirmed” message.  
5. If payment fails, the system must show an error message and allow the user to retry.

---

These criteria ensure that the checkout feature works as intended, is user-friendly, and meets all business requirements.

### مخطط حالة الاستخدام لنظام إدارة الحجز

The following diagram illustrates the primary actors and their interactions with the Booking Management System:

| Actor (الممثل) | Description (الوصف) |
| :--- | :--- |
| **Customer/User** (العميل/المستخدم) | An external user who interacts with the system to book, manage, or cancel services. |
| **System Administrator** (مسؤول النظام) | An internal user responsible for system setup, maintenance, and managing user accounts. |
| **Payment Gateway** (بوابة الدفع) | An external system that processes payments. |
![alx-booking-uc](alx-booking-uc.png)


---
## 6. Acceptance Criteria
## 6. معايير القبول

Acceptance Criteria (AC) are a set of conditions that a software feature must satisfy to be accepted by the users, customers, or product owner. They are formal checkpoints used during testing (specifically Acceptance Testing) to confirm that the feature performs its intended function and meets all quality standards.

**Importance in Requirement Analysis:**
* **Clarity and Consensus:** They bridge the gap between business requirements and technical implementation, ensuring everyone agrees on what "done" means.
* **Testable Definition:** They make requirements measurable and testable, eliminating ambiguity.
* **Go/No-Go Decision:** They provide the clear basis for the Product Owner to approve or reject a feature delivery.

### Acceptance Criteria Example: The Checkout Feature
### مثال على معايير القبول: ميزة "إنهاء عملية الشراء/الخروج"

| ID | Criteria |
| :--- | :--- |
| **AC-C1** | The system MUST successfully process payment via credit card (Visa/MasterCard). |
| **AC-C2** | If the payment is successful, the user MUST be redirected to a confirmation page displaying the booking details and a confirmation number. |
| **AC-C3** | If the payment fails (e.g., card declined), the system MUST display a clear error message and allow the user to re-enter payment details without losing booking information. |
| **AC-C4** | The system MUST send an automatic confirmation email to the user within 60 seconds of a successful transaction. |
| **AC-C5** | The system MUST update the inventory/calendar availability immediately upon successful payment to prevent double-booking. |
## Example Wireframe

![Wireframe Example](./wireframe.png)
