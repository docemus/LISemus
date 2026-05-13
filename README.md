# LISemus - Laboratory Information System

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![Project Status: Documentation Phase](https://img.shields.io/badge/Status-Documentation_Phase-orange.svg)]()

This repository contains the design, technical specifications, and functional requirements for the **LISemus (Laboratory Information System)** project. The system is designed to manage complex laboratory workflows, from patient registration to diagnostic reporting and specialized services.

## Overview

**LISemus** is an open-source Laboratory Information System (LIS) designed to support modern clinical laboratories, with particular attention to healthcare facilities operating in low-resource contexts.

The project aims to improve the quality, traceability, safety, and efficiency of laboratory diagnostic workflows by providing a modular, interoperable, and standards-oriented software platform.

LISemus is conceived as a progressive and sustainable system: it starts from a Minimum Viable Product (MVP) focused on the essential end-to-end diagnostic workflow and evolves through additional modules and functional extensions.

## Vision

Our vision is to make reliable laboratory diagnostics more accessible through an open-source, sustainable, and adaptable LIS platform.

LISemus is intended to help laboratories move from paper-based or fragmented workflows to structured digital processes, supporting better clinical decisions, safer patient care, and stronger laboratory governance.

## Mission

The mission of LISemus is to provide a modern, open-source LIS that helps clinical laboratories:

- manage patient requests, samples, examinations, results, and reports;
- ensure end-to-end traceability of the diagnostic process;
- reduce transcription errors and data loss;
- support standardized and high-quality reporting;
- improve interoperability with hospital systems and laboratory analyzers;
- promote compliance with internationally recognized laboratory quality principles, including ISO 15189;
- remain sustainable and adaptable in different healthcare environments.

## Documentation Roadmap (LIS Series)
The project documentation is structured into five main series (LIS 1 to LIS 5). The current status is as follows:

| Document ID | Description | Status | Reference |
| :--- | :--- | :--- | :--- |
| **LIS 1** | System Architecture & High-Level Design | **Baselined** | Frozen |
| **LIS 2** | Data Model & Schema Specifications | **Baselined** | Frozen |
| **LIS 3** | Functional Requirements Mapping (rev. 4.1) | **Baselined** | Frozen |
| **LIS 4** | Technical Implementation Specs | **In Progress** | Phased |
| **LIS 5** | Integration & Quality Assurance Plan | **In Progress** | Phased |


> [!NOTE]
> **Technical documentation is currently in Italian to ensure clinical precision** and alignment with local healthcare regulations. English translations are part of our roadmap and will be released alongside the first stable modules.
> 

## MVP & Phased Development Strategy
The project follows an **MVP (Minimum Viable Product)** methodology. Functional requirements documented in LIS 4 and LIS 5 are being developed in stages based on the priority matrix defined in `LIS 3`.

### 1. Core Functionalities (MVP Scope)
Focuses on essential features required for the system's initial launch. This includes:

* **Patient Intake:** Basic registration and ID management.
* **Order Management:** Request validation and tracking.
* **Reporting:** Core diagnostic workflows and result delivery.

### 2. Extended Functionalities (Post-MVP)
Advanced features designed to optimize and scale the system, including:

* **Advanced Integration:** High-level synchronization with external HIS/EMR systems.
* **Specialized Domains:** Comprehensive modules for specific areas (e.g., Blood Bank/Transfusional Services - Ambito 21).
* **Audit & Resiliency:** Advanced audit trails and system-wide data protection.

