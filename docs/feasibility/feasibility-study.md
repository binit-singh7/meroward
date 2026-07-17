# Feasibility Study

## NirmanSathi

### An Integrated Residential Construction Governance & Marketplace Platform for Nepal

---

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
| Document Title   | Feasibility Study                                                  |
| Project Name     | NirmanSathi                                                        |
| Version          | 1.0                                                                |
| Document Status  | Draft                                                              |
| Course           | E-Governance                                                       |
| Academic Program | Bachelor of Computer Science and Information Technology (BCS CSIT) |
| Institution      | Orchid International College                                       |
| Authors          | Binit Kumar Singh, Alkesh Chaudhary, Prine Upadhaya                |
| Prepared On      | July 2026                                                          |

# Version History

| Version | Date      | Description               | Author(s)                                           |
| ------- | --------- | ------------------------- | --------------------------------------------------- |
| 1.0     | July 2026 | Initial feasibility study | Binit Kumar Singh, Alkesh Chaudhary, Prine Upadhaya |

# Table of Contents

1. Introduction
2. Project Overview
3. Objectives of the Feasibility Study
4. Technical Feasibility
5. Operational Feasibility
6. Economic Feasibility
7. Schedule Feasibility
8. Legal and Regulatory Feasibility
9. Organizational Feasibility
10. Risk Analysis
11. Risk Mitigation Strategy
12. Feasibility Summary
13. Conclusion
14. References

# Introduction

Digital transformation has become an essential component of public service delivery, enabling governments to improve efficiency, transparency, and accessibility through the use of information and communication technologies. In Nepal, municipalities have gradually adopted digital systems for various administrative services; however, residential construction management continues to rely heavily on manual procedures, resulting in delays, increased paperwork, and limited transparency.

NirmanSathi is proposed as an integrated residential construction governance and marketplace platform that combines e-governance services with construction-related commercial services. The platform enables citizens to apply for building permits online, submit required documents, track application status, and communicate with municipal authorities. In addition, it provides a marketplace where citizens can connect with verified architects, contractors, construction material suppliers, and equipment rental providers through a single unified system.

This feasibility study evaluates whether the proposed system can be successfully developed within the available academic resources, technical capabilities, budget, and project timeline. It also examines the operational, organizational, legal, and economic factors that influence the practicality of implementing NirmanSathi as a semester project while maintaining the potential for future real-world deployment.

# Project Overview

NirmanSathi is a web-based platform designed to simplify and modernize the residential construction process in Nepal. The system integrates municipal construction approval services with a digital construction marketplace, allowing citizens to manage the entire residential construction lifecycle through a single platform.

The governance component of the system focuses on digitizing the building permit process by enabling online application submission, document upload, permit review, approval workflow, and application status tracking. These services reduce dependency on manual paperwork while improving transparency and communication between citizens and municipal authorities. These services reduce dependency on manual paperwork while improving transparency and communication between citizens and municipal authorities.

The marketplace component complements the governance services by providing access to construction material suppliers through a digital marketplace. Citizens can browse products, add items to a shopping cart, and complete purchases using a simulated eSewa payment workflow. Additional marketplace services such as architect consultation, contractor hiring, and equipment rental are planned for future versions. Citizens can browse construction materials, request professional services, place marketplace orders, and complete purchases using a simulated eSewa payment workflow. This integrated approach eliminates the need to use multiple independent systems during residential construction projects.

The platform follows a multi-municipality architecture in which multiple municipalities can operate independently using the same software while maintaining complete separation of administrative data. This design promotes scalability, maintainability, and future adoption by local governments across Nepal.

# Objectives of the Feasibility Study

The primary objective of this feasibility study is to evaluate whether the proposed NirmanSathi platform can be realistically developed and demonstrated as a semester project while following professional software engineering practices.

The specific objectives are:

- To evaluate the technical feasibility of developing the system using Django, PostgreSQL, HTML, CSS, Bootstrap, and JavaScript.
- To assess whether the project can be completed within the available academic timeline and available development resources.
- To examine the operational feasibility of integrating a building permit management system with a construction material marketplace.
- To evaluate the economic feasibility of developing the project using open-source technologies and minimal financial resources.
- To identify legal and regulatory considerations related to digital governance and residential construction management in Nepal.
- To analyze the ability of municipalities and citizens to adopt the proposed digital workflow.
- To identify potential project risks and recommend appropriate mitigation strategies.
- To determine whether the proposed system provides sufficient academic value while addressing practical challenges in residential construction governance.

# Technical Feasibility

Technical feasibility evaluates whether the proposed system can be successfully developed using the available technologies, development tools, technical knowledge, and computing resources.

NirmanSathi is considered technically feasible because it utilizes modern, open-source technologies that are widely adopted in web application development. The selected technology stack is suitable for building scalable, secure, and maintainable applications while remaining appropriate for an academic project.

The backend of the system will be developed using the Django web framework with Python 3.x. Django follows the Model-View-Template (MVT) architecture and provides built-in features such as authentication, authorization, ORM (Object Relational Mapping), security mechanisms, and administrative interfaces. These capabilities reduce development time while promoting secure and maintainable software design.

PostgreSQL will be used as the database management system because of its reliability, performance, and support for complex relational data. Since NirmanSathi involves role-based access control, building permit applications, and marketplace transactions, PostgreSQL provides an efficient platform for managing structured relational data.

The frontend will be developed using HTML, CSS, Bootstrap, and JavaScript to create responsive and user-friendly interfaces that are compatible with modern web browsers. Bootstrap simplifies responsive design while JavaScript enables interactive user experiences.

Git and GitHub will be used for version control, allowing the development team to manage source code efficiently, track project history, and collaborate throughout the development process.

The project team possesses foundational knowledge of Django, PostgreSQL, frontend web technologies, and software engineering concepts acquired during the BCS CSIT program. Additional learning resources and official documentation will be used whenever necessary during implementation.

Considering the availability of development tools, technical resources, open-source frameworks, and the team's technical background, the development of NirmanSathi is technically feasible.

# Operational Feasibility

Operational feasibility evaluates whether the proposed system can effectively support the daily activities of its intended users and whether stakeholders are capable of adopting the new system.

NirmanSathi is designed to improve the residential construction process by replacing paper-based administrative procedures with a centralized digital platform. The proposed workflow closely follows existing municipal permit approval procedures while simplifying document submission, communication, and application tracking.

Citizens will be able to submit permit applications online, upload required documents, monitor application progress, register complaints, and access construction-related services without repeatedly visiting municipal offices.Municipality officers will review submitted permit applications, verify uploaded documents, approve or reject applications, and update their status through an administrative dashboard.

The marketplace enables citizens to purchase construction materials from registered suppliers without leaving the platform. This integration demonstrates the combination of e-governance and e-commerce within a single web application. This reduces fragmentation by enabling citizens to complete multiple construction-related activities from one platform.

Since the proposed workflow closely aligns with existing administrative practices while digitizing manual processes, minimal changes to municipal operations would be required. Basic training would enable municipal staff to effectively operate the system.

Therefore, the proposed platform is operationally feasible and capable of improving efficiency, transparency, and coordination among all stakeholders involved in residential construction.

# Economic Feasibility

Economic feasibility evaluates whether the proposed system can be developed within the available financial resources while providing sufficient value to its stakeholders.

As an academic project, NirmanSathi will be developed using open-source technologies, significantly reducing development costs. Django, PostgreSQL, Bootstrap, Visual Studio Code, Git, and GitHub are freely available for educational use, eliminating the need for expensive software licenses.

The project will primarily require existing computing resources owned by the development team, including personal computers and internet connectivity. Cloud deployment services such as Render or Railway may be used for demonstration purposes using their free or educational plans.

The simulated eSewa payment workflow eliminates the need for merchant registration, transaction fees, or production payment gateway integration while still demonstrating the complete online purchasing process within the marketplace.

Although the project does not aim to generate immediate financial returns, it demonstrates how municipalities can reduce administrative costs associated with paper-based processes, manual record management, and repetitive office visits. Citizens may also benefit from reduced travel costs, faster service delivery, and easier access to construction-related services.

Considering the minimal development cost, use of open-source software, and the potential operational benefits, the project is economically feasible.

# Schedule Feasibility

Schedule feasibility evaluates whether the proposed project can be completed within the available academic timeline while maintaining acceptable software quality.

NirmanSathi is planned as a semester project with an estimated development duration of approximately two and a half months. Considering the limited timeframe, the project will follow an incremental development approach in which the core governance and marketplace functionalities are prioritized for implementation while advanced features are reserved for future development.

The project development process follows the Software Development Life Cycle (SDLC), beginning with project planning and documentation, followed by requirement analysis, system design, implementation, testing, deployment, and final presentation.

To ensure successful project completion, the development team will focus on implementing the core building permit workflow and a construction material marketplace. Additional features have been intentionally deferred to future versions to maintain a realistic implementation scope. Features such as GIS integration, AI-assisted blueprint validation, mobile applications, and real payment gateway integration have been intentionally excluded from the current implementation due to time constraints.

Regular progress reviews, version control using GitHub, and milestone-based development will be adopted to monitor project progress and minimize delays.

Considering the defined project scope, available development time, and planned implementation strategy, the project is considered schedule feasible.

# Legal and Regulatory Feasibility

Legal and regulatory feasibility evaluates whether the proposed system complies with applicable laws, regulations, and government policies.

NirmanSathi has been designed primarily as an academic project intended to demonstrate the digital transformation of residential construction governance. The proposed workflows are inspired by the administrative procedures currently followed by municipalities in Nepal but do not replace official government systems.

The system aligns with Nepal's Digital Nepal Framework by promoting digital public service delivery, transparency, and improved citizen access to government services. The project also considers the principles of the Local Government Operation Act, 2017, which grants local governments the responsibility to regulate residential building construction and issue construction-related permits.

All personal information and uploaded documents within the demonstration system will be represented using sample or fictional data. No confidential government records or sensitive citizen information will be collected during development.

The simulated eSewa payment workflow is included solely for demonstration purposes and does not process actual financial transactions or interact with official payment gateway services.

Therefore, the proposed system does not conflict with existing legal or regulatory requirements and is considered legally feasible as an academic proof-of-concept.

# Organizational Feasibility

Organizational feasibility evaluates whether the intended users and participating organizations are capable of adopting and operating the proposed system.

The primary users of the implemented system include citizens, municipality officers, construction material suppliers, and system administrators. Other stakeholders such as architects, contractors, and equipment rental providers remain part of the project's long-term vision and future scope. Each user category is provided with role-specific functionalities designed to support their respective responsibilities within the residential construction process.

The proposed system closely follows the existing workflow used by municipalities for processing residential building permits. As a result, adoption of the system would require only moderate procedural adjustments rather than complete organizational restructuring.

Municipal officers and engineers would require basic training to become familiar with the digital permit workflow, document verification process, and dashboard functionalities. Citizens would benefit from simplified online services that reduce paperwork and unnecessary visits to municipal offices.

The multi-municipality architecture enables each municipality to manage its own users, applications, and administrative records independently while using the same software platform. This approach supports scalability without increasing operational complexity.

Since the system complements existing municipal processes rather than replacing them entirely, NirmanSathi is considered organizationally feasible for future adoption by local governments.

# Risk Analysis

Risk analysis identifies potential challenges that may affect the successful development and implementation of NirmanSathi. Identifying these risks during the planning phase allows the development team to prepare appropriate mitigation strategies and improve the overall likelihood of project success.

| Risk                                       | Probability | Impact | Mitigation Strategy                                                                  |
| ------------------------------------------ | ----------- | ------ | ------------------------------------------------------------------------------------ |
| Limited project development time           | High        | High   | Prioritize core modules and follow an incremental development approach.              |
| Requirement changes during development     | Medium      | Medium | Maintain proper documentation and update requirements through version control.       |
| Team coordination issues                   | Medium      | Medium | Conduct regular meetings, assign clear responsibilities, and monitor progress.       |
| Technical challenges while learning Django | Medium      | Medium | Refer to official documentation, online resources, and seek guidance when necessary. |
| Database design complexity                 | Medium      | High   | Complete ER diagrams and database design before implementation.                      |
| Loss of project data or source code        | Low         | High   | Use Git and GitHub for version control and maintain regular backups.                 |
| Browser compatibility issues               | Low         | Medium | Test the application on multiple modern web browsers during development.             |
| Simulated payment workflow limitations     | Low         | Low    | Clearly indicate that the payment module is for demonstration purposes only.         |
| Delays due to academic workload            | Medium      | High   | Prepare a realistic development schedule and complete documentation before coding.   |

# Risk Mitigation Strategy

To minimize project risks, NirmanSathi will be developed using an incremental and well-documented software development process. Project documentation will be completed before implementation to reduce requirement ambiguity and improve development efficiency.

Git and GitHub will be used throughout the project to maintain version history, facilitate collaboration, and prevent accidental loss of source code. Regular progress reviews and milestone-based development will help monitor project completion according to the planned schedule.

The project scope has been intentionally limited to the core building permit workflow and construction material marketplace. Advanced features such as architect services, contractor management, equipment rental, AI-assisted blueprint validation, GIS integration, and real payment gateway integration have been deferred to future versions.

Continuous testing during development will help identify defects early and improve overall software quality before final deployment.

# Feasibility Summary

The feasibility assessment indicates that NirmanSathi is a practical and achievable project within the scope of a BCS CSIT semester project. The use of modern open-source technologies, an incremental development strategy, and a clearly defined project scope significantly improve the likelihood of successful implementation.

The project demonstrates strong technical feasibility through the use of Django, PostgreSQL, Bootstrap, JavaScript, and GitHub. Operational feasibility is supported by aligning the system with existing municipal workflows while simplifying the residential construction process for citizens. Economic feasibility is achieved through the use of freely available development tools and minimal implementation costs. Schedule feasibility is maintained by prioritizing core functionalities and limiting advanced features to future development. Legal and organizational feasibility are also satisfied by aligning the project with Nepal's digital transformation initiatives while maintaining a scalable multi-municipality architecture.

Overall, the feasibility study concludes that NirmanSathi is technically, operationally, economically, legally, organizationally, and practically feasible for development as an academic project.

# Current Implementation Scope

The current implementation of NirmanSathi focuses on demonstrating the integration of e-governance and e-commerce through two core components:

### E-Governance

- User Authentication
- Citizen Registration
- Building Permit Application
- Document Upload
- Permit Approval Workflow
- Application Status Tracking

### E-Commerce

- Construction Material Marketplace
- Shopping Cart
- Simulated eSewa Payment
- Order Management

This implementation scope has been intentionally defined to ensure successful completion within the available academic timeline. Additional features described throughout the project documentation represent the long-term vision of the platform.

# Conclusion

The feasibility study demonstrates that the proposed NirmanSathi platform is a viable solution for improving residential construction governance through digital technologies. By integrating municipal permit management with a construction marketplace, the project addresses both administrative inefficiencies and the fragmented nature of construction-related services.

The evaluation confirms that the required technologies, development tools, project timeline, and available resources are sufficient to develop the core functionalities of the system. Although certain advanced features have been reserved for future implementation, the planned system architecture supports scalability and long-term enhancement without requiring significant structural changes.

As a result, NirmanSathi is considered a feasible academic project that effectively demonstrates the integration of e-governance and e-commerce principles while following professional software engineering practices and the Software Development Life Cycle (SDLC).

# Feasibility Matrix

| Feasibility Aspect             | Status     | Remarks                                                                      |
| ------------------------------ | ---------- | ---------------------------------------------------------------------------- |
| Technical Feasibility          | ✔ Feasible | Modern open-source technologies are available and suitable.                  |
| Operational Feasibility        | ✔ Feasible | Supports existing municipal workflows with digital improvements.             |
| Economic Feasibility           | ✔ Feasible | Development uses open-source software with minimal cost.                     |
| Schedule Feasibility           | ✔ Feasible | Incremental implementation makes the project achievable within the semester. |
| Legal & Regulatory Feasibility | ✔ Feasible | Supports Nepal's digital governance initiatives and uses simulated data.     |
| Organizational Feasibility     | ✔ Feasible | Multi-municipality architecture supports practical adoption.                 |

# Overall Recommendation

Based on the technical, operational, economic, legal, organizational, and schedule evaluations, the development team recommends proceeding with the implementation of NirmanSathi. The project is considered feasible for academic development and provides a strong foundation for future enhancement into a comprehensive residential construction governance and marketplace platform.

# References

1. Government of Nepal. _Digital Nepal Framework_. Ministry of Communication and Information Technology.
2. Ministry of Federal Affairs and General Administration (MoFAGA), Nepal.
3. Department of Urban Development and Building Construction (DUDBC). _Nepal National Building Code (NBC)_.
4. Local Government Operation Act, 2017, Government of Nepal.
5. Django Software Foundation. _Django Documentation_. https://docs.djangoproject.com/
6. PostgreSQL Global Development Group. _PostgreSQL Documentation_. https://www.postgresql.org/docs/
7. Bootstrap Team. _Bootstrap Documentation_. https://getbootstrap.com/docs/
8. Sommerville, I. _Software Engineering_. 10th Edition.
9. Pressman, R. S., & Maxim, B. R. _Software Engineering: A Practitioner's Approach_. 9th Edition.
10. Electronic Building Permit System (e-BPS), Nepal.
