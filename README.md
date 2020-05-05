# Bahmni-Insurance-Connect 
A java application/service for integration with OpenIMIS (Insurance Management System)
 - Gateway for communication between OpenIMIS system and Bahmni components like openmrs, odoo
 - FHIR Client for handling FHIR resources communication between OpenIMIS and Bahmni
 - FHIR resources construction for insurance related stuffs like claim, eligibility coverage etc.

## Build
 - ``mvn clean packages deploy``
 - Generates rpm and packaged jar
 
## Deployment 
 - Install the generated rpm on top of existing Bahmni installed platform (works only from Bahmni 0.92 )
 - Configure the application.properties file: add necessary credentials and urls (`/etc/insurance-integration/insurance-integration.properties`)

