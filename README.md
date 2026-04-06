# SAP RAP Flight Management Application

This repository contains my SAP ABAP and RAP learning project built in Eclipse ADT on SAP BTP ABAP Environment.

## Project Overview
I built a Flight Management application using the SAP RESTful Application Programming Model (RAP). The project includes backend data modeling, business logic, validations, service exposure, and a generated Fiori Elements user interface.

## Main Technical Components
- Custom database table: `ZAFFLIGHT`
- Root CDS view: `ZR_AFFLIGHT`
- Projection CDS view: `ZC_AFFLIGHT`
- Behavior implementation: RAP business object with validations
- OData V4 service binding
- Fiori Elements preview application

## Implemented Features
- Created and filled a custom flight table with sample data
- Generated RAP business object and service artifacts
- Implemented validation for:
  - Flight price must be greater than zero
  - Currency code must be valid
- Adjusted UI behavior:
  - Removed create/delete where required
  - Made selected fields read-only
  - Added value help for currency
  - Hid technical/admin fields

## Packages
- `ZS4D400_AF`
- `ZS4D400_AF_RAP`

## Tools Used
- SAP Eclipse ADT
- SAP BTP ABAP Environment
- RAP
- CDS View Entities
- EML
- OData V4
- Fiori Elements
- abapGit
- GitHub

## Learning Outcomes
This project helped me practice:
- ABAP object-oriented development
- CDS data modeling
- RAP behavior definitions and implementations
- EML-based data modification
- Service generation and UI preview
- GitHub integration with abapGit

## Status
Working project successfully pushed to GitHub and previewed through generated Fiori Elements UI.
