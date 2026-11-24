# SmartCare — Assumptions, Constraints & Risks

As part of my Software Project Management course, I assessed what it would take to deliver SmartCare, a proposed platform for patients navigating a medical process. This document records the assumptions behind the plan, the constraints on delivery, and the risks I identified together with their potential impact and planned mitigation.

[Assumptions](#assumptions) · [Constraints](#constraints) · [Risks](#risks) · [Risk Map](#risk-map)

## Assumptions

| No. | Assumption | Confidence | Lead Time | Impact | Priority |
|---:|---|---:|---:|---:|---:|
| 1 | The development team has the technical skills to implement complex integrations. | 70% | 1 | 4 | 9 |
| 2 | Enough people with the required skills will be assigned to meet the project objectives and schedule. | 65% | 1 | 4 | 9 |
| 3 | Project managers will monitor and report progress closely enough to detect schedule deviations early. | 80% | 1 | 3 | 6 |
| 4 | Development environments, tools, cloud services, and databases will remain available throughout the project. | 60% | 2 | 4 | 8 |
| 5 | Development team members will cooperate and communicate openly. | 75% | 1 | 3 | 7 |
| 6 | Management and the client will make decisions and grant approvals without delay. | 55% | 1 | 3 | 8 |
| 7 | Scope and requirements will remain stable once development begins. | 45% | 2 | 4 | 10 |
| 8 | The system architecture will remain substantially unchanged once development begins. | 55% | 2 | 4 | 9 |
| 9 | Infrastructure, environments, and supporting systems will remain free of exceptional incidents that would materially disrupt development. | 70% | 2 | 4 | 7 |
| 10 | The development, test, and production environments will be fully compatible, helping prevent environment-related failures. | 60% | 2 | 4 | 9 |

## Constraints

| No. | Constraint | Category |
|---:|---|---|
| 1 | Project management and development must follow Scrum and Kanban practices. | Work process |
| 2 | The system must meet strict information security and medical privacy standards. | Information security and regulatory compliance |
| 3 | Management and Finance must formally approve the project before implementation and development can begin. | Project approval |
| 4 | Spending must stay within the budget approved in the business plan. | Budget |
| 5 | Development can begin only once enough qualified staff have been assigned to meet the schedule, launch date, and specification. | Resource allocation and staffing |
| 6 | The development environment may use only fictitious patient data. It must have no access to real patient records. | Regulatory compliance and data privacy |
| 7 | The interface must use the health plan’s UI components to maintain its visual identity. | UI design and organizational policy |
| 8 | The minimum viable product must be completed and launched within 12 months of project approval. | Schedule |
| 9 | Infrastructure and cloud services must be purchased from approved vendors with authorization from Procurement. | Procurement |
| 10 | Open-source software requires approval from the organization’s cybersecurity department before use. | Information security |

## Risks

| No. | Risk | Potential Project Impact | Planned Mitigation |
|---:|---|---|---|
| 1 | Difficulty integrating SmartCare with the health plan’s core systems and databases. | Development and rollout could face substantial delays.<br>The system could struggle to display real-time data, reducing product quality.<br>Poorer code quality could make future changes, updates, and features harder to deliver. | Specify all interfaces in detail early in the project.<br>Plan incremental integration tests from the start of development.<br>Prioritize the connections needed for the minimum viable product. |
| 2 | Inaccurate estimates for development, testing, and rollout could put the launch date at risk. | Launch could be delayed.<br>Keeping the team on the project longer could raise costs.<br>Health-plan management could lose confidence in the project. | Build contingency time into the schedule.<br>Review progress regularly to catch delays early.<br>Reprioritize and reduce scope if a critical delay occurs. |
| 3 | Underestimating development, integration, testing, and rollout costs could lead to a budget overrun. | Features may have to be cut.<br>Development could stop if funding runs out.<br>Expected profitability could decline. | Track spending regularly with Finance.<br>Set aside a reserve for unexpected costs.<br>Adjust scope if a significant overrun emerges. |
| 4 | Physicians or health-plan members may resist using the system. | Low usage could prevent the project from meeting its objectives.<br>The health plan’s return on investment could fall.<br>Repeated training and costly interface changes may be needed after launch. | Involve users during requirements definition to understand their needs.<br>Run an awareness campaign on social media and in clinics.<br>Provide guidance and ongoing user support. |
| 5 | Sensitive medical data could be exposed in breach of privacy requirements. | The exposure could seriously harm patient privacy and the health plan’s reputation.<br>The organization could face costly lawsuits and regulatory fines.<br>Enforcement authorities could halt the project immediately. | Define strict security requirements and implement strong access controls.<br>Test security before each release.<br>Establish a procedure for responding quickly to security incidents. |
| 6 | The team may lack the technical experience, skills, or knowledge the project requires. | Code quality could decline and defects could increase.<br>Complex technical objectives may be difficult to meet.<br>The learning curve could slow development substantially. | Provide targeted technical training at project kickoff.<br>Recruit specialists or arrange expert support for complex work.<br>Use code reviews to maintain quality. |
| 7 | Staffing may be insufficient to meet project objectives. | Existing staff could face overload and burnout.<br>Critical tasks could slip and deadlines could be missed.<br>Morale could fall and more staff could leave. | Plan workloads and identify critical tasks.<br>Prioritize work accordingly.<br>Consider temporary staff or subcontractors when needed. |
| 8 | Development or test environments or cloud tools may be unavailable. | Development and testing could stop entirely.<br>The team could be unable to integrate components or verify behavior under real operating conditions.<br>The project schedule could slip. | Set up development, test, and production environments early.<br>Coordinate regularly with IT to prevent technical issues.<br>Maintain servers and tools throughout the project. |
| 9 | The client and development teams may have difficulty working together. | Missing operational information could lead to poor decisions.<br>Essential approvals could be delayed.<br>The product could fall short of the client’s expectations. | Appoint a consistent, available client contact.<br>Hold weekly progress meetings.<br>Review deliverables with the client against the business requirements. |
| 10 | An inaccurate specification may require changes to the system. | Rework could consume time and money.<br>The project could exceed its original budget and schedule.<br>Changing requirements could divert the team’s attention. | Have all relevant stakeholders review and approve the specification.<br>Work in short stages so corrections and improvements can be made quickly.<br>Establish a change management process. |

## Risk Map

Each entry gives the risk number from the table above and its overall rank in the original assessment. Rank 1 is the highest priority.

| Severity ↓ / Likelihood → | Low | Low–medium | Medium | Medium–high | High |
|---|---|---|---|---|---|
| Extreme | — | — | Risk 5 (rank 1) | — | Risk 1 (rank 2) |
| High | — | — | Risk 4 (rank 6) | Risk 3 (rank 5) | Risk 10 (rank 3)<br>Risk 2 (rank 4) |
| Medium–high | — | — | Risk 9 (rank 7)<br>Risk 7 (rank 8)<br>Risk 6 (rank 9) | — | — |
| Medium | — | Risk 8 (rank 10) | — | — | — |
| Low | — | — | — | — | — |
