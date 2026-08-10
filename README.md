# SISMED EXAMES

Portfolio presentation of a web-based system developed to support exam collection, specimen identification, label printing, and operational monitoring.

> **Notice:** this repository contains documentation and demonstration images only. The source code, database, and internal business rules are not publicly available.

## Overview

SISMED EXAMES was created to centralize operational activities related to exam collection, reduce manual controls, and improve the traceability of actions performed within the system.

## Key features

- Patient registration and search
- Collection registration and monitoring
- Exam selection and organization
- Label printing for different laboratories
- Operational reports
- Management dashboard
- Role-based access control
- Audit trail
- Session and login-attempt protection

## Technologies

- PHP 8
- MySQL
- HTML5 and CSS3
- JavaScript
- Apache
- Zebra BrowserPrint
- QZ Tray

## Security decisions

- Password hashing
- Prepared database statements
- CSRF protection
- Session and role-based access controls
- Audit logging
- Separation between demonstration and production environments
- Credentials kept outside the public repository
- Fully fictional demonstration data

## Gallery

Add screenshots without personal or sensitive information to `images/`. Suggested filenames:

| Screen | Suggested file |
| --- | --- |
| Login | `images/login.png` |
| Dashboard | `images/dashboard.png` |
| Collection | `images/collection.png` |
| Labels | `images/labels.png` |
| Report | `images/report.png` |

## Documentation

- [Architecture](docs/architecture.md)
- [Features](docs/features.md)
- [Security and privacy](docs/security.md)
- [Screenshot preparation guide](images/README.md)

## Live demo

[Open the SISMED EXAMES demonstration](https://ricmorsil.freedev.app/public/index.php)

> This environment is intended exclusively for project presentation. All displayed data is fictional. Demo credentials are provided privately when required.

## Author

Developed by **Richard Moreira**.

© 2026 Richard Moreira. All rights reserved.
