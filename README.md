## Auto Enable External Modules From Project Template

Self service for auto-enabling External Modules from a project template along with the module's configuration setting values .

### Getting started
The module doesn't require any configuration at the project level. Its only function it to assign the modules enabled on the project template onto this newly created project. The module must be enabled globally so it can automatically enable modules on a project created from a project template. In fact, the former is the recommended use-case.
The auto enabling of modules takes place on the Project Setup page (landing page of creating a project from a project template).

### How it works
Once enabled on a project, it detects whether the project was created from a project template, and if it was, then it checks if the project template currently contains enabled external modules, and if so it assigns their configuration to the project. Then the Auto Enable module hides itself from the list of enabled modules on the project. The process only takes places once and only during the first 3-minutes of creating the project. It is this time-window that protects old projects from being added external modules (and their configuration) if they were built from a project template.

### For posterity
This module was designed as a response to the COVID pandemic of 2020 as part of MGB's custom solution for remote eConsent. Its goal was to streamline and reduce the time-to-production for projects implementing remote eConsent. It was released internally on 3/2020 and released to the REDCap consortium on 7/2021.

#### Comments, questions, or concerns, please contact:
Ed Morales at EMORALES@BWH.HARVARD.EDU

© 2021 Mass General Brigham (formerly Partners HealthCare, Inc). All Rights Reserved.