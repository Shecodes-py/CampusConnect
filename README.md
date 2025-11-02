# CampusConnect
 A Unified Web App that integrates three essential services to give students back their time, money, and peace of mind.


🏫 CampusConnect: Unilag's Unified Digital Ecosystem

🎯 Project Overview

    CampusConnect is a comprehensive Single Page Application (SPA) designed for the SWE TechBloom Innovation Challenge. It addresses the daily inefficiencies and anxieties faced by university students by unifying three critical services—Productivity, Safety, and Welfare—into one seamless platform.

    The prototype demonstrates a unified, integrated data structure where users can transition instantly between services, reinforcing the concept of a "Campus Super App."

💡 The Problem & The Solution

    The Problem: Student life is plagued by wasted time (searching for available study spaces), financial loss (unrecovered lost items), and welfare risks (opaque vendor hygiene and pricing). These issues rely on fragmented, analog systems like notice boards and unreliable social media.

The Solution: CampusConnect replaces chaos with a unified, real-time platform that delivers:

Efficiency: Find resources and navigate instantly.

Security: Automated, safe item recovery.

Transparency: Data-driven choices for dining and services.

🛠️ Core Integrated Modules (The Three Pillars)
    
    The application architecture is built around three interdependent modules, all powered by a single backend database (simulated in this prototype):

Module

Core Function

Prototype Demonstration

    1. Productivity Hub
    
    Live Map Status: Real-time visibility of available study spaces, quiet zones, and functioning equipment.
    
    Real-Time Filtering: Filtering mock campus spaces by availability (Available, Quiet, Full).
    
    2. Safety Hub (FindIt)
    
    Automated Matching: Securely connects owners and finders through an intelligent Lost & Found matching engine.

    Matching Simulation: Clicking a 'Lost Item' instantly highlights its matching 'Found Item' card.
    
    3. Welfare Hub (Eats)
    
    Vendor Transparency: Community-verified hygiene ratings, taste scores, and a central price comparison tracker.
    
    Rating & Category Filtering: Filtering vendors by food category and minimum star rating.

⚙️ Technology Stack (MVP)

    CampusConnect is engineered for speed, simplicity, and rapid development, perfect for the initial submission phase.
    
    Frontend: HTML5, Tailwind CSS (for responsive design), and Vanilla JavaScript (for core interaction logic and state management).
    
    Charting/Visualization: Canvas elements are used for all visualizations (no external charting libraries in this single-file prototype, using custom CSS/HTML structures for display).
    
    Database (Planned): Google Firebase (Firestore & Auth) is specified for the production build to handle real-time updates and secure user authentication.

🚀 Getting Started

Prerequisites

    You need a modern web browser (Chrome, Firefox, Edge, Safari). No server or build process is required.

Installation & Execution

      This repository contains a single, self-contained file: campus_connect_prototype.html.



Run Locally:
 Simply open the file in your browser:

open campus_connect_prototype.html


Note: All core functionality (navigation, data filtering, and the matching simulation) is handled directly by the embedded JavaScript and CSS.

📈 Future Development & Scaling

The current prototype is designed to easily integrate with a Firebase backend. Next steps include:

     Firestore Integration: Replacing the mock appData object with live onSnapshot listeners to enable true real-time functionality for the Productivity Map.
     
     Authentication: Implementing Firebase Auth to secure user profiles and verify student identity.
     
     Secure Chat: Building the secure Firestore-based chat service between matched users in the FindIt module.
     
     Vendor Submissions: Developing the UI and Cloud Functions logic to handle new review submissions and recalculate vendor average scores.
