# Project Proposal

## NirmanSathi

## An Integrated Residential Construction Governance & Marketplace Platform for Nepal

## Submitted By

- **Binit Kumar Singh**
- **Alkesh Chaudhary**
- **Prine Upadhaya**

**Program:** Bachelor of Computer Science and Information Technology (BCS CSIT)

**Semester:** Sixth Semester

---

## Submitted To

**Department of Computer Science**

**Orchid International College**

---

## Course

**E-Governance**

---

# Document Information

| Field            | Details                                                            |
| ---------------- | ------------------------------------------------------------------ |
| Document Title   | Project Proposal                                                   |
| Project Name     | NirmanSathi                                                        |
| Version          | 1.0                                                                |
| Document Status  | Draft                                                              |
| Course           | E-Governance                                                       |
| Academic Program | Bachelor of Computer Science and Information Technology (BCS CSIT) |
| Institution      | Orchid International College                                       |
| Authors          | Binit Kumar Singh, Alkesh Chaudhary, Prine Upadhaya                |
| Prepared On      | July 2026                                                          |

# Table of Contents

1. Abstract
2. Introduction
3. Background
4. Existing System Analysis
5. Problem Statement
6. Proposed Solution
7. Objectives
8. Scope
9. Stakeholders
10. System Overview
11. Technology Stack
12. Development Methodology
13. Project Timeline
14. Expected Benefits
15. Limitations
16. Future Scope
17. Conclusion
18. References

## Abstract

The construction approval process in Nepal is still largely dependent on manual procedures involving physical document submission, multiple visits to municipal offices, and limited transparency in application tracking. Citizens are also required to search independently for architects, contractors, suppliers, and equipment providers, resulting in a fragmented construction experience.

NirmanSathi is proposed as a centralized web-based platform that integrates digital residential construction governance with a construction material marketplace. The current implementation enables citizens to submit building permit applications, upload required documents, track application status, and purchase construction materials using a simulated eSewa payment workflow. Future versions are envisioned to include architect and contractor marketplaces, equipment rental services, inspections, and digital certificate management.

The proposed system is designed for use by municipalities across Nepal using a shared platform while ensuring that each municipality manages only its own administrative data. This approach promotes transparency, efficiency, accountability, and improved service delivery in residential construction management.

The project will be developed using Django as the backend framework, PostgreSQL as the database management system, and HTML, CSS, Bootstrap, and JavaScript for the frontend. By combining e-governance services with an integrated construction marketplace, NirmanSathi aims to simplify the construction process for citizens while supporting municipalities in delivering faster and more efficient public services.

## Introduction

The construction sector plays a significant role in the economic and social development of Nepal. Every year, thousands of citizens undertake residential construction and renovation projects that require approvals from their respective municipalities. These approvals ensure that buildings comply with legal regulations, safety standards, zoning requirements, and municipal building codes.

This project specifically focuses on residential building construction and home renovation activities within municipalities of Nepal. It is intended to simplify the construction process for individual homeowners by integrating municipal services with construction-related business services. The project does not cover large-scale infrastructure projects such as highways, bridges, airports, hydropower projects, or commercial megaprojects, ensuring that the scope remains practical and achievable for implementation.

Despite the increasing adoption of digital technologies in public administration, the construction approval process in many municipalities remains largely manual. Citizens are often required to visit municipal offices multiple times to obtain information, submit application forms, provide supporting documents, and track the status of their applications. This traditional approach consumes considerable time and resources while limiting transparency and communication between citizens and local government authorities.

In addition to administrative challenges, individuals planning construction projects frequently struggle to find reliable architects, contractors, construction material suppliers, and equipment rental providers. These services are usually scattered across different platforms or rely heavily on personal networks and recommendations, making the overall construction process inefficient and difficult to manage.

To address these challenges, this project proposes **NirmanSathi**, a centralized web-based platform that integrates digital residential construction governance with a construction material marketplace. The current implementation allows citizens to apply for building permits online, upload required documents, monitor application status, and purchase construction materials using a simulated eSewa payment workflow. The platform is designed with a modular architecture that allows future versions to incorporate additional services such as architect and contractor marketplaces, equipment rental, construction inspections, and digital certificate management.

The platform is designed to support municipalities throughout Nepal using a shared system architecture while ensuring that each municipality manages only its own administrative data. By integrating governance services and marketplace functionalities into a single platform, NirmanSathi aims to improve service delivery, increase transparency, reduce administrative workload, and simplify the overall residential construction process.

The platform is designed to support municipalities throughout Nepal using a shared system architecture while ensuring that each municipality manages only its own administrative data. By integrating governance services and marketplace functionalities into a single platform, NirmanSathi aims to improve service delivery, increase transparency, reduce administrative workload, and simplify the overall residential construction process.

## Background

The Government of Nepal has increasingly prioritized digital transformation through various e-governance initiatives aimed at improving public service delivery, transparency, and administrative efficiency. Local governments have gradually adopted digital systems for services such as vital registration, tax collection, and online information dissemination. However, many construction-related administrative processes continue to rely on traditional paper-based workflows, limiting the overall effectiveness of digital governance.

The Government of Nepal has introduced several digital transformation initiatives to improve public service delivery through e-governance. One of the major national strategies is the Digital Nepal Framework, which promotes the adoption of digital technologies across multiple sectors, including urban infrastructure and public administration. The framework encourages local governments to modernize public services, improve transparency, and provide efficient digital services to citizens. However, many construction-related municipal services still rely on manual procedures or partially digitized systems, highlighting the need for integrated digital platforms that simplify the residential construction process.

The process of obtaining building permits and other construction-related approvals is an essential responsibility of local municipalities. These procedures help ensure that residential buildings comply with building codes, land-use regulations, and public safety standards. Despite their importance, the application and approval processes often involve manual documentation, multiple office visits, lengthy verification procedures, and limited visibility into application progress.

At the same time, citizens undertaking residential construction projects must independently search for architects, contractors, engineers, suppliers, and equipment rental providers. Since these services are typically available through separate businesses or informal networks, the lack of an integrated platform increases the complexity of planning and managing construction projects.

With increasing internet accessibility and the growing adoption of digital technologies in Nepal, there is an opportunity to modernize construction governance through a unified digital platform. By integrating government services with a verified construction marketplace, municipalities can provide more transparent and efficient public services while citizens can access all essential construction-related services from a single platform.

NirmanSathi is proposed as a response to these challenges by providing a centralized digital ecosystem that supports residential construction management from permit application to project completion. The platform aligns with the objectives of e-governance by promoting transparency, efficiency, accountability, and citizen-centric service delivery while also supporting Nepal's ongoing digital transformation.

# Existing System Analysis

At present, residential construction approval in Nepal is carried out through a combination of manual administrative procedures and electronic permit management systems implemented by some municipalities. Citizens are generally required to prepare building designs, collect ownership documents, submit applications to municipal offices, communicate with engineers, and wait for approvals before beginning construction.

Several municipalities in Nepal have adopted the Electronic Building Permit System (e-BPS), which digitizes the building permit approval workflow. The system allows citizens to submit permit applications online, upload building drawings, track application status, and receive approvals from municipal officers and engineers. This has significantly improved transparency and reduced paperwork compared to traditional manual processes.

Although e-BPS successfully digitizes the permit approval process, its primary objective is municipal administration. It does not provide an integrated platform where citizens can discover verified architects, compare contractors, request quotations, purchase construction materials, rent construction equipment, or manage construction-related activities through a single system.

NirmanSathi is proposed to address this gap by extending beyond permit management. Rather than functioning only as a municipal permit system, it integrates construction governance with a marketplace for verified professionals, suppliers, and equipment providers. This enables citizens to manage the complete residential construction journey—from planning and permit application to construction and project completion—through one centralized platform.

## Problem Statement

The residential construction approval process in many municipalities of Nepal continues to rely heavily on manual administrative procedures. Citizens are required to visit municipal offices multiple times to obtain application forms, submit documents, verify application status, and collect approvals or certificates. This paper-based approach often results in long processing times, increased administrative workload, and limited transparency throughout the approval process.

Another major challenge is the lack of an integrated platform for construction-related services. Citizens must independently search for architects, contractors, engineers, construction material suppliers, and equipment rental providers through personal contacts or different online and offline sources. This fragmented approach makes project planning more time-consuming and increases the difficulty of finding reliable and verified service providers.

Although electronic permit systems have been introduced in some municipalities, these systems primarily focus on digitizing administrative approval processes. Citizens still need to rely on multiple independent platforms or personal networks to hire architects, contractors, purchase construction materials, and rent construction equipment. The absence of a unified digital ecosystem creates unnecessary complexity, reduces transparency, and increases the overall time and effort required to complete residential construction projects.

Municipal authorities also face operational challenges in managing construction permits and inspections. Manual record keeping, physical document storage, and limited digital communication make it difficult to efficiently process applications, monitor project progress, maintain historical records, and generate administrative reports.

Furthermore, the absence of a centralized digital platform reduces transparency and accountability. Citizens often have limited visibility into the status of their applications, while municipalities have fewer opportunities to streamline workflows, improve service delivery, and reduce paperwork.

These challenges highlight the need for a unified digital platform that modernizes construction governance while simultaneously providing access to trusted construction professionals, suppliers, and related services. Such a system can improve efficiency, transparency, and accessibility for both citizens and municipal authorities.

## Proposed Solution

To address the challenges associated with residential construction governance and fragmented construction services, this project proposes **NirmanSathi**, a centralized web-based platform that integrates digital municipal services with a construction marketplace.

Unlike conventional electronic building permit systems that primarily focus on digitizing municipal approval workflows, NirmanSathi is designed as an integrated residential construction ecosystem. The platform combines e-governance services with a construction marketplace, allowing citizens to access government services while also connecting with verified construction professionals and material suppliers through a single digital platform.

The proposed solution aims to eliminate the fragmentation that currently exists in the residential construction process. Instead of using separate systems for permit applications, professional hiring, material procurement, and equipment rental, citizens can manage their entire construction journey within one centralized application. This integrated approach improves convenience, transparency, and coordination among all stakeholders involved in residential construction.

The platform is designed to streamline the entire residential construction lifecycle, beginning with online building permit applications and continuing through inspections, certificate issuance, and project completion. Citizens can submit applications, upload required documents, monitor application status, and communicate with municipal authorities through a single digital interface.

NirmanSathi follows Nepal's administrative hierarchy by allowing multiple municipalities to operate on a shared platform while ensuring that each municipality manages only its own data. Municipal officers and engineers can review applications, conduct inspections, verify submitted documents, issue approvals, and generate digital certificates through dedicated administrative dashboards.

In addition to e-governance services, the platform incorporates a construction marketplace where verified construction professionals and material suppliers. can register their services and products. Citizens can browse professional profiles, request quotations, purchase construction materials, and rent construction equipment directly through the platform.

By combining government services and construction-related commerce into a unified ecosystem, NirmanSathi aims to improve transparency, reduce administrative delays, simplify construction project management, and enhance the overall experience for both citizens and municipalities.The proposed architecture follows a modular design, allowing additional government services and commercial modules to be integrated in future versions without major modifications to the existing system.

The proposed architecture follows a modular and incremental software development approach. Core governance and marketplace functionalities will be implemented during the current project phase, while additional services can be integrated in future versions without requiring major architectural modifications.

## Objectives

### General Objective

The primary objective of NirmanSathi is to develop a centralized web-based platform that modernizes residential construction governance while integrating a trusted construction marketplace. The system aims to improve the efficiency, transparency, and accessibility of municipal construction-related services while simplifying the process of connecting citizens with verified construction professionals and suppliers.

### Specific Objectives

The specific objectives of the proposed system are:

- To digitize the residential building permit application process.
- To reduce paperwork and minimize physical visits to municipal offices.
- To provide real-time application tracking for citizens.
- To facilitate digital document submission and verification.
- To support municipal officers and engineers in reviewing and approving applications efficiently.
- To maintain municipality-specific data while operating on a centralized platform.
- To provide an online construction material marketplace with a simulated e-commerce purchasing workflow.
- To simplify the discovery, ordering, and purchase of construction materials through a centralized marketplace.
- To create a unified digital ecosystem that supports the complete residential construction lifecycle.
- To support secure shopping cart management and simulated eSewa payment processing.
- To develop a scalable platform capable of supporting additional construction service marketplaces in future versions.
- To promote transparency and accountability throughout residential construction projects.
- To develop a scalable platform that can be adopted by municipalities across Nepal while maintaining municipality-specific administrative data.

## Scope

The scope of NirmanSathi is limited to residential construction management within municipalities of Nepal. The system focuses on digitizing construction approval workflows while providing an integrated marketplace for construction-related services.

The project includes the following major areas:

The following scope represents the complete conceptual vision of NirmanSathi. Due to the limited duration of the semester project, only selected modules are implemented in the current version. The detailed implementation scope is presented later in this proposal.

### E-Governance

- Building Permit Management (New Construction & Renovation)
- Construction Inspection Management
- Completion & Occupancy Certificate Issuance
- Application Tracking
- Complaint Management

### Marketplace

- Verified Construction Professional Services (Architects & Contractors)
- Construction Material Marketplace
- Equipment Rental Services
- Quotation Management
- Product Ordering
- Simulated Digital Payment

The project is designed for residential buildings only and does not cover large-scale infrastructure projects such as highways, bridges, hydropower projects, or commercial megaprojects.

The marketplace includes a simulated online payment workflow to demonstrate the purchasing process for construction materials and equipment rentals. The system records payment transactions without connecting to an actual payment gateway.

Given the semester timeline, not all modules above are built to the same depth — see **Implementation Scope** for the breakdown of fully implemented versus partially implemented modules.

### System Coverage

The proposed system covers the following functional areas:

#### Governance Services

- Online Building Permit Application (New Construction & Renovation)
- Blueprint Submission and Verification
- Construction Inspection Management
- Completion & Occupancy Certificate Issuance
- Complaint Registration and Resolution
- Application Status Tracking

#### Construction Marketplace

- Verified Construction Professional Directory (Architects & Contractors)
- Construction Material Marketplace
- Equipment Rental Services
- Quotation Request Management
- Product Ordering and Order Tracking

#### Administration

- User and Role Management
- Province, District, Municipality, and Ward Management
- Dashboard and Reporting
- Notification Management

# 8. Implementation Scope

NirmanSathi is envisioned as a comprehensive residential construction governance and marketplace platform. However, considering the academic nature of this project and the available development timeline, the current implementation focuses on the core functionalities required to demonstrate the integration of e-governance and e-commerce.

The implemented features include:

## E-Governance

- User Authentication and Role-Based Access Control
- Citizen Registration and Profile Management
- Province, District, Municipality, and Ward Management
- Building Permit Application
- Document Upload
- Permit Review and Approval Workflow
- Application Status Tracking

## E-Commerce

- Construction Material Marketplace
- Product Category Management
- Shopping Cart
- Simulated eSewa Payment Workflow
- Order History

The modules listed above represent the complete implementation scope of the current academic project. All remaining features described elsewhere in this proposal illustrate the long-term vision of NirmanSathi and are intentionally excluded from the current implementation due to the project's limited duration.

## Assumptions

The proposed system is developed based on the following assumptions:

- Citizens have access to internet-enabled devices.
- Municipalities are willing to adopt standardized digital permit procedures.
- Municipal officers and engineers perform document verification through the system.
- Construction professionals voluntarily register and maintain accurate profiles.
- Uploaded documents are authentic and verified by the respective municipal authorities.
- Simulated payment transactions are sufficient to demonstrate the complete e-commerce workflow.

## Stakeholders

The current implementation primarily involves Citizens, Municipality Officers, Construction Material Suppliers, and System Administrators. Additional stakeholders such as Architects, Contractors, and Equipment Rental Providers are part of the platform's long-term vision and are not included in the current implementation.

### Primary Stakeholders

#### Citizens

Citizens are the primary users of the system. They can register on the platform, apply for construction permits, upload required documents, track application progress, hire construction professionals, purchase construction materials, and submit complaints related to construction activities.

#### Municipal Officers

Municipal officers are responsible for reviewing permit applications, verifying submitted documents, approving or rejecting requests, issuing certificates, and managing municipal construction records.

#### Municipal Engineers

Municipal engineers evaluate submitted building plans, conduct site inspections, prepare inspection reports, and recommend approval or rejection based on construction regulations.

#### Verified Architects

Verified architects create professional profiles on the platform and offer architectural design, structural planning, and construction consultation services to citizens.

#### Verified Contractors

Verified contractors provide construction and renovation services, respond to project requests, submit quotations, and manage construction projects.

#### Construction Material Suppliers

Construction material suppliers register their businesses, manage product inventories, process customer orders, and sell construction materials through the marketplace.

#### Verified Equipment Rental Providers

Equipment rental providers list construction equipment available for rent, manage rental bookings, and coordinate equipment availability with customers.

#### System Administrator

The system administrator manages platform configuration, user roles, administrative hierarchy, municipality registration, and overall system maintenance.

## System Overview

NirmanSathi is a centralized web-based platform designed to integrate construction governance services with a construction marketplace within a single digital ecosystem.

The system supports multiple municipalities across Nepal through a centralized architecture while ensuring complete data isolation between municipalities. Each municipality independently manages its officers, engineers, citizens, applications, inspections, certificates, and administrative records.

The platform consists of four major functional components that work together to provide an integrated residential construction ecosystem.

### Authentication and User Management

This module manages user registration, authentication, role-based authorization, and profile management. Different user roles such as Citizens, Municipality Officers, Construction Material Suppliers, and System Administrators are provided with dedicated dashboards and permissions according to their responsibilities.

### E-Governance Module

This module digitizes residential construction approval workflows, including:

- Building Permit Application (New Construction & Renovation)
- Blueprint Submission
- Inspection Management
- Completion & Occupancy Certificate Issuance
- Complaint Management
- Application Tracking

### Construction Marketplace

The current implementation of the marketplace focuses on construction material purchasing through an integrated e-commerce module. Citizens can browse available products, add items to a shopping cart, place orders, and complete purchases using a simulated eSewa payment workflow. The modular architecture also allows future expansion to include architect and contractor marketplaces, equipment rental services, and quotation management.

The marketplace currently includes:

- Construction Material Marketplace
- Product Category Management
- Shopping Cart
- Order Management
- Simulated eSewa Payment Workflow

### Administration Module

The administration module enables the management of Nepal's administrative hierarchy, including Provinces, Districts, Municipalities, and Wards. It also provides tools for user management, system configuration, reporting, notifications, and overall platform administration. This centralized architecture allows multiple municipalities to use the same software while ensuring that each municipality can access only its own data.

### Unique Value Proposition

The primary strength of NirmanSathi lies in its ability to integrate digital governance with construction-related commercial services. While existing electronic permit systems focus mainly on municipal approval workflows, NirmanSathi extends beyond permit management by providing access to verified professionals, construction material suppliers, equipment rental services, quotation management, and project support. This enables citizens to complete the entire residential construction process using a single unified platform rather than relying on multiple disconnected systems.

## Technology Stack

The proposed system will be developed using modern web technologies to ensure scalability, maintainability, and performance.

| Layer                   | Technology                           |
| ----------------------- | ------------------------------------ |
| Backend Framework       | Django                               |
| Programming Language    | Python 3.x                           |
| Frontend                | HTML5, CSS3, Bootstrap 5, JavaScript |
| Database                | PostgreSQL                           |
| Version Control         | Git & GitHub                         |
| Documentation           | Markdown                             |
| UI Design               | Figma                                |
| Development Environment | Visual Studio Code                   |
| Deployment (Future)     | Render                               |

The selected technology stack provides rapid development, strong community support, secure authentication mechanisms, and efficient database management suitable for large-scale web applications.
**Payment Integration:** Simulated eSewa payment workflow (demonstration only)

## Non-Functional Requirements

The system is expected to satisfy the following non-functional requirements:

- Secure authentication and authorization using role-based access control.
- Responsive user interface compatible with desktop and mobile devices.
- Reliable data storage using PostgreSQL.
- Scalable architecture capable of supporting multiple municipalities.
- Maintainable and modular software design following Django best practices.
- Efficient performance for common operations such as application tracking, permit processing, and marketplace browsing.
- Data privacy by ensuring municipalities can access only their own administrative records.

## Development Methodology

The development of NirmanSathi will follow the Software Development Life Cycle (SDLC) to ensure a systematic and organized development process.

The project will be completed through the following phases:

1. Project Planning
2. Feasibility Study
3. Software Requirement Specification (SRS)
4. System Design (UML Diagrams)
5. Database Design
6. User Interface Design
7. Backend Development
8. Frontend Development
9. System Testing
10. Deployment
11. Final Documentation

Each phase produces clearly defined deliverables that serve as the foundation for the next stage of development. This structured methodology helps reduce development risks, improve maintainability, and ensure that project objectives are achieved within the planned schedule.

## Project Timeline

The development of NirmanSathi is planned over a period of approximately two and a half months. The project will follow a structured Software Development Life Cycle (SDLC), ensuring that each phase is completed before proceeding to the next.

| Phase                        | Activities                                                                   | Duration |
| ---------------------------- | ---------------------------------------------------------------------------- | -------- |
| Project Planning             | Idea finalization, proposal preparation                                      | Week 1   |
| Requirement Analysis         | Feasibility study, SRS documentation                                         | Week 1–2 |
| System Design                | UML diagrams, database design, UI wireframes                                 | Week 2–3 |
| Backend Development          | Django project setup, authentication, permit management, marketplace modules | Week 3–7 |
| Frontend Development         | User interface implementation and integration                                | Week 5–8 |
| Testing & Debugging          | Functional testing, bug fixing, user acceptance testing                      | Week 8–9 |
| Documentation & Presentation | Final report, presentation slides, deployment                                | Week 10  |

## Expected Benefits

The successful implementation of NirmanSathi is expected to benefit citizens, municipalities, construction professionals, and the overall digital governance ecosystem in Nepal.

### Benefits for Citizens

- Simplifies the residential construction process through a single digital platform.
- Reduces the need for repeated visits to municipal offices.
- Enables online application submission and real-time permit tracking.
- Provides access to verified architects, contractors, suppliers, and equipment rental providers.
- Improves transparency and convenience throughout the construction lifecycle.
- Demonstrates a streamlined digital payment workflow for purchasing construction materials and booking equipment rental services.

### Benefits for Municipalities

- Digitizes construction permit management and record keeping.
- Reduces paperwork and manual administrative workload.
- Improves coordination among municipal officers and engineers.
- Enhances transparency, accountability, and service delivery.
- Enables better monitoring and reporting of construction activities.

### Benefits for Construction Professionals

- Provides a centralized platform to showcase professional services.
- Increases visibility to potential clients.
- Simplifies communication with citizens.
- Creates opportunities for business growth through digital engagement.

### Benefits for Construction Material Suppliers

- Expands market reach through an online marketplace.
- Simplifies inventory and order management.
- Enables direct interaction with customers.
- Increases business opportunities through digital commerce.

### Overall Benefits

- Supports Nepal's digital transformation initiatives.
- Promotes integrated e-governance services.
- Encourages transparency and accountability in construction governance.
- Demonstrates how digital technologies can improve public service delivery while supporting local businesses.

## Limitations

The current implementation represents a proof-of-concept developed within the constraints of a semester-long academic project. Consequently, several advanced features are intentionally simplified or excluded.

The limitations include:

- The eSewa payment workflow is simulated and does not connect to the official payment gateway.
- Real-time SMS and email notification services are not integrated.
- GIS mapping and land visualization are not implemented.
- AI-assisted blueprint validation is outside the current scope.
- Digital signatures are not supported.
- Integration with existing municipal information systems is not implemented.
- Mobile applications are reserved for future development.
- The system focuses exclusively on residential construction and renovation projects.

## Future Scope

Although the current implementation focuses on the core residential construction workflow, the proposed architecture is designed to support future expansion. Potential enhancements include:

- Integration with official eSewa, Khalti, and banking payment gateways.
- SMS, email, and push notification services.
- GIS-based land visualization and mapping.
- AI-assisted blueprint validation based on the Nepal National Building Code.
- Digital signature support for permit approvals and certificates.
- Drone-assisted construction inspections.
- Android and iOS mobile applications.
- Integration with Nepal National Identity (NID).
- Property tax and municipal revenue integration.
- Analytics dashboards for municipal planning and decision making.
- Public APIs for integration with other e-governance platforms.

## Conclusion

NirmanSathi presents an integrated approach to modernizing residential construction governance in Nepal by combining digital municipal services with a construction marketplace. Rather than functioning solely as a building permit management system, the proposed platform supports the complete residential construction lifecycle, including permit application, professional service discovery, material procurement, equipment rental, construction inspection, and certificate issuance.

The project addresses challenges associated with fragmented construction services by providing a unified platform that improves transparency, efficiency, and collaboration among citizens, municipalities, construction professionals, and suppliers. Its centralized architecture enables multiple municipalities to operate independently on a shared platform while maintaining secure separation of administrative data.

Although developed as a semester project, NirmanSathi follows professional software engineering practices and adopts a modular architecture that supports future expansion. The current implementation demonstrates the core concepts of integrating e-governance services with construction-related e-commerce, while providing a scalable foundation for advanced features such as GIS integration, AI-assisted blueprint validation, digital payments, and mobile applications.

## References

1. Government of Nepal. _Digital Nepal Framework_. Ministry of Communication and Information Technology.
2. Ministry of Federal Affairs and General Administration (MoFAGA), Nepal.
3. Department of Urban Development and Building Construction (DUDBC). _Nepal National Building Code (NBC)_.
4. Local Government Operation Act, 2017, Government of Nepal.
5. Django Software Foundation. _Django Documentation_. <https://docs.djangoproject.com/>
6. PostgreSQL Global Development Group. _PostgreSQL Documentation_. <https://www.postgresql.org/docs/>
7. Bootstrap Team. _Bootstrap Documentation_. <https://getbootstrap.com/docs/>
8. Sommerville, I. _Software Engineering_. 10th Edition.
9. Pressman, R. S., & Maxim, B. R. _Software Engineering: A Practitioner's Approach_. 9th Edition.
10. Electronic Building Permit System (e-BPS), Nepal (reference for existing municipal permit management systems).
11. World Bank. Digital Development resources.
12. Nepal Government e-Governance Master Plan.
