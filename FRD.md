# Functional Requirements Document (FRD) for Negosyo Center Bacoor Information Kiosk 🛠️

## 1. Introduction:

The Functional Requirements Document outlines the detailed functionalities and features of the Information Kiosk Digitization Project. This document serves as a reference for developers, designers, and stakeholders to understand the specific requirements of the system.

## 2. User Stories:

### 2. MSMEs Interaction:

- As MSME representatives, we want to easily access information on DTI services.
  - The system should provide a clear and user-friendly interface.
  - The DTI services section should have a clickable button leading to relevant information.

- As MSMEs, we want a seamless experience navigating through the kiosk.
  - The navigation buttons should be intuitive and labeled appropriately.
  - Users should be able to return to the main menu from any section.
  - [Future Enhancement] As MSMEs, we want breadcrumbs functionality to track our navigation path.

- As MSMEs, we want to access the citizen charter conveniently.
  - The Citizen Charter button should open a modal with a zoomable HTML object.
  - Users should be able to zoom in and out for better readability.

## 3. System Requirements:

### 3.1 Hardware Requirements:

- A wall-mounted Android 10 tablet with the specified specifications.
- The tablet should have sufficient battery life for daily operation.
- Ensure the tablet is securely enclosed to prevent damage.

### 3.2 Software Requirements:

- The kiosk application should be compatible with Mozilla Firefox.
- Utilize HTML and Bootstrap CSS with a responsive design suitable for a government-issued tablet.

### 3.3 Offline Functionality (Future Enhancement):

- Future migration to React Native for locally installed app and enhanced offline functionality.

## 4. User Interface (UI) Design:

- Follow a clean and modern design for the kiosk interface.
- Buttons for different sections should be clearly visible and labeled.
- Implement a responsive design tailored for the government-issued tablet.
- [Future Enhancement] Include breadcrumbs for users to track their navigation.

## 5. Interactions:

### 5.1 Button Interactions:

- Buttons should have a click/tap interaction.
- Visual feedback (e.g., color change) upon interaction.

### 5.2 Modal Interactions:

- The Citizen Charter modal should open and close smoothly.
- Enable zoom functionality within the modal for the HTML object.

## 6. Security:

- Implement basic measures to ensure the physical security of the tablet.
  - Securely mount the tablet to prevent theft or tampering.

## 7. Testing:

- Conduct thorough testing for all functionalities.
- Include unit testing, integration testing, and user acceptance testing.

## 8. Future Enhancements:

- Consider migrating the project to React for improved maintainability.
- Explore React Native for offline functionality, enabling local installation.
- [Future Enhancement] Add breadcrumbs functionality to enhance user navigation.

## 9. Revision History:

- Version 1.0 (Initial Draft)
  - [Date]

## 10. Approval:

This FRD is subject to approval by Negosyo Center Bacoor and Bacoor City Livelihood Office representatives.

## 11. Project Contact:

For further information, contact Ritz Carl Feliciano at rc.feliciano013097@gmail.com.

**Note:** This document provides a high-level overview of functional requirements and may require further detailing during the development phase.
