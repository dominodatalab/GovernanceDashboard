# Governance Dashboard
A comprehensive dashboard to oversee governance activities in your Domino deployment.

This is an example of a dashboard to oversee Governance in your Domino deployment. 
<img width="1682" alt="image" src="https://github.com/user-attachments/assets/7f118e3f-288e-41db-8a08-2d57f152cfc2" />

## Overview

The Governance Dashboard provides a centralized interface to monitor and manage governance-related artifacts and processes within a Domino deployment. It helps track registered models, pending governance tasks, policy adoption status, and details of governance bundles across projects.

## Features

1. **Summary Metrics**: View high-level statistics such as the total number of registered models, outstanding governance tasks, and active governance bundles.
2. **Policy Adoption Lifecycle**: Visualize how policies are being adopted, including their current stage (e.g., draft, review, approved, deprecated) and progress metrics.
3. **Governance Bundle Details**: Drill down into each governance bundle to see metadata, associated policies, owners, and status.
4. **Registered Models List**: List and filter all registered models, with key attributes (e.g., version, owner, date registered, associated governance status).
5. **Project Bundles Overview**: Display all governance bundles organized per project, enabling quick navigation and status checks.
6. **Interactive Filters **: Filter models, bundles, and tasks for efficient oversight.

## Prerequisites

- **API_HOST**: URL to a Domino deployment.
- **API_KEY**: Valid API tokens to query governance-related endpoints.

## Usage
Configure app.py with the correct API_Host and API_Key. Create a project and create an application (Deployments > Apps). Make sure both app.sh and app.py are in your project repository. 
