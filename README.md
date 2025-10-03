
Disaster Alleviation Foundation - Web Application
https://img.shields.io/badge/Azure-DevOps-blue
https://img.shields.io/badge/.NET-8.0-purple
https://img.shields.io/badge/ASP.NET-Core-green
https://img.shields.io/badge/Database-SQL%2520Server-red

A comprehensive web application for disaster management and relief coordination, built with ASP.NET Core 8.0 and Azure cloud services.

🌟 Overview
The Disaster Alleviation Foundation platform enables efficient coordination of disaster relief efforts through:

Incident Reporting - Real-time disaster incident reporting and tracking

Resource Management - Donation collection and distribution tracking

Volunteer Coordination - Volunteer registration and task management

User Authentication - Secure role-based access control

🚀 Features
Core Functionality
User Registration & Authentication - Secure signup/login with role-based permissions

Incident Management - Report, track, and manage disaster incidents

Donation System - Accept and manage various types of donations (food, clothing, medical supplies, financial)

Volunteer Portal - Volunteer registration, task assignment, and scheduling

Admin Dashboard - Comprehensive management interface

Technical Features
Responsive Design - Mobile-first, professional UI/UX

Real-time Updates - Live incident and donation tracking

Secure Authentication - ASP.NET Core Identity with Azure AD integration

Database Management - Entity Framework Core with SQL Server

Cloud Ready - Full Azure DevOps pipeline integration

🛠 Technology Stack
Backend
ASP.NET Core 8.0 - Web framework

Entity Framework Core - ORM and data access

ASP.NET Core Identity - Authentication and authorization

SQL Server - Database management

Frontend
Bootstrap 5.3 - Responsive UI framework

Font Awesome - Icons and visual elements

JavaScript/jQuery - Client-side interactivity

Razor Pages - Server-side rendering

DevOps & Cloud
Azure DevOps - CI/CD pipelines

Azure App Service - Hosting platform

Azure SQL Database - Cloud database

Azure Key Vault - Secrets management

Application Insights - Monitoring and analytics

📋 Prerequisites
Before running this application, ensure you have:

.NET 8.0 SDK

Visual Studio 2022 or VS Code

SQL Server (LocalDB or Express)

Azure CLI (for deployment)

Git

🏗 Project Structure
text
DisasterAlleviationFoundation/
├── DisasterAlleviationFoundation.Web/
│   ├── Controllers/          # MVC Controllers
│   ├── Models/              # Data Models and ViewModels
│   ├── Views/               # Razor Views
│   ├── Services/            # Business Logic Services
│   ├── Data/                # Database Context and Migrations
│   ├── wwwroot/             # Static Files
│   └── Program.cs           # Application Entry Point
├── DisasterAlleviationFoundation.Core/
│   ├── Models/              # Core Domain Models
│   ├── Services/            # Core Business Services
│   └── Interfaces/          # Service Contracts
├── DisasterAlleviationFoundation.Tests/
│   ├── UnitTests/           # Unit Test Projects
│   └── IntegrationTests/    # Integration Tests
├── azure-pipelines.yml      # CI/CD Pipeline
└── README.md               # Project Documentation
🚀 Quick Start
Local Development Setup
Clone the Repository

bash
git clone https://dev.azure.com/your-organization/DisasterAlleviationFoundation/_git/DisasterAlleviationFoundation
cd DisasterAlleviationFoundation
