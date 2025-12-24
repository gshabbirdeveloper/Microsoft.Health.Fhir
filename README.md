# FHIR Server for Azure (Customized Fork)

A modern **.NET Core implementation of the HL7 FHIR standard**, optimized for cloud-native healthcare applications.

---

## 🚀 Overview
The **FHIR Server for Azure** is an open-source project designed to make clinical health data interoperable across systems. Built on the HL7 **Fast Healthcare Interoperability Resources (FHIR)** specification, this server provides developers with a rapid way to deploy, manage, and extend FHIR services in the cloud.

Key goals:
- Enable fast deployment of a compliant FHIR service.
- Provide a foundation for custom healthcare applications.
- Support interoperability, security, and scalability in the Microsoft ecosystem.

---

## 🏗️ Architecture
The server is built with logical separation to maximize flexibility:

- **Hosting Layer** – Supports multiple environments with configurable IoC containers.  
- **RESTful API Layer** – Implements HL7 FHIR APIs.  
- **Core Logic Layer** – Encapsulates FHIR business logic.  
- **Persistence Layer** – Pluggable storage providers; includes ready-to-use support for **Azure Cosmos DB** and **SQL Server**.

---

## 🔑 Features
- **Role-Based Access Control (RBAC)** via Azure Active Directory.  
- **Bulk Export** for large-scale data operations.  
- **Data Conversion ($convert-data)** into FHIR format.  
- **FHIR Proxy** for secure gateway access.  
- **SMART on FHIR support** for app integration.  
- **Compliance-ready** for Protected Health Information (PHI).  

---

## 📚 Documentation
- **Quickstart Guides**: Deploy via Portal, CLI, or PowerShell.  
- **Schema Migration**: Upgrade SQL schemas with ease.  
- **Authentication & Roles**: Configure RBAC and client apps.  
- **Search Implementation**: Learn how queries are handled.  
- **Debugging**: Step-by-step guide using Visual Studio.  

---

## 🛠️ Managed Azure Offerings
This open-source project powers two managed services:
- **Azure API for FHIR** (GA)  
- **Azure Healthcare APIs** (includes FHIR + DICOM in one workspace)  

---

## 🤝 Contributing
We welcome community contributions!  
Ways to help:
- Submit bugs and fixes.  
- Review and improve source code.  
- Share feedback and feature requests.  
- Join discussions on StackOverflow or Twitter (#fhirforazure).  

This project follows the **Microsoft Open Source Code of Conduct**.  


👉 This updated version is **shorter, cleaner, and more GitHub-friendly** than the original. It highlights architecture, features, and contribution guidelines without overwhelming detail.

Would you like me to **also show you how to rename the project and update the README file directly inside VS Code step by step** (starting with editing `README.md`), or keep this as a standalone text you can paste?
