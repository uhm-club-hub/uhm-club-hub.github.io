---
title: Final Project - Club Hub
---

## Overview
Club Hub is a centralized directory application designed to connect students at the University of Hawaiʻi at Mānoa with campus organizations, clubs, and extracurricular activities.

## Project Links
* **[GitHub Organization & Repositories](https://github.com/uhm-club-hub)** 
* **[Team Contract]【需要你替换为你们团队契约的链接】** 

## Deployment
Our application is actively being developed and is deployed via Vercel.
* **[View Club Hub Live on Vercel](https://club-hub-nu.vercel.app)**

## Project Management
We use Issue Driven Project Management (IDPM) to track our progress.
* **[Milestone 1 (M1) Project Board]【需要你替换为M1看板链接】**: Displays the issues completed for this milestone. (Note: All M1 issues have estimates/actuals, and nothing remains in Backlog or In Progress).
* **[Milestone 2 (M2) Project Board]【需要你替换为M2看板链接】**: Outlines the issues and goals we plan to address in the next phase of development.

---

## The Problem
Currently, discovering and joining student organizations at UHM can be a frustrating and fragmented experience. Information is often scattered across outdated university web pages, various social media platforms, or physical flyers on campus bulletin boards. For new or transfer students, this lack of a centralized, easily searchable database makes it difficult to find communities that align with their specific academic, cultural, or personal interests. Furthermore, club administrators struggle to maintain visibility and keep their contact information updated for prospective members.

## The Solution
Club Hub solves this by providing a unified, interactive directory tailored specifically for the UHM community. The application will allow students to filter and search for registered organizations based on predefined interest tags (e.g., "Engineering", "Arts", "Outdoors", "Professional").

### Key Features
*   **Role-Based Access:** Distinct roles for regular students, club administrators, and system admins.
*   **Tag-Based Filtering:** A robust search system allowing users to find clubs matching their personal profiles.
*   **Profile Management:** Club administrators can easily log in to update their organization’s description, meeting times, and contact information, ensuring the directory remains current without relying on a central webmaster.

---

## Current State & Screenshots
*(Note: As part of Milestone 1, the following screenshots reflect the current state of our deployed application.)*

### Landing Page
A clean, welcoming entry point explaining the purpose of Club Hub with a prompt to log in via a UHM account. 
<!-- 请确保放入实际网页的截图，M1要求有Landing page并且包含登录入口 -->
![Landing Page]【需要你替换为实际图片路径，例如 (./images/landing.png)】

### Directory / Search Page
The core feature page displaying a grid of club cards. Includes a sidebar with dropdown menus to filter by categories.
![Directory Page]【需要你替换为实际图片路径，例如 (./images/directory.png)】

### User Profile Page
A dashboard where students can set their personal interest tags and see a list of bookmarked or recommended clubs.
![User Profile]【需要你替换为实际图片路径，例如 (./images/profile.png)】

### Club Admin Dashboard
A form-based page where designated club officers can edit their club’s public profile and update announcements.
![Admin Dashboard]【需要你替换为实际图片路径，例如 (./images/admin.png)】

### System Admin Page (or other 4th page)
A dashboard for site admins to review newly registered clubs, approve them for public display, and manage entries.
![System Admin]【需要你替换为实际图片路径，例如 (./images/sys-admin.png)】

---

## Use Cases
*   **New Student Discovery:** A freshman logs in, sets their interests to "Software Engineering" and "Hiking," and the system instantly filters the directory to show relevant organizations.
*   **Club Officer Update:** A club president logs in, navigates to their organization’s page, and updates the meeting location for the upcoming semester. The changes are immediately reflected in the public directory.
*   **System Administration:** A site admin logs in to review newly registered clubs, approve them for public display, and remove any obsolete or duplicate entries.

## Technical Stack
Building upon modern web development standards, the project utilizes:
*   **Frontend:** React and Next.js for a responsive, component-based user interface.
*   **Styling:** Bootstrap 5 for rapid UI prototyping and consistent mobile-friendly layout.
*   **Backend/Database:** PostgreSQL to securely manage user profiles, club data, and the relational mapping of interest tags.
*   **Language:** Strict TypeScript to ensure type safety and minimize runtime errors throughout the application.
