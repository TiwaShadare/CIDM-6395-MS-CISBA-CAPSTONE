# Capstone Project Proposal

## SalonShield: A Cloud-Based Cybersecurity Risk Management System for Small Nail Salons and Beauty Spas

### Project Overview

SalonShield is a proposed cloud-based cybersecurity risk management application designed for small, independently owned nail salons and beauty spas. These businesses increasingly depend on technologies such as point-of-sale systems, online appointment platforms, business email, Wi-Fi networks, cloud applications, employee devices, and digital customer records, but they may lack dedicated cybersecurity personnel and formal processes for managing technology-related risks. The purpose of SalonShield is to provide a centralized system through which salon owners and managers can document technology assets, identify and prioritize cybersecurity risks, track security controls and remediation activities, conduct basic cybersecurity audits, maintain incident and contingency plans, and visualize their overall cybersecurity posture.

### Proposed Synthesis

The project will integrate four competency areas—Data Management (DM), Business Analytics (BA), Software Systems (SS), and Cybersecurity and Networking (CN)—as a connected value chain rather than as independent components. **Data Management** will establish the relational database used to capture and organize assets, threats, vulnerabilities, risks, security controls, remediation activities, audits, users, and incidents. **Business Analytics** will use this data to calculate and classify risk scores, identify high-priority risks, evaluate audit results and remediation progress, and produce dashboard visualizations that support management decision-making. **Software Systems** will operationalize these capabilities through a functional web application that provides forms, workflows, dashboards, application logic, and database interaction. **Cybersecurity and Networking** will address the protection and deployment of the application through authentication, role-based access control, secure credential and database management, input validation, protected communications, containerization, and cloud/network security principles.

The four areas are intentionally dependent upon one another. DM provides the structured data required by BA; BA transforms that data into meaningful risk information; SS delivers the data and analytical capabilities through a usable application; and CN protects the application, its users, communications, and underlying information. Removing any one area would therefore reduce or break an important capability of the overall system.

### Prototype and Scope

The semester deliverable will be a minimum viable prototype rather than a production cybersecurity platform. The prototype will focus on core features including user login, technology asset inventory, cybersecurity risk assessment, automated risk scoring and classification, a risk dashboard, security-control and remediation tracking, a basic cybersecurity audit, and incident/contingency planning. The proposed technology stack includes MySQL for relational data management; Python and FastAPI for application and business logic; HTML, CSS, JavaScript, and Chart.js for the user interface and visualizations; Pytest for testing; Git and GitHub for version control; and Docker and cloud technologies for deployment.

### Expected Outcome

The expected outcome is a functional prototype demonstrating how concepts and skills developed throughout the Computer Information Systems and Business Analytics program can be synthesized to address a realistic business problem. SalonShield will demonstrate the complete progression from capturing and managing cybersecurity data, to analyzing that data, to delivering actionable information through a software system, and finally to securing the system and its information. The completed artifact, source code, data, documentation, competency evidence, and supporting materials will be maintained within a single GitHub repository.
