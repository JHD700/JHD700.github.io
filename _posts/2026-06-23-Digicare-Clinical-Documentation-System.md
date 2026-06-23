---
title: FullStack - DigiCare Clinical Documentation 
description: Commissioned FullStack Webapp
date: 2026-06-23 11:33:00 +0800
categories: [Projects, ASP.NET]
tags: [project, webapp, api, asp.net]
---

> This project is still currently `under development` and may contain outdated information.
{: .prompt-warning }

> The documentation will soon include `video demonstration` and an `ERD Diagram`.
{: .prompt-info }

## Overview
The webapp was commissioned for a thesis proposal and intended to digitize patient documentation. The platform facilitates secure, real-time collaboration on patient records with customizeable groups. By centralizing data, the system enables seamless communication between student clinicians, instructors, and professors to grade submissions and ensure clinical records consistently adhere to institutional standards.

## Key Features

* **Google Authentication**
    * Implements a secure OAuth 2.0 flow for isolated identity management.
* **RBAC & Permissions**
    * Utilizes a custom token-minting service to enforce role-based access control.
* **RESTful API**
    * Features a robust ASP.NET Core backend architecture for efficient data exchange.

---

## Technology Stack

| Layer | Tools & Technologies |
| :--- | :--- |
| **Backend** | ASP.NET Core, EF Core, AutoMapper, Dependency Injection |
| **Identity** | Firebase Auth, Custom JWT Token Minting |
| **Frontend** | React, TypeScript, Vite, React Router, Shadcn/UI, TailwindCSS |
| **Database** | MySQL |


## Project Team

| Member Name           | Role                                   | Profile                                             |
| :-------------------- | :------------------------------------- | --------------------------------------------------: |
| **Sydney Rejano**     | Frontend Engineer + Frontend Architect | [Linkedin](https://www.linkedin.com/in/sydrjn/)     |
| **Josh Esquivel**     | API & Database Architect               | [Linkedin](https://www.linkedin.com/in/jhesquivel/) |

## Document Roadmap
- [ ] Media
  - [ ] Video Demo
  - [ ] Images
  - [ ] ERD
- [ ] Backend
  - [ ] API Documentation
- [ ] Project Management
  - [ ] Functional Requirements
  - [ ] List of Features and Descriptions