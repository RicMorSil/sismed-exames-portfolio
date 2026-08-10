# 💉 SISMED EXAMES

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

<p>
  <img src="https://img.shields.io/badge/PHP-8%2B-777BB4?style=for-the-badge&logo=php&logoColor=white" alt="PHP 8+">
  <img src="https://img.shields.io/badge/MySQL-8.0%2B-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL">
  <img src="https://img.shields.io/badge/HTML5-WEB-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-STYLING-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-ES6%2B-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/Apache-WEB_SERVER-D22128?style=for-the-badge&logo=apache&logoColor=white" alt="Apache">
  <img src="https://img.shields.io/badge/Zebra_BrowserPrint-LABEL_PRINTING-000000?style=for-the-badge" alt="Zebra BrowserPrint">
  <img src="https://img.shields.io/badge/QZ_Tray-LABEL_PRINTING-228B22?style=for-the-badge" alt="QZ Tray">
</p>

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

## 🚀 Live demo
[![Open the SISMED EXAMES demonstration](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://ricmorsil.freedev.app/public/index.php)

> ⚠️ This environment is intended exclusively for project presentation. All displayed data is fictional. Demo credentials are provided privately when required.

## Author

Developed by **[Richard Moreira](https://github.com/RicMorSil).**
© 2026 Richard Moreira. All rights reserved.
