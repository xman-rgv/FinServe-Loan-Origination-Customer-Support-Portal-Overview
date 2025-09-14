# Phase 2 – Salesforce Org Setup

## Project Overview
This repository documents the configuration of a Salesforce Developer Org for the FinServe Loan Origination & Customer Support Portal. The goal is to build a scalable solution for managing loan applications, server infrastructure, and customer interactions.

## Custom Object: Server
A custom object named `Server` was created to track infrastructure details relevant to the FinServe platform.

### Fields Added:
- `Server_Name` (Text)
- `IP_Address` (Text)
- `Location` (Picklist)
- `Status` (Picklist)
- `Installation_Date` (Date)
- `Is_Virtual` (Checkbox)

## Tabs
- A custom tab was created for the `Server` object to make it accessible via the app navigation.

## Access Control
- A permission set named `Server Access` was created.
- Object-level permissions (Read, Create, Edit, Delete) were granted.
- Specific users were assigned to this permission set for controlled access.

## App Configuration
- A Lightning App was created to group relevant tabs and provide a unified interface for users.
- Navigation items include the `Server` tab and other components as needed.

## Documentation
All setup steps are documented with screenshots located in the `/Phase2_Salesforce_Setup/` folder:
- Dashboard after login
- App creation
- Custom object setup
- Fields added
- Tabs created

## Notes
Use the App Launcher (grid icon) to access the custom app and verify tab visibility and object functionality.

