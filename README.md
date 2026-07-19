# 🏆 Sports Hall Booking System | ServiceNow Service Portal

## 📌 Project Overview

The **Sports Hall Booking System** is a comprehensive facility reservation solution built on the **ServiceNow Service Portal**. It digitizes the complete booking lifecycle—from venue selection and availability validation to payment processing, approval workflows, automated notifications, and refund management.

The system replaces traditional manual booking methods with a centralized, secure, and user-friendly platform that enables users to reserve sports facilities efficiently while providing administrators with complete visibility and control over facility utilization.

---

# 🎯 Project Objectives

* Digitize the sports hall reservation process.
* Eliminate manual booking conflicts and paperwork.
* Provide real-time venue availability.
* Automate booking approvals and confirmations.
* Improve user experience through a modern Service Portal.
* Support digital payment and refund processing.
* Optimize sports facility utilization.
* Enable centralized reporting and future scalability.

---

# 🚀 Key Features

### 🏟️ Venue Booking

* Browse available sports facilities.
* Select preferred venue, date, and time slot.
* View real-time availability.
* Book halls directly through the Service Portal.

### ✅ Intelligent Booking Validation

* Prevent overlapping reservations.
* Validate booking duration.
* Enforce configurable booking rules.
* Restrict invalid or duplicate bookings.

### 🔄 Approval Workflow

* Pending Approval
* Approved
* Rejected
* Cancelled

Optional manager approval ensures controlled facility access.

### 💳 Payment Management

* Online payment support
* Transaction tracking
* Payment history
* Booking fee calculation

### 💰 Refund Automation

When a booking is cancelled:

* Automatically calculates refund amount
* Deducts a **10% cancellation charge**
* Updates refund status
* Stores refund mode
* Records work notes for audit purposes

### 📧 Automated Notifications

The system automatically sends:

* Booking confirmation emails
* Payment confirmation
* Booking reminder emails before reservation time
* Cancellation notifications

Reminder emails are triggered automatically using scheduled jobs and Event Registry.

### 📊 Reporting Ready

The solution maintains centralized booking records that can later be used for:

* Booking analytics
* Facility utilization
* Peak hour analysis
* Operational reporting
* Administrative dashboards

---

# 🏗️ System Architecture

The application is centered around a custom ServiceNow table:

`u_sports_hall_bookings`

The table stores:

* Hall Information
* User Details
* Booking Schedule
* Booking Status
* Payment Information
* Refund Details
* Transaction Number
* Cancellation Reason
* Reminder Status

Business Rules, Scheduled Jobs, Events, Notifications, and Service Portal Widgets interact with this table to automate the entire booking lifecycle.

---

# ⚙️ Core Automation

## Business Rules

* Automatic refund calculation
* Cancellation charge processing
* Refund status updates
* Audit work notes generation

## Scheduled Jobs

* Detect upcoming bookings
* Trigger reminder events
* Prevent duplicate reminder emails

## Events & Notifications

* Booking Confirmation
* Booking Reminder
* Email Scripts
* Dynamic Email Templates

---

# 🌐 Service Portal Experience

The portal provides an intuitive self-service interface where users can:

* Explore sports venues
* Book facilities
* Make payments
* View booking history
* Cancel reservations
* Track booking status

The UI has been customized with:

* Responsive design
* Sports-themed branding
* Modern booking cards
* Customized navigation
* Improved user experience

---

# 🔄 Booking Workflow

```text
User Login
      │
      ▼
Browse Sports Venues
      │
      ▼
Select Date & Time
      │
      ▼
Availability Validation
      │
      ▼
Booking Submission
      │
      ▼
Payment Processing
      │
      ▼
Approval Workflow
      │
      ▼
Booking Confirmation
      │
      ▼
Reminder Notification
      │
      ▼
Booking Completion
      │
      ▼
(Optional)
Cancellation
      │
      ▼
Automatic Refund Processing
```

---

# 👥 Stakeholders

| Stakeholder             | Responsibility                              |
| ----------------------- | ------------------------------------------- |
| End Users               | Reserve sports facilities                   |
| Sports Hall Managers    | Approve bookings and manage availability    |
| Facility Administration | Monitor utilization and oversee maintenance |

---

# 📂 Project Modules

* Service Portal
* Custom Tables
* Widgets
* Business Rules
* Scheduled Jobs
* Events
* Notifications
* Email Scripts
* Approval Workflow
* Payment & Refund Logic
* Booking Validation
* UI Customization
* Navigation Configuration

---

# 🛠️ Technologies Used

* ServiceNow Service Portal
* ServiceNow Studio
* GlideRecord API
* Business Rules
* Scheduled Script Executions
* Event Registry
* Notifications
* Email Scripts
* Client Scripts
* UI Policies
* Service Portal Widgets
* HTML
* CSS
* JavaScript
* GlideDateTime

---

# 📈 Business Benefits

* Eliminates manual booking processes
* Prevents double bookings
* Reduces administrative workload
* Improves booking transparency
* Enhances user experience
* Automates notifications and reminders
* Simplifies payment and refund processing
* Increases operational efficiency
* Provides a scalable and maintainable booking solution

---

# 📋 Project Execution Roadmap

* Requirement Gathering
* Data Architecture Design
* Service Portal Development
* Booking Logic Implementation
* Approval Workflow Configuration
* Event & Notification Setup
* User Acceptance Testing (UAT)
* Production Deployment

---

# 🎯 Future Enhancements

* QR Code based booking verification
* Mobile responsive enhancements
* Calendar integration
* Microsoft Teams & Outlook notifications
* Dashboard and KPI reporting
* AI-based venue recommendations
* Waitlist management
* Multi-location sports facility support
* Online payment gateway integration
* Role-based analytics dashboard

---

# ⭐ Conclusion

The **Sports Hall Booking System** demonstrates how the **ServiceNow Service Portal** can be leveraged to build a complete enterprise-grade reservation platform. By integrating booking validation, approval workflows, payment management, automated reminders, refund processing, and a responsive self-service portal, the solution delivers a streamlined digital experience for users while significantly improving operational efficiency for sports facility administrators.

This project showcases practical implementation of ServiceNow platform capabilities, automation, and portal customization, making it an excellent reference for learning enterprise application development using ServiceNow.
