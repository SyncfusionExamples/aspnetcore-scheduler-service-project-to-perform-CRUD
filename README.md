# Service-project-to-perform-CRUD-operations-on-Syncfusion-Scheduler

Repository Description: A backend service providing REST CRUD endpoints for Syncfusion Scheduler events.

Project Overview

Small web service exposing REST endpoints and an Entity Framework model backed by the included MDF database.

Features

- RESTful CRUD endpoints for scheduler events
- Entity Framework model with local `.mdf` database

Prerequisites

- Visual Studio
- .NET Framework 4.5
- LocalDB or SQL Server to attach `App_Data\ScheduleData.mdf`

Installation & Usage

Open the solution, restore NuGet packages, build and run. Endpoints are provided by `EventDatasController` for Scheduler integration.

Documentation

General Syncfusion Documentation: https://help.syncfusion.com/

ASP.NET MVC Syncfusion Guides (relevant to this project):

- Introduction: https://ej2.syncfusion.com/aspnetmvc/documentation/introduction
- Schedule Component: https://ej2.syncfusion.com/aspnetmvc/documentation/schedule/getting-started

Contributing

Open issues or pull requests for fixes or improvements.

License

Verify Syncfusion licensing before production use.
