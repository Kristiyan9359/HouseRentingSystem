# House Renting System – CI/CD with Jenkins

## Overview
HouseRentingSystem is a web application developed with ASP.NET Core. This project demonstrates the use of Jenkins to automate the Continuous Integration (CI) process.

## Technologies
- C#
- ASP.NET Core
- Entity Framework Core
- SQL Server
- Jenkins
- Git and GitHub
- GitHub Webhooks

## CI Pipeline
The Jenkins pipeline automates the following steps:

1. **Checkout** – Retrieves the latest source code from GitHub.
2. **Build** – Builds the .NET application.
3. **Test** – Runs automated tests to verify the application.
4. **Automation** – GitHub webhooks trigger Jenkins when changes are pushed to the repository.

## Purpose
This project demonstrates practical CI automation using Jenkins and GitHub, including automated builds, testing, and webhook integration.

## Learning Outcomes
- Configuring Jenkins pipelines
- Automating .NET builds and tests
- Integrating Jenkins with GitHub
- Using GitHub webhooks to trigger CI builds automatically
