📋 Project Overview
The Zee Alleviation Foundation is a comprehensive disaster relief management system built with ASP.NET Core MVC. The platform enables efficient coordination of emergency response efforts through incident reporting, donation management, and volunteer coordination.

🚀 Features
Core Modules
🔴 Incident Management - Report and track emergency incidents

💰 Donation System - Manage monetary and resource donations

👥 Volunteer Coordination - Register and manage volunteers

👤 User Management - Secure authentication and user profiles

Key Functionalities
Real-time incident reporting and tracking

Donation categorization and management

Volunteer skill matching and availability tracking

Responsive design for all devices

Professional dashboard with analytics

🛠️ Technology Stack
Frontend
HTML5 with Razor syntax

CSS3 with custom properties and modern features

Bootstrap 5.3.0 - Responsive framework

Font Awesome 6.0.0 - Icons

Google Fonts - Poppins & Inter fonts

Backend
ASP.NET Core MVC

Entity Framework Core

SQL Server (or your preferred database)

Authentication & Authorization

📁 Project Structure
text
Sindiswe-Alleviation-Foundation/
│
├── Controllers/
│   ├── HomeController.cs
│   ├── IncidentController.cs
│   ├── DonationController.cs
│   └── VolunteerController.cs
│
├── Models/
│   ├── User.cs
│   ├── LoginViewModel.cs
│   ├── RegisterViewModel.cs
│   ├── IncidentReport.cs
│   ├── Donation.cs
│   └── Volunteer.cs
│
├── Views/
│   ├── Home/
│   │   ├── Index.cshtml
│   │   ├── Login.cshtml
│   │   ├── Register.cshtml
│   │   └── Profile.cshtml
│   │
│   ├── Incident/
│   │   ├── Index.cshtml
│   │   ├── Report.cshtml
│   │   └── Details.cshtml
│   │
│   ├── Donation/
│   │   ├── Index.cshtml
│   │   ├── Create.cshtml
│   │   └── AllDonations.cshtml
│   │
│   └── Volunteer/
│       ├── Index.cshtml
│       ├── Register.cshtml
│       └── MyRegistration.cshtml
│
├── wwwroot/
│   ├── css/
│   ├── js/
│   └── images/
│
└── Program.cs
🎨 Design Features
Visual Design
Modern Color Scheme: Blue and purple gradients with professional accents

Glass Morphism Effects: Frosted glass navigation and cards

Responsive Layout: Mobile-first design approach

Interactive Elements: Smooth animations and hover effects

Professional Typography: Poppins and Inter font combination

Layout Components
Left Sidebar Navigation - Fixed navigation with user menu

Top Navigation Bar - Page title and user actions

Hero Sections - Engaging landing areas with call-to-action buttons

Card-based Design - Consistent card components throughout

Statistics Dashboard - Impact metrics and analytics

🔧 Installation & Setup
Prerequisites
.NET 6.0 or later

SQL Server (or compatible database)

Visual Studio 2022 or VS Code
