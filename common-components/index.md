---
category: Components
expires: 2020-01-01
---

# Common Components
Common components are software or technical systems that are created once and reused many times in different services or business contexts. They could be applications, data, integration, a network, security products, hosting. They are building blocks, typically mapped to a business or technical capability, which can be used to deliver modular services or systems of a higher order.

__Key characteristics__

Common components can be of any size but they all share the same characteristics:
1. They are designed according to common standards, principles and patterns, with independent quality assurance to ensure the principles and patterns have been applied.
2. They are designed and developed in a modular, scalable and resilient way to support ease of reuse and reliability.
3. They are mapped to a specific business or technical capability/service. This enables easy search and prevents duplication.
4. They are treated as an asset and therefore require asset lifecycle management – support wrap, continuous improvement, enhancement or replacement.
5. They are standalone but interoperable with other common components, such that change to one does not cause a ripple effect change to others.
6. test

## Why should we use common components? ##

The adoption of common components can bring significant benefits to DfE. Some of these benefits are:
- __Speed to market__ – reuse can save time to build, test and deliver services. We should not have to build services from scratch every time.
- __Reduced costs__ – the more we can reuse, the more we can save through reduced technical diversity or duplication, enabling us to focus our efforts on the differentiating or innovative aspects of the service.
- __Lower risk__ – building to common standards and through lifecycle management lowers the risk of failure.

## What's available? ##

Domain | Component | Owner | Status
- | - | - | -
End User Compute | Outlook and Teams | Leanna Green | Live
| Telephony and Skype | Leanna Green | Live
| Mobile telephony | Leanna Green | Live
Hosting | [Cloud Infrastructure Platform (CIP)](https://educationgovuk.sharepoint.com/sites/ciog/groupdelivery/Home.aspx) | Saghir Akbar | Live
Security & networks | [DfE Sign-in](#dfe-signin) | Leanna Green | Live
| Core network | Jon Gilbert | Live
Service Management | Service desk toolset | Leanna Green | Live
Integration | [Enterprise API Management (EAPIM)](#eapim) | Saghir Akbar | Beta
Information & data | SharePoint | Harj Bilan | Live
| Enterprise Data and Analytics Platform (EDAP) | Harj Bilan | Live
| Data collection | Harj Bilan | Live
| Postcode lookup | Harj Bilan | Discovery
| Geospatial / maps | Harj Bilan | Discovery
Applications | Shared Customer Relationship Management (CRM) platform | Saghir Akbar | Beta
| 360 customer view | Saghir Akbar | Alpha
| Marketing Automation platform | tbc | Discovery
| Robotic Process Automation (RPA) platform | tbc | Alpha

_(Note. the following sections are placeholders, content to be developed)_

<a name="dfe-signin"></a>
### 1. DfE Sign-in
DfE Sign-in is the new way for users to access DfE online services and has now replaced Secure Access.

__Documentation__

- _Links to tech docs, onboarding info_

__Support__

- _Questions regarding adoption and use_
- _Where to go if there's a problem_

__Roadmap__

- _Who's already using this component - see ['Services accessed using DfE Sign-in'](https://services.signin.education.gov.uk/)_
- _What's being onboarded_

__Further guidance__

- _Who creates / maintains this content (support email)_

<a name="eapim"></a>
### 2. Enterprise API Management platform

The enterprise integration and API management platform provides a single place to host and manage APIs.

The solution offers a range of features that make it easy to publish APIs and share data, including automated on-boarding, tested global policy controls, portal customisation, identity and access management support, and flexible subscription management.

Key platform features include:
1.	Developer portal that enables developers to quickly find and reuse existing APIs – making it easy to exchange data between systems.
2.	Templates that introduce a standard way of publishing APIs.
3.	API Gateway that manages security policies and access management.
4.	Integration middleware APIs to share data between multiple systems.
5.	Central support reduces the cost of maintaining APIs.

EAPIM has been developed using Microsoft Azure’s API gateway, and the solution is deployed within the new CIP hosting platform.


__Documentation__

Read the Operating Model for more information about the solution design, security, availability, support and governance. If you need access to this document contact Matt Morgan.  

__Support__

The service is supported internally by a central team within CIPS.

To report an issue with the service, contact the service desk; the team are available from 08:00 – 22:00 hrs Monday to Friday, excluding English public holidays.  

__Roadmap__

Over the next 18 months, the ETS team are evolving the solution in three key areas:
•	Implementing enhancements to the API platform and integration middleware  
•	Driving adoption On-boarding more APIs onto the platform
	Promoting re-use of integration middleware
•	Convergence
	Platform capability and adoption roadmaps converge on DFEAAP (Single Access point from multiple client channels (internal/external) Mobile, Web and Desktop

__Further guidance__
Contact Sarfraz Malik to find out more about this solution.

## Further guidance ##

For more information on common components or to discuss adding your component to the repository, contact the [Architecture team](mailto:architecture.governance@education.gov.uk)
