---
title: Changelog
author: nugroho
description: An information about changelog. 
ysi.author: nugroho
ysi.custom: nugroho
ysi.date: 02/19/2020
uid: changelog
---
### Unreleased

**1.2.0** - _2020-03-27_

#### Added

* Application Settings for **Notification, SMS, Email** and **Default Organization**
* _Busines to Customes_ **B2C** Identity Provider for **Google** and **Facebook**
* **IdProo Agent** for Active Directory (AD)
* Synchronization target to Directory Hubs
* Multiple users properties from Synchronization
* CSS and Javascript **Skeleton**
* Add IdP, DirectoryId and Status (Active or Inactive) in DB user Identity
* Webhook in application, also devide in section model and HTTP request

#### Changed

* Improve dashboard application
* Improve security access for login and application
* Improve Login Identity from **External data Provider**
* Add new user properties **directoryId** and **providerId**
* Fix typo for label
* Improve query and display data
* Rename surename and givenname to firstname and lastname
* Improve CSS and layouting for (List, Form, Table)
* Improve reset password
* Improve market place

#### Removed

*   Section "System" in configuration

### Released

**1.0.0** - _2020-01-30_

#### Added

* **IdProo** as more than Single Sign On **(SSO)** Applications
* **Dashboard** information **"Summary"** for **Users, Login, Application and Activities**
* Drill-down **users** activities in dashboard
* ##### 
    <noscript>Users</noscript>
    in organizations
    * Manage data users in IdProo such as: **Add, Edit, Detail, Delete (Hard & Soft)**
    * Enable and disable user in details
    * Lock and unlock, relate in every Identity Provider **(IdP)**
*   ##### **Applications** registred in IdProo

    *   Add new application client for Web **(Hybrid, SPA), Mobile, Desktop**
    *   Manage application properties such as: **Branding, Authentications, Clients secret, API Permissions, Expose an API, Application Role and Owner**
    *   Management **webhooks** for application
*   ##### **Directory Hubs** for _Active Directory_ and _Azure Active Directory_ **(B2B)** Busines to Busines Identity Provider

    *   Manage directory _AD or AAD_ and allow user login from every directory
    *   Synchronization data user _AD or AAD_ to IdProo
*   **Position** Permanents, Temporaries, Functionals and Adhocs
*   **Synchronization** Users data from **HR** to **IdProo** and set as database. You can set connection from **MSSQL, MySQL, Postgree** and **Oracle**
*   **Master Data** Access Menu, Audit Logs, Announcement, Group Access, Functionals and Organization Units
*   ##### Market Place

    *   List application registred in IdProo
*   **Rest password** user IdProo from IdP (AD and AAD)
*   Portal SSO
