# Software Requirements Specification (SRS) for SmartEnroll

## 1. Purpose Statement

SmartEnroll is a smart academic planning and registration system for the University of South Florida (USF). It aims to combine course registration and degree planning into a single platform to reduce scheduling conflicts and improve real-time prerequisite tracking. By checking prerequisite requirements, schedule conflict detection, and real-time degree progress updates, SmartEnroll can help students graduate on time which will also reduce the advising workload.

## 2. Overview

SmartEnroll will provide a solution that is accessible to students, advisors, and faculty. The system will include real-time prerequisite tracking, schedule conflict alerts, degree progress monitoring, and automated registration reminders. It will connect with the existing USF systems, such as OASIS and DegreeWorks, to ensure accurate student academic planning.

## 3. Product Perspective

SmartEnroll is a new system designed as an extension of USF’s existing academic tools. It will serve as a platform that consolidates degree planning and course registration functionalities, improving the user experience and efficiency of academic planning processes.

## 4. Functional Requirements

- Real-time degree progress tracking.

- Automated prerequisite verification before course registration.

- Schedule conflict detection and alerts.

- Automated registration deadline reminders.

- Advisor-student collaboration tools within the platform.

- Role-based access for students, advisors, and administrators.

## 5. Non-Functional Requirements

- High availability and reliability to support peak registration periods.

- User-friendly interface with modern UI/UX standards.

- Secure authentication and data privacy compliance.

- Fast response times for data queries and updates.

- Accessibility features for diverse student populations.

## 6. Constraints

- Operational: Must run on existing USF servers and databases.

- Technical: Integration with DegreeWorks and OASIS.

- Economic: Limited funding for full-scale deployment.

- Schedule: Project must be completed within one semester.

- Legal: Compliance with USF data privacy policies.

- Cultural: Designed for users with varying levels of technical proficiency.

## 7. Standards

- Development using Ruby on Rails.

- Coding and quality standards set by MicroBase, Inc.

- UI/UX design based on modern web design principles.

## 8. Assumptions

- USF IT Department will provide API access to DegreeWorks and OASIS.

- Users (students and advisors) will have internet access and basic computing skills.

- The system will primarily be accessed via web browsers.

## 9. Defined Terms

- OASIS: USF’s current online course registration system.

- DegreeWorks: USF’s academic planning tool.

- Prerequisite Validation: Automatic checking of course prerequisites before registration.

- Schedule Conflict Detection: System alerts if selected courses overlap.

- Automated Registration Reminders: Notifications sent to students regarding deadlines.

## 10. End-User Characteristics

- Students: Undergraduate and graduate students with basic technical proficiency.

- Advisors & Faculty: Academic advisors assisting students with course planning.

- USF IT Staff: Responsible for system integration and maintenance.

## 11. References

- USF DegreeWorks Documentation

- USF OASIS User Guide

- USF Data Privacy Policy

- MicroBase, Inc. Coding Standards
