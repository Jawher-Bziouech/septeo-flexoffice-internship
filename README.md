# FlexOffice — Septeo Internship Case Study

> Portfolio case study of a full-stack application developed during my software engineering internship at Septeo.  
> This repository intentionally does **not** contain Septeo's original source code, internal configuration, infrastructure addresses, credentials, or customer data.

## Overview

FlexOffice is a workplace resource and reservation management application. During my internship, I worked on a full-stack .NET / Angular codebase involving resource management, reservations and planning, authentication and authorization, and business-oriented REST APIs.

This repository documents the technical experience and architecture without publishing company-owned code.

## Technologies

### Backend
- ASP.NET Core
- C#
- REST APIs
- Entity Framework Core
- CQRS / MediatR
- FluentValidation
- JWT authentication
- Role-based authorization
- Swagger / OpenAPI

### Frontend
- Angular
- TypeScript
- Responsive web interfaces
- Planning and reservation workflows
- Drag-and-drop interactions

### Engineering & tooling
- Layered / Clean Architecture principles
- Dependency injection
- Database migrations
- Git
- Docker

## Functional Scope

The application included business concepts such as:

- users and roles;
- companies and locations;
- workplace resources;
- reservations;
- availability and planning;
- authentication and authorization;
- administrative and operational workflows.

## Architecture

The backend follows a separation-of-concerns approach inspired by Clean Architecture.

```text
Angular Frontend
       |
       | HTTP / REST
       v
ASP.NET Core API
       |
       +--> Application layer
       |      +--> Commands
       |      +--> Queries
       |      +--> Validation
       |
       +--> Domain / business models
       |
       +--> Infrastructure
              +--> Entity Framework Core
              +--> Persistence
              +--> External services
```

CQRS-style commands and queries with MediatR help separate write and read operations, while validation and persistence concerns remain isolated from the API layer.

## What I Worked On

My internship work gave me practical experience with:

- developing and maintaining ASP.NET Core REST endpoints;
- structuring backend features using CQRS and MediatR;
- validating application requests with FluentValidation;
- working with Entity Framework Core and database migrations;
- implementing JWT-based authentication and role management;
- developing Angular interfaces connected to backend APIs;
- working on planning and reservation-oriented user experiences;
- navigating and contributing to an existing professional codebase.

## What This Repository Contains

This is a **case-study repository**, not a copy of the company's project.

It is intended to show recruiters and developers the technologies, architectural concepts, and engineering work involved in the internship while respecting the confidentiality and ownership of the original codebase.

## Confidentiality

The original internship project contained company-specific configuration and infrastructure information. Those materials are deliberately excluded from this public repository.

No Septeo source code, internal URLs, credentials, customer data, or private configuration is published here.

## Internship

**Company:** Septeo  
**Role:** Full Stack .NET & Angular Developer Intern  
**Period:** July–August 2025

## Author

**Jaouhar Bziouech**  
Software Engineering student — ESPRIT  
M2 Data Science in Business — PST&B
