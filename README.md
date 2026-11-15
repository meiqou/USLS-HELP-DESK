# USLS-HELP-DESK

A centralized support and ticketing system designed to streamline inquiries, technical support, and service requests for the University of St. La Salle (USLS) community.

# Table of Contents

About the Project

Key Features

Tech Stack

Getting Started

Prerequisites

Installation

Usage

Project Structure

Contributing

License

# About the Project

The USLS Help Desk provides students, faculty, and staff with an accessible platform to submit, track, and resolve campus-related issues and IT support tickets. By organizing requests into categorized workflows, the system helps support teams prioritize tasks, reduce response times, and maintain clear communication with users.

# Key Features

User Authentication & Role Management: Distinct portals and permissions for Students/Faculty (Requesters), Support Agents, and Administrators.

Ticket Submission & Categorization: Easy ticket creation with priority levels, department routing (e.g., IT Support, Registrar, Facilities), and file attachments.

Real-Time Status Tracking: Users can monitor ticket progress (Open, In Progress, Resolved, Closed) and receive updates.

Admin & Agent Dashboard: Centralized view for managing queues, assigning tickets, and viewing resolution metrics.

Knowledge Base / FAQs: Self-service articles to help users resolve common issues independently.

# Tech Stack

(Update this section to reflect the exact technologies used in your repository)

Frontend: HTML5, CSS3, JavaScript.

Backend: PHP / namespaced classes / PSR-4 autoloader (no external libraries)

Database: MySQL / MariaDB 

# Installation

Clone the repository:

git clone https://github.com/meiqou/USLS-HELP-DESK.git
cd USLS-HELP-DESK


# Usage

Requesters (Students/Staff): Log in with your university credentials, click "Create Ticket", fill out the issue details, and submit.

Support Staff: Access the agent dashboard to claim unassigned tickets, post replies, and update ticket statuses.

Administrators: Manage user roles, ticket categories, and system reports from the admin panel.

📂 Project Structure

USLS-HELP-DESK/
├── public/             # Publicly accessible assets
├── src/                # Main application source code
├── database/           # SQL schemas
├── .env.example        # Sample environment configuration
└── README.md           # Project documentation
