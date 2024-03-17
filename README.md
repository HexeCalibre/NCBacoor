# Developing Information Kiosk: An Innovative Project for Negosyo Center Bacoor

## Abstract 📝

This research paper explores the development of an innovative Information Kiosk tailored for the Bacoor City Livelihood and Development Office. Leveraging the capabilities of HTML (Hypertext Markup Language) and Bootstrap, the kiosk is specially designed for tablet devices, aiming to streamline and enhance various administrative processes related to business registration and development. The comprehensive content of the kiosk includes features such as DTI (Department of Trade and Industry) business name registration, renewal, certification requests, issuance of certified true copies, FAQs (Frequently Asked Questions), cancellation procedures, business territorial scope upgrades, business name reconsideration, and support for barangay micro-business enterprises.

The primary beneficiary of this Information Kiosk is the Bacoor City Livelihood and Development Office. By implementing this technological solution, the office aims to improve efficiency, reduce processing times, and provide more accessible and user-friendly services for businesses operating within the city. This research contributes to the field by showcasing a practical application of web technologies in a government setting, highlighting the potential impact of user-centric design and technology adoption for administrative processes. The findings of this study may serve as a valuable reference for similar initiatives in other local government units, fostering a more technology-driven and responsive public service landscape.

## Table of Contents 🌐

- [Developing Information Kiosk: An Innovative Project for Negosyo Center Bacoor](#developing-information-kiosk-an-innovative-project-for-negosyo-center-bacoor)
  - [Abstract 📝](#abstract-)
  - [Table of Contents 🌐](#table-of-contents-)
  - [Approval Sheet 📄](#approval-sheet-)
  - [Acknowledgement 🙏](#acknowledgement-)
  - [Dedication 🌟](#dedication-)
  - [Chapter 1: The Problem and Its Background 📚](#chapter-1-the-problem-and-its-background-)
    - [Introduction 🌱](#introduction-)
- [Chapter 1: The Problem and Its Background](#chapter-1-the-problem-and-its-background)
  - [1.1 Introduction](#11-introduction)
    - [Background of the Study 🌍](#background-of-the-study-)
  - [1.3 Statement of the Problem](#13-statement-of-the-problem)
    - [Statement of the Problem ❓](#statement-of-the-problem-)
      - [Main Problem](#main-problem)
      - [Specific Problem](#specific-problem)
    - [Objectives of the Study 🎯](#objectives-of-the-study-)
      - [Main Objective](#main-objective)
      - [Specific Objectives](#specific-objectives)
    - [Scope and Limitation 📌](#scope-and-limitation-)
      - [Scope of the Study](#scope-of-the-study)
      - [Limitations of the Study](#limitations-of-the-study)
    - [Theoretical Framework of the Study 🧠](#theoretical-framework-of-the-study-)
    - [Conceptual Framework of the Study 💡](#conceptual-framework-of-the-study-)
    - [Chapter 2: Review of Related Studies and Literature 📖](#chapter-2-review-of-related-studies-and-literature-)
      - [Related Literature 📖](#related-literature-)
      - [Synthesis 🔍](#synthesis-)
    - [Chapter 3: Research Methodology 📊](#chapter-3-research-methodology-)
      - [Program Design 🛠️](#program-design-️)
      - [Agile Model Implementation 🔄](#agile-model-implementation-)
      - [What is Agile?](#what-is-agile)
      - [Agile Vs Traditional SDLC Models](#agile-vs-traditional-sdlc-models)
      - [Agile Model - Pros and Cons](#agile-model---pros-and-cons)
      - [Agile Model Lifecycle Phases:](#agile-model-lifecycle-phases)
    - [Requirements Analysis 📋](#requirements-analysis-)
      - [1. Requirements Analysis for Business Name Registration Website:](#1-requirements-analysis-for-business-name-registration-website)
      - [2. Requirements Analysis for Information Kiosk Project:](#2-requirements-analysis-for-information-kiosk-project)
      - [Sitemap 🗺️](#sitemap-️)
      - [WireFrame 🗺️](#wireframe-️)
      - [Sequence Diagram of Existing and Proposed System 🔄](#sequence-diagram-of-existing-and-proposed-system-)
      - [Sequence Diagram of Existing System 🔄](#sequence-diagram-of-existing-system-)
    - [Sequence Diagram of Proposed System 🔄](#sequence-diagram-of-proposed-system-)
    - [Chapter 5: Summary, Conclusions, and Recommendations 📝](#chapter-5-summary-conclusions-and-recommendations-)
  - [List of Tables and Figures 📊📸](#list-of-tables-and-figures-)
  - [References 📚](#references-)
  - [Appendices 📑](#appendices-)

## Approval Sheet 📄

## Acknowledgement 🙏

I extend my deepest gratitude to all those who contributed to the successful completion of this research endeavor. Special thanks go to the Bacoor City Livelihood and Development Office for their invaluable support and cooperation throughout the project.

I appreciate the guidance and mentorship provided by [Name], whose expertise greatly enriched the development of the Information Kiosk. Sincere thanks also extend to [Name] for their insightful feedback and constructive suggestions that significantly enhanced the quality of this research.

Lastly, I am thankful for the unwavering support of my friends, whose encouragement and understanding have been instrumental in my academic pursuits.

This research would not have been possible without the collective efforts of everyone mentioned above. Your contributions are sincerely appreciated.

## Dedication 🌟

I dedicate this work to my Family, the Bacoor City Livelihood and Development Office Family whose unwavering love, support, and encouragement have been my anchor throughout this journey. Your belief in me has fueled my determination, and this accomplishment is as much yours as it is mine. Thank you for being my constant source of inspiration.

## Chapter 1: The Problem and Its Background 📚

### Introduction 🌱

In the ever-evolving landscape of public service, technology plays a pivotal role in reshaping efficiency and accessibility. This research introduces an Information Kiosk crafted for the Bacoor City Livelihood and Development Office, leveraging HTML and Bootstrap. This tablet-friendly solution addresses intricate administrative processes tied to business registration.

# Chapter 1: The Problem and Its Background

## 1.1 Introduction

The Negosyo Center faces challenges in client interactions, necessitating the need for an Information Kiosk. The overarching problem is the underutilization of a government-issued tablet.

### Background of the Study 🌍

The current state of Negosyo Center operations reveals inefficiencies, and the tablet underutilization exacerbates these issues. The proposed Information Kiosk aims to address these challenges.

## 1.3 Statement of the Problem

Challenges faced by the City Livelihood and Development Office and tablet underutilization contribute to inefficiencies. Addressing these problems is crucial for streamlined client interactions.

### Statement of the Problem ❓

#### Main Problem

Optimize client experience at the Negosyo Center through Information Kiosk implementation.

#### Specific Problem

1. Resolve tablet installation challenges.
2. Improve Negosyo Center efficiency.
3. Align with ARTA and ISO standards.

### Objectives of the Study 🎯

#### Main Objective

The primary objective of the Information Kiosk project is to optimize the client experience at the Negosyo Center by addressing the underutilization of the tablet and the inefficiency of posted materials. Through the seamless integration of technology, the goal is to establish an accessible and efficient platform that empowers clients with accurate information, reduces handling times, and minimizes uncertainty, thereby enhancing overall service delivery and satisfaction at the Bacoor City Livelihood Office.

#### Specific Objectives

- The tablet provided at the Negosyo Center is underutilized, leading to a missed opportunity in leveraging technology for effective information dissemination.
- Lack of active engagement with the tablet results in a failure to optimize its potential for addressing client inquiries and concerns.
- Traditional paper postings on the window are inefficient in communicating information to clients, contributing to prolonged handling times and client uncertainty.
- Ineffective communication through paper postings hinders the establishment of an optimal and seamless client-service interaction.
- The combined issues of underutilized technology and inefficient communication processes necessitate targeted interventions to enhance the overall client experience at the Bacoor City Livelihood Office.

### Scope and Limitation 📌

#### Scope of the Study

The study's potential impacts on Negosyo Center operations extend to providing valuable insights for similar initiatives.

- Technology Integration: Examination of the current state of tablet utilization and implementation of strategies for enhancing engagement and utilization.
- Communication Effectiveness: Evaluation of existing methods such as traditional paper postings and introduction of more efficient communication channels.
- User Experience Improvement: Analysis of the overall client experience considering factors such as accessibility, clarity, and responsiveness, followed by measures to enhance it.
- Operational Efficiency: Assessment of the impact of the Information Kiosk on overall efficiency and implementation of streamlined processes.

#### Limitations of the Study

In the pursuit of improving client-service interaction at the Negosyo Center through the Information Kiosk project, it is crucial to recognize several inherent limitations that may impact the study’s scope and applicability.

- Focus solely on the Bacoor City Livelihood Office restricts the generalizability of findings to other locations or contexts.
- Time constraints may limit the depth of the study, particularly in understanding long-term effects and sustainability.
- Resource limitations, both financial and human, might impact the extent of technology integration and the execution of large-scale awareness campaigns.
- Staff resistance or training gaps could affect the successful utilization of the Information Kiosk, influencing the overall project outcomes.
- Dependence on technology introduces the risk of technical issues or malfunctions, potentially disrupting the intended objectives.

Recognizing and addressing these limitations transparently will contribute to a more nuanced understanding of the study’s outcomes, facilitating informed decision-making and refining strategies for client-service improvement at the Negosyo Center.

### Theoretical Framework of the Study 🧠

The Information Kiosk project draws upon several theoretical foundations to guide its design, implementation, and analysis.

- **Technology Acceptance Model (TAM):** Guides the exploration of user attitudes, motivations, and behaviors towards the technology, ensuring its seamless integration into the client-service process.
- **Service Quality (SERVQUAL) Model:** Emphasizes the importance of service delivery in influencing customer satisfaction, guiding the assessment of factors such as accessibility, responsiveness, and accuracy.
- **Diffusion of Innovations Theory:** Guides the understanding of how new ideas or technologies are adopted and spread within a social system, helping tailor strategies for effective training, awareness promotion, and encouraging clients to engage with the new technology.
- **Human-Computer Interaction (HCI) Principles:** Ensure the Information Kiosk’s design aligns with user expectations and promotes a positive user experience, aiming to minimize user errors, enhance information accessibility, and foster user satisfaction.

**BJ Fogg's Behavior Model Application:**

| **BJ Fogg's Behavior Model Application** | **BJ Fogg's Behavior Grid** |
|-----------------------------------------|-----------------------------|
| ![BJ Fogg's Behavior Model Application](/public/documents/diagrams/Fogg-Behavior-Model.jpg)[Source](https://behaviormodel.org/wp-content/uploads/2020/08/Fogg-Behavior-Model.jpg) | ![BJ Fogg's Behavior Grid](/public/documents/diagrams/BJ%20Fogg%20Behavior%20Grid.png)[Source](https://behaviordesign.stanford.edu/sites/g/files/sbiybj23031/files/styles/responsive_large/public/media/image/foggbehaviorgrid_0.png?itok=ETiDs7gC) |

1. **Trigger:** Identify triggers that prompt users to interact with the Information Kiosk. Triggers can be external (e.g., signage, promotional materials) or internal (e.g., user needs, motivations).
2. **Ability:** Simplify the interaction process by ensuring the kiosk is easy to access and use. Design the interface with clear instructions, intuitive navigation, and minimal cognitive load to enhance user ability.
3. **Motivation:** Understand user motivations and tailor the kiosk's content and features to align with their needs and goals. Highlight benefits, incentives, or rewards for using the kiosk to increase motivation.

The overarching framework combines these theories, providing a comprehensive approach to address the underutilization of technology and inefficiency in communication at the Negosyo Center. By synthesizing these theoretical perspectives, the study aims to offer a robust foundation for the successful implementation and evaluation of the Information Kiosk project, with the ultimate goal of transforming and optimizing client service processes.

### Conceptual Framework of the Study 💡

| **Inputs**                               | **Processes**                                            | **Outputs**                           |
|------------------------------------------|----------------------------------------------------------|--------------------------------------|
| **Knowledge Requirements:**             | **Software Design and Development using Agile Model:**  | **Information Kiosk for Negosyo Center** |
| - HTML                                   | - Define the requirements for the project.               | - Implementation of the Information Kiosk system in Bacoor.  |
| - CSS                                    | - Design the user interface and visual elements.         |                                      |
| - Bootstrap                              | - Develop the software components using Agile methodology. |                                      |
| - Github                                 | - Test the functionality and performance of the system.  |                                      |
| - Git                                    | - Deploy the Information Kiosk for public use.           |                                      |
| - Vercel                                 | - Review and gather feedback for iterative improvements. |                                      |
| - Visual Studio Code                     | - Manage the project and codebase efficiently.           |                                      |
| **Software Requirements:**              | - Ensure compatibility with Android 10 and Firefox v123.0. |                                      |
| - Android 10                             |                                                          |                                      |
| - Firefox v123.0                         |                                                          |                                      |
| **Hardware Requirements:**              | - Select and procure the necessary hardware components.  |                                      |
| - Tablet                                 | - Install and mount the tablet for public access.        |                                      |
| - 10.1” Display                          | - Ensure the display size meets usability requirements.  |                                      |
| - Wall Mounting                          | - Securely attach the tablet to a suitable location.     |                                      |
| - Charger                                | - Provide power supply for continuous operation.         |                                      |
| - Wifi Router                            | - Enable internet connectivity for online functionality. |                                      |



### Chapter 2: Review of Related Studies and Literature 📖

#### Related Literature 📖

Eleanor D. Glor's study on key factors influencing innovation in government serves as a foundational piece in understanding the dynamics of innovation within public sector organizations. Glor's research explores the various factors that contribute to successful innovation initiatives in government, shedding light on critical aspects such as organizational culture, leadership support, resource allocation, and stakeholder engagement. By examining case studies and empirical evidence, Glor identifies key drivers and barriers to innovation, providing valuable insights for practitioners and policymakers seeking to foster innovation in government agencies.

#### Synthesis 🔍

Integrating Glor's study into the synthesis section allows for a comprehensive analysis of innovation in government and its implications for the development of the Information Kiosk project at the Bacoor City Livelihood and Development Office. By synthesizing Glor's findings with existing literature on technology adoption and organizational change, this section illuminates the contextual factors shaping innovation processes within government agencies. Furthermore, it underscores the importance of addressing institutional challenges and leveraging supportive frameworks to facilitate the successful implementation of innovative solutions, such as the Information Kiosk, in public service delivery.

### Chapter 3: Research Methodology 📊

#### Program Design 🛠️

#### Agile Model Implementation 🔄

![Agile Model](/public/documents/diagrams/Agile-software-Development-Life-Cycle-1.jpg)
[Source](https://bitbytesoft.com/wp-content/uploads/2022/01/Agile-software-Development-Life-Cycle-1.jpg)

The program design adopts the Agile Model to facilitate iterative development and responsiveness to changing requirements. Agile principles such as iterative planning, continuous feedback, and adaptive responses align with the dynamic nature of innovation initiatives, enabling rapid prototyping and experimentation. By embracing the Agile approach, the program design fosters a culture of collaboration, flexibility, and transparency, allowing stakeholders to actively participate in the development process and contribute to the evolution of the Information Kiosk project. This iterative methodology ensures that the kiosk's features and functionalities are aligned with user needs and organizational goals, maximizing its effectiveness and sustainability in addressing the challenges identified in Glor's study.

#### What is Agile?
https://www.tutorialspoint.com/sdlc/sdlc_agile_model.htm

Agile is an iterative approach to software development that emphasizes flexibility, collaboration, and customer feedback. It prioritizes delivering functional software in short, frequent cycles, allowing teams to respond to changing requirements and customer needs quickly.

#### Agile Vs Traditional SDLC Models

| **Agile Model**       | **Traditional SDLC Models** |
|-----------------------|-----------------------------|
| Emphasizes flexibility| Follows a linear approach   |
| Customer involvement   | Minimal customer involvement|
| Adaptive planning      | Detailed planning upfront   |
| Incremental delivery   | Delivery at the end of the project |
| Iterative development  | Sequential development phases |
| Continuous feedback    | Limited feedback until the end |

#### Agile Model - Pros and Cons

| **Pros**                           | **Cons**                                |
|------------------------------------|-----------------------------------------|
| Flexibility and adaptability       | Lack of predictability                  |
| Customer satisfaction              | Requires experienced team members       |
| Rapid response to changes          | Dependency on customer availability    |
| Early delivery of working software | Potential for scope creep               |
| Collaborative work environment     | Difficulty in measuring progress       |
| Continuous improvement             | Initial learning curve for stakeholders|

#### Agile Model Lifecycle Phases:

1. **Planning:** Involves identifying project scope, defining objectives, and setting priorities for the upcoming iteration.
   
2. **Requirements Analysis:** Collaboratively gathering and refining user stories, features, and functionalities required for the iteration.
   
3. **Design:** Creating the architecture, wireframes, and prototypes based on the gathered requirements.
   
4. **Coding:** Implementing the design and developing the features iteratively, typically in short cycles known as sprints.
   
5. **Unit Testing:** Conducting automated and manual tests to verify the functionality of individual components or units of code.
   
6. **Acceptance Testing:** Demonstrating the completed features to stakeholders and obtaining their feedback for validation and acceptance.

These phases are repeated iteratively throughout the Agile development process, with each iteration resulting in a potentially shippable increment of the product.

---

### Requirements Analysis 📋

The requirements analysis phase is pivotal in defining the scope and objectives of the project while considering the needs of stakeholders and adhering to regulatory standards. Below are the updated requirements analyses for both projects:

#### 1. Requirements Analysis for Business Name Registration Website:

**Functional Requirements:**

| Requirement               | Definition                                                                                                          |
|---------------------------|---------------------------------------------------------------------------------------------------------------------|
| Information Display       | Display registration-related information, including requirements, fees, and instructions, in an organized manner.   |
| Accordion Functionality  | Implement accordion components to streamline navigation through different sections of the website.                  |
| QR Code Integration      | Integrate QR codes to provide quick access to registration links and additional resources for users.                |
| Link Functionality        | Enable users to click on links within the content to access detailed information or external resources.           |

**Non-functional Requirements:**

| Requirement       | Definition                                                                                       |
|-------------------|--------------------------------------------------------------------------------------------------|
| Performance       | Ensure response time within 2 seconds for loading content and accordion sections for a smooth user experience. |
| User Interface   | Design a clear and concise layout with intuitive elements for easy comprehension of registration procedures. |
| Accessibility    | Ensure text readability, color contrast, and interactive elements are accessible for users with diverse needs. |
| Portability      | Guarantee compatibility and responsiveness across different screen sizes, especially on NC-Bacoor Tablets. |

**Technical Requirements:**

| Requirement         | Definition                                                                                                       |
|---------------------|------------------------------------------------------------------------------------------------------------------|
| HTML Structure      | Utilize semantic HTML tags and proper document structure for accessibility and search engine optimization (SEO). |
| Bootstrap Framework | Integrate Bootstrap CSS and JS for consistent styling and responsive design across various devices and screen sizes. |

**Regulatory and Compliance Requirements:**

| Requirement    | Definition                                                                                                     |
|----------------|----------------------------------------------------------------------------------------------------------------|
| Compliance     | Adhere to government regulations and standards for online registration processes and business operations.     |
| Data Security  | Implement secure data transmission protocols to safeguard user information during registration.                |

#### 2. Requirements Analysis for Information Kiosk Project:

**Functional Requirements:**

| Requirement         | Definition                                                                                                           |
|---------------------|----------------------------------------------------------------------------------------------------------------------|
| Information Display | Digitized display of relevant information on the kiosk screen, including services offered and relevant announcements. |
| Client Interaction  | Enable user input for inquiries, feedback submission, and navigation through the kiosk interface.                    |
| Feedback Mechanism | Provide a mechanism for collecting user feedback and suggestions to improve system functionality and user experience. |

**Non-functional Requirements:**

| Requirement      | Definition                                                                                   |
|------------------|----------------------------------------------------------------------------------------------|
| Performance      | Ensure response time within 2 seconds to ensure prompt interaction with the kiosk.             |
| Reliability      | Maintain an uptime of at least 99% to ensure uninterrupted availability of kiosk services.    |
| Maintainability  | Provide regular updates and documentation to facilitate ongoing maintenance and support.      |
| Portability      | Ensure easy relocation within the Negosyo Center premises for optimal placement and accessibility. |

**User Requirements:**

| Requirement             | Definition                                                                                       |
|-------------------------|--------------------------------------------------------------------------------------------------|
| User Interface Design   | Design an intuitive and user-friendly interface for easy navigation and interaction with the kiosk. |
| Content Presentation    | Present information clearly and concisely to facilitate understanding and decision-making for users. |
| Accessibility Features  | Include features such as text resizing and color contrast adjustments to accommodate diverse user needs. |

**Technical Requirements:**

| Requirement               | Definition                                                                                                           |
|---------------------------|----------------------------------------------------------------------------------------------------------------------|
| Hardware Specifications   | Utilize a government-issued tablet with specified hardware specifications for optimal performance.                    |
| Software Platforms        | Develop the kiosk application using HTML and Bootstrap CSS to ensure compatibility and responsiveness.               |
| Integration with Systems  | Integrate with existing systems for data retrieval and update to enhance the kiosk's functionality and utility.      |

**Regulatory and Compliance Requirements:**

| Requirement                 | Definition                                                                                                       |
|-----------------------------|------------------------------------------------------------------------------------------------------------------|
| Data Privacy Regulations    | Ensure compliance with data privacy regulations to protect the confidentiality and security of user data.         |
| Accessibility Guidelines    | Conform to accessibility guidelines to ensure equal access and usability for all users, including those with disabilities. |

#### Sitemap 🗺️

The sitemap provides a visual representation of the hierarchical structure and navigation flow of the website. It outlines the arrangement of pages or sections and their relationships, facilitating an understanding of the overall architecture and user journey.

![Sitemap](/public/documents/diagrams/Sitemap.png)[Source](https://octopus.do/fhe4eli9mi9)

The thorough analysis of requirements ensures alignment with project objectives and stakeholder expectations, ultimately leading to the successful implementation of both projects.

#### WireFrame 🗺️

---

**Program Flowchart of Existing and Proposed System** 🔄

In developing the program flowchart, Glor's study informs the identification of critical decision points and process dependencies inherent in innovation projects within government settings. By mapping out the flow of activities and interactions involved in implementing the Information Kiosk, this flowchart integrates Glor's insights into the practical realities of navigating bureaucratic structures and mobilizing support for innovation initiatives. Additionally, it highlights the iterative nature of the innovation process, emphasizing the need for continuous evaluation and adaptation based on stakeholder feedback and evolving organizational needs.

#### Sequence Diagram of Existing and Proposed System 🔄

In developing the sequence diagrams, Glor's study informs the identification of critical decision points and process dependencies inherent in innovation projects within government settings. By mapping out the flow of activities and interactions involved in implementing the Information Kiosk, these diagrams integrate Glor's insights into the practical realities of navigating bureaucratic structures and mobilizing support for innovation initiatives. Additionally, they highlight the iterative nature of the innovation process, emphasizing the need for continuous evaluation and adaptation based on stakeholder feedback and evolving organizational needs.

#### Sequence Diagram of Existing System 🔄

![Traditional Sequence Diagram](/public/documents/diagrams/Traditional%20Sequence%20Diagram.png) [Source](https://www.mermaidchart.com/app/projects/5eb3b288-88ab-41fc-b2ee-1a99aa0fbe3d/diagrams/5e409bf9-3373-4378-b185-17a1ed4882a4/version/v0.1/edit)

**Description:**
The sequence diagram for the existing system depicts the current sequence of interactions between different system participants, including clients or MSMEs, receptionists, and DTI tellers. It illustrates the steps involved in client interaction, query forwarding, information provision, and logout procedures within the Negosyo Center. This diagram serves as a representation of the existing process and forms the basis for comparison with the proposed system.

### Sequence Diagram of Proposed System 🔄

![Proposed Sequence Diagram](/public/documents/diagrams/Proposed%20Sequence%20Diagram.png) [Source](https://www.mermaidchart.com/raw/52d32843-420d-42e6-a0f2-bab78f8adc6e?theme=dark&version=v0.1&format=svg)

**Description:**
The sequence diagram for the proposed system outlines the envisaged sequence of interactions following the implementation of the Information Kiosk and associated process enhancements. It introduces new steps, such as client self-assistance using the Information Kiosk, streamlined query handling, and improved communication between receptionists and DTI tellers. This diagram represents the anticipated changes and improvements in the client-service interaction process, reflecting the objectives of the Information Kiosk project.



---

### Chapter 5: Summary, Conclusions, and Recommendations 📝

In the concluding chapter, Glor's study serves as a touchstone for reflecting on the broader implications of the Information Kiosk project and offering recommendations for future research and practice. By synthesizing the key findings from Glor's research with the project's outcomes and lessons learned, this section underscores the significance of addressing systemic barriers to innovation in government and advocating for a culture of experimentation and learning. Furthermore, it provides actionable recommendations for sustaining the momentum of innovation beyond the initial implementation phase, drawing on Glor's insights into the importance of leadership support, capacity building, and stakeholder engagement.
## List of Tables and Figures 📊📸

## References 📚

- Glor, E. D. (2001). Key factors influencing innovation in government. The Innovation Journal: The Public Sector Innovation Journal, 6(2).
- Tutorialspoint. (n.d.). Agile model. Retrieved March 3, 2024, from https://www.tutorialspoint.com/sdlc/sdlc_agile_model.html


## Appendices 📑
