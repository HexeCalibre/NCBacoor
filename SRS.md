# System Requirements Specification (SRS) Document

## 1. Introduction

### 1.1 Purpose

The purpose of this Software Requirements Specification (SRS) document is to outline the requirements for the development of the Information Kiosk project at Negosyo Center Bacoor, focusing on both the tablet hardware specifications and the software features.

### 1.2 Document Conventions

- **Bold Text**: Indicates headings and emphasized information.
- `Code Text`: Represents code snippets or technical terms.
- *Italic Text*: Denotes placeholders or variable information.

### 1.3 Intended Audience

This document is intended for developers, project managers, stakeholders, and any other individuals involved in the development and implementation of the Information Kiosk project.

### 1.4 Project Scope

The Information Kiosk project aims to optimize client experience at the Negosyo Center by digitizing and displaying information on a tablet. It includes features for information display, client interaction, and feedback collection.

### 1.5 References

- [Government Issued Tablet Specifications]
- [Negosyo Center Operational Guidelines]
- [ISO Cleanliness Standards]

## 2. Overall Description

### 2.1 Product Perspective

The Information Kiosk will function as a standalone system within the Negosyo Center, interacting with users to provide information on business transactions and procedures.

### 2.2 Product Features

- **Information Display**: Digitized display of relevant information.
- **Client Interaction**: User input for inquiries and feedback.
- **Feedback Mechanism**: Collection of user feedback for system improvement.

### 2.3 User Classes and Characteristics

Users include clients of the Negosyo Center, who may vary in technological proficiency but share a common need for information regarding business transactions.

### 2.4 Operating Environment

The Information Kiosk will operate within the Negosyo Center premises, utilizing a government-issued tablet and connecting to the center's network infrastructure.

### 2.5 Design and Implementation Constraints

- Compliance with ISO cleanliness standards.
- Intuitive and user-friendly interface design.

### 2.6 User Documentation

User documentation will be provided to guide clients on how to interact with the Information Kiosk.

### 2.7 Assumptions & Dependencies

- Availability of stable network connectivity within the Negosyo Center premises.
- Compliance with government regulations and standards.

## 3. System Features and Requirements

### 3.1 Functional Requirements

1. **Information Display**:
   - Display digitized information on the tablet screen.
   - Update information dynamically based on user input.
2. **Client Interaction**:
   - Accept user inquiries and provide relevant responses.
   - Facilitate user feedback submission.
3. **Feedback Mechanism**:
   - Collect user feedback and suggestions for system improvement.
   - Provide options for users to rate their experience.

### 3.2 External Interface Requirements

- **User Interface**: Intuitive touch-based interface for easy navigation.
- **Software Interface**: Integration with existing systems for data retrieval and update.
- **Hardware Interface**: Interaction with the government-issued tablet for display and input.
- **Communication Interface**: Connectivity with the Negosyo Center's network for data exchange.

### 3.3 Conditions Necessary for Product to Run

- Stable network connectivity.
- Proper installation and configuration of the Information Kiosk software.
- Availability of power source for the tablet.

### 3.4 Non-functional Requirements

- **Performance**: Response time within 2 seconds.
- **Security**: User authentication and data encryption.
- **Reliability**: Uptime of at least 99%.
- **Maintainability**: Regular updates and documentation.
- **Portability**: Easy relocation within the Negosyo Center premises.

## 4. Diagrams and Models

### 4.1 Context Diagram

![Context Diagram](link-to-context-diagram.png)

### 4.2 Functional Decomposition

- Information Kiosk System
  - Information Display Module
  - Client Interaction Module
  - Feedback Mechanism Module

### 4.3 Use Case Diagram

![Use Case Diagram](link-to-use-case-diagram.png)

### 4.4 Sequence Diagram

![Sequence Diagram](link-to-sequence-diagram.png)

### 4.5 As-Is and To-Be Process Model

- **As-Is**: Manual information dissemination and client interaction.
- **To-Be**: Digitized information display and interactive client engagement.

### 4.6 User Stories

1. As a client, I want to easily access information on business transactions.
2. As a staff member, I want to collect user feedback for system improvement.

### 4.7 Mind Map

- Information Kiosk
  - Features
    - Information Display
    - Client Interaction
    - Feedback Mechanism
  - Requirements
    - Functional
    - Non-functional
  - Diagrams and Models

## 5. Tablet Specifications

### 5.1 Brand and Model

- **Brand:** Cherry Mobile
- **Model:** Aqua Tab Pro
- **Color:** Black

### 5.2 Asset Information

- **Property Tag:** Mambog III
- **Control Number:** 014-2024
- **Serial Number:** 357665077196672

### 5.3 Technical Specifications

- **Operating System:** Android 10
- **Processor:** Octa-core (1.6GHz + 1.2GHz)
- **Storage:** 64GB ROM
- **RAM:** 4GB
- **Display:** 10.1 inches
- **Wireless Connectivity:** WLAN 802.11 b/g/n
- **Battery Capacity:** 5000mAh

## 6. Software Details

### 6.1 Deployment

- **Website:** [nc-bacoor.vercel.app](https://nc-bacoor.vercel.app)
- **Folder Size:** 11.7MB
- **Number of Files:** 341
- **Number of Folders:** 178
- **Technologies Used:** HTML, Bootstrap
- **Deployment Platform:** Vercel

## 7. Kiosk Features

### 7.1 User Interface Elements

- **Buttons**: The kiosk interface includes buttons for various services such as FAQ, Registration, Renewal, Other Services, Contact Us, and Citizen Charter.
- **QR Code Integration**: QR codes are used for services like Registration, Renewal, Certification, and Feedback. Users can scan these codes to proceed to the respective websites or forms.
- **Accordion Layout**: The Other Services page employs a Bootstrap accordion layout to display detailed information categorically.
- **Modal Windows**: Contact Us and Citizen Charter features are implemented using modal windows for a user-friendly interaction experience.

### 7.2 Content

The content of the kiosk includes information on services provided by the Department of Trade and Industry (DTI), compliance with the Anti-Red Tape Act (ARTA), and ISO 9001:2015 standards.
- **DTI Services**: Information about DTI services is provided, with redirection to relevant websites for detailed service descriptions.
- **Citizen Charter**: The Citizen Charter, compliant with ARTA and ISO 9001:2015, is accessible through the kiosk. It is presented in a modal window using the HTML `<object>` element, allowing users to zoom in and out.

## 8. Conclusion

The Information Kiosk at Negosyo Center Bacoor is equipped with a variety of features such as buttons, QR code integration, accordion layout, and modal windows to enhance user interaction. The content focuses on providing information about DTI services and the Citizen Charter in compliance with ARTA and ISO 9001:2015 standards. The combination of hardware specifications and software features ensures an effective and user-friendly kiosk system.
