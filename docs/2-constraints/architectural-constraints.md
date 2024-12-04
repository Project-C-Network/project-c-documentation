---
id: architectural-constraints
title: Architectural Constraints
sidebar_position: 2
---

# Constraints in Architectural

Architects must have a clear understanding of the areas where they have creative freedom in their design choices and where they are bound by constraints. These constraints must be addressed comprehensively, as they are non-negotiable factors within the project.

## Key Points:
- **Creative Freedom**: The aspects of the project where architects can explore innovative and unique design solutions.
- **Constraints**: Rigid factors such as regulatory, structural, environmental, or budgetary limitations that must be adhered to during the project.

| Constraint                    | Explanation                                                                                                    |
|-------------------------------|----------------------------------------------------------------------------------------------------------------|
| Scalability                   | The architecture must support scaling to handle increasing numbers of users and localized data as the application grows. |
| Data Privacy                  | User data must comply with local privacy regulations (e.g., GDPR, HIPAA, etc.) and ensure that sensitive data is securely stored and transmitted. |
| Geolocation Services          | Integration of geolocation services (e.g., Google Maps, OpenStreetMap) must adhere to API usage policies and provide accurate, real-time location-based data. |
| Localization Support          | The application must support multiple languages and formats (dates, currency) based on the user's locality. |
| Offline Functionality         | Some features should work offline (e.g., local caching of maps or reports) to accommodate users with limited internet access. |
| Accessibility (WCAG)          | The application must comply with Web Content Accessibility Guidelines (WCAG) to ensure usability for all users, including those with disabilities. |
| Real-Time Updates             | The application should provide real-time notifications and updates for concerns raised, ensuring users stay informed. |
| Security Measures             | Implementation of strong authentication (e.g., OAuth, 2FA) and data encryption to protect user accounts and reports. |
| Resource Constraints          | The architecture must consider limited resources in some localities (e.g., low bandwidth, older devices) to ensure smooth performance. |
| Community Moderation          | Support tools for community-driven content moderation to maintain appropriate and relevant content. |
| Disaster Resilience           | The system should be robust and capable of functioning during disasters when social concerns are at their peak. |
| Open-Source or Cost-Free Components | Use open-source or cost-free software and frameworks where feasible to minimize operational costs. |
| Documentation                 | To keep it clean, efficient, and simple, it will follow the Arc42 method and be deployed for anytime access. |
| Deployment                    | The project must be deployed whenever a release is made.                                                       |
| Testing                       | Ensure good unit test coverage (80%+) and acceptance testing covering all web app functionality.                |



