# CMPG323_Project2
#  NWUTechTrends Management System
## Overview
This project aims to develop a CRUD RESTful API that facilitates the management and analysis of telemetry data associated with automations created by NWU Tech Trends.
•	Capture Automation Performance: Record telemetry data whenever an automation runs, allowing stakeholders to assess its effectiveness in terms of time saved.
•	Cost Analysis: Associate time saved with a cost to calculate the cost savings achieved through automation.
•	Project & Client Insights: Group telemetry data by project and client, enabling stakeholders to analyse time and cost savings on a per-project or per-client basis.
•	Data-Driven Decision Making: Empower stakeholders to make informed decisions regarding

## This project comprises of two requirements as follows:
## Functional requirement
Implement a CRUD RESTful API with the following methods:
•	GET All: Retrieves all telemetry entries from the database.
•	GET by ID: Retrieves a specific telemetry entry based on its ID.
•	POST: Creates a new telemetry entry in the database.
•	PATCH: Updates an existing telemetry entry.
•	DELETE: Deletes an existing telemetry entry.
•	GET Savings (Project): Queries all telemetry per project, calculates cumulative time and cost saved, and filters data based on project ID and date range.
•	GET Savings (Client): Queries all telemetry per client, calculates cumulative time and cost saved, and filters data based on client ID and date range.

## Non-Functional requirement
•	Implementing authentication to restrict unauthorized access to the API.
•	Ensuring no sensitive credentials are stored on GitHub.
•	Deploying the API service to Azure with an F1 tier (free) service plan.
•	Securing and publishing the API on the Azure-hosted service.

## List of Endpoints for the NWU Tech Trends Telemetry Management API
GET Endpoints:
•	/api/telemetry: Retrieves all telemetry entries from the database.
•	/api/telemetry/{id}: Retrieves a specific telemetry entry based on its ID.
•	/api/telemetry/savings/project/{projectId}?startDate={startDate}&endDate={endDate}: Calculates cumulative time and cost saved for a project based on project ID and date range.
•	/api/telemetry/savings/client/{clientId}?startDate={startDate}&endDate={endDate}: Calculates cumulative time and cost saved for a client based on client ID and date range.
POST Endpoint:
•	/api/telemetry: Creates a new telemetry entry in the database.
PATCH Endpoint:
•	/api/telemetry/{id}: Updates an existing telemetry entry based on its ID.
DELETE Endpoint:
•	/api/telemetry/{id}: Deletes a specific tel

## Reference List
1. CMPG 323 -IT Developments. (2023) *Intro to APIs*. YouTube. Available at: https://youtu.be/-kaBMzOPiP0?si=QtBxY6v_4erUb9Is (Accessed: 30 August 2024).
2. CMPG 323 -IT Developments. (2023) *API controllers*. YouTube. Available at: https://youtu.be/kiSJGGy29fY?si=p4abUASnu51FYVR6 (Accessed: 30 August 2024).
3. CMPG 323 -IT Developments. (2023) * 17 Aug CMPG323 weekly virtual class Cloud, deploy API
*. YouTube. Available at: https://youtu.be/murThM9ATJA?si=NJBcFpQ7jxnrOqet (Accessed: 3 August 2024).
4. CMPG 323 -IT Developments. (2023) *Intro to APIs*. YouTube. Available at: https://youtu.be/-kaBMzOPiP0?si=QtBxY6v_4erUb9Is (Accessed: 5 August 2024).
5. CMPG 323 project 2-Asp.NET CORE WEB API 23 August 223. Accessed(9 August 2024).
6. OpenAI (2024) Ways to fix the errors in your existing code. Available at: (https://chatgpt.com/c/96b778e6-6845-438c-b59b-2a8b08fa6e07) (Accessed: 10 August 2024).
7. OpenAI (2024) How to fix the error in the user login. Available at: (https://chatgpt.com/c/96b778e6-6845-438c-b59b-2a8b08fa6e07) (Accessed: 11 August 2024).
8. OpenAI (2024) Ways to fix the errors in your existing code. Available at: (https://chatgpt.com/c/96b778e6-6845-438c-b59b-2a8b08fa6e07) (Accessed: 6 August 2024).

   # My pushed project is in code master

