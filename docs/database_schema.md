EstateX Database Schema (Version 1)
Companies
Stores builder information.

Fields:

Company ID

Company Name

Industry

GST Number

Address

City

State

Country

Timezone

Created At

Users
Stores users.

Fields:

User ID

Company ID

Full Name

Email

Mobile

Role

Status

Last Login

Projects
Stores project details.

Fields:

Project ID

Company ID

Project Name

Project Type

City

Location

Starting Price

Maximum Price

Status

Launch Date

Campaigns
Stores marketing campaigns.

Fields:

Campaign ID

Project ID

Platform

Campaign Name

Budget

Spend

Leads Generated

CPL

Status

Leads
Stores customer information.

Fields:

Lead ID

Project ID

Campaign ID

Name

Mobile

Email

Budget

Source

Status

Lead Score

Booking Probability

Assigned AI

Created At

Activities
Stores every action.

Fields:

Activity ID

Lead ID

Activity Type

Description

Performed By

Date Time

Site Visits
Stores visits.

Fields:

Visit ID

Lead ID

Project ID

Visit Date

Visit Status

Feedback

Bookings
Stores bookings.

Fields:

Booking ID

Lead ID

Unit Number

Booking Amount

Booking Date

Status

Tasks
Stores reminders.

Fields:

Task ID

Lead ID

Assigned To

Due Date

Status

AI Conversations
Stores every AI interaction.

Fields:

Conversation ID

Lead ID

AI Employee

Conversation Type

Summary

Sentiment

Next Action
