# OrangeHRM Admin Module Automation

This project is a TestNG-based Selenium automation framework for testing the **Admin module** of the OrangeHRM application.

## Tech Stack

- **Language**: Java  
- **Automation Framework**: Selenium WebDriver  
- **Testing Framework**: TestNG  
- **Build Tool**: Maven  
- **IDE**: Eclipse  
- **Tested On**: OrangeHRM local instance (installed using XAMPP)

## Project Structure

OrangeHRM_Automation/
│
├── src/
│ ├── main/
│ │ └── java/
│ │ └── com/orangehrm/
│ │ ├── pages/ # Page Object Model classes
│ │ └── utils/ # Reusable utility classes
│ └── test/
│ └── java/
│ └── com/orangehrm/tests/ # Test classes
│
├── testng.xml # TestNG suite configuration
├── pom.xml # Maven dependencies and project config
└── .classpath, .project, .settings/ # Eclipse IDE configuration files


## Features Automated

- Login functionality
- Admin module access and interactions
- Form input and dropdown handling using utility methods

## How to Run

1. **Install Dependencies**  
   Run the following command to download Maven dependencies:
   ```bash
   mvn clean install

**Author** - Amey Pakhare
