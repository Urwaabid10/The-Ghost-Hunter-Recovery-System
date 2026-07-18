# Ghost Hunter No-Show Recovery System (CrossFit Gym)

## Demo

A short walkthrough of the system is available below:

 [Click here to watch the demo](https://drive.google.com/file/d/1nib1AA8Q4xG2knr4FlEHXnUtMTdABbLV/view?usp=drive_link)

## Overview

Missed appointments are a major source of lost revenue for fitness businesses. CrossFit gyms offering free trials often experience high no-show rates, with a significant portion of booked prospects never attending their scheduled sessions.

This project introduces an automated no-show recovery system designed to re-engage missed leads, encourage re-bookings, and ensure no opportunity is lost without follow-up.

---

## Problem Statement

* High no-show rate for free trial bookings
* No structured follow-up system for missed appointments
* Loss of potential members and revenue
* Manual follow-ups are inconsistent or delayed

---

## Solution

An automated recovery loop that:

* Tracks appointment attendance status
* Triggers follow-up workflows for no-shows
* Encourages re-booking through automated messaging
* Escalates unresponsive leads for manual intervention

---

## Key Features

### Calendar with Reminder System

* Integrated booking calendar for free trial sessions
* Automated confirmation and reminder messages
* Reduces initial no-show rate

---

### No-Show Trigger Workflow

* Secondary workflow activated when appointment status is marked as "No-Show"
* Ensures immediate follow-up action

---

### Automated Recovery Messaging

* Sends SMS with a re-booking link
* Encourages leads to reschedule quickly
* Designed to create urgency and engagement

---

### Conditional Logic (If/Else)

* Tracks whether the lead clicks the re-book link
* If action is taken:

  * Lead re-enters booking flow
* If no action:

  * Moves to escalation stage

---

### Escalation System

* If no response within 48 hours:

  * Creates an internal task for front desk follow-up
  * Moves lead to "High Priority Rescue" pipeline stage

---

## Workflow Summary

1. Lead books a free trial via calendar
2. System sends confirmation and reminder messages
3. If lead does not attend:

   * Appointment marked as "No-Show"
4. Recovery workflow is triggered
5. SMS with re-book link is sent
6. System monitors engagement:

   * If clicked: lead re-books
   * If ignored for 48 hours:

     * Internal task is created
     * Lead moved to "High Priority Rescue" stage
7. Front desk follows up manually

---

## Tech Stack

* CRM Platform: GoHighLevel (GHL)
* Automation: Workflow triggers and conditional logic
* Communication: SMS automation
* Scheduling: Calendar integration

---

## Business Impact

* Recovers lost revenue from missed appointments
* Increases re-booking rates
* Reduces manual follow-up workload
* Improves overall lead conversion

---

## Use Cases

* CrossFit gyms
* Fitness centers
* Personal training studios
* Any appointment-based business

---

## Future Enhancements

* Multi-step follow-up sequences (SMS + Email)
* Incentive-based rebooking (discounts or offers)
* AI-based engagement scoring
* Automated reporting and analytics dashboard

---

## Author
Urwa
AI Automation Developer and CRM Specialist

---


