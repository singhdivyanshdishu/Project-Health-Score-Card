# Project Health Score Card

This repository contains the Power BI dashboard for visualizing project construction details. The dashboard provides a comprehensive overview of project health, including the number of projects, budget, expenses, and the status of various projects.

## Dashboard Overview

![image](https://github.com/user-attachments/assets/a57cc752-72bf-4d0b-ae28-881d238ec1ea)


The dashboard includes the following sections:

- **Count of Project by Location**: A map visual showing the distribution of projects across different locations.
- **Project Metrics**: Key metrics including the number of projects, total budget, total expenses, and average project progress.
- **Project Status**: A pie chart displaying the count of projects by their status (In Progress, Completed, Planned, On Hold, Cancelled).
- **Project Type and Priority**: A bar chart showing the count of projects by type and priority level.
- **Project Details**: A table listing detailed information about each project, including project name, manager, start date, end date, completion percentage, and budget.
- **Budget and Expense by Project Manager**: A bar chart comparing the budget and expenses managed by each project manager.

## Data Loading and Transformation

The data for this dashboard was loaded from an Excel file. The following transformations were applied:

1. **Date Format Correction**: Ensured all date fields were in a consistent format.
2. **Null Value Correction**: Handled missing or null values in the dataset.

## How to Use

1. Clone this repository to your local machine:
    ```bash
    git clone https://github.com/yourusername/project-health-score-card.git
    ```

2. Open the Power BI Desktop and load the dataset from the `data` folder.

3. Apply the necessary transformations as described above.

4. Import the visuals and configure the dashboard layout as per the provided screenshot.

5. Alternatively, you can download and view the Power BI dashboard directly from the following OneDrive link:
    [Download Project Health Dashboard](https://onedrive.live.com/?authkey=%21AApQ1ZiG3PUDFbc&cid=DEA2EF3ACD24C00C&id=DEA2EF3ACD24C00C%2126042&parId=DEA2EF3ACD24C00C%2126041&o=OneUp) 

## Repository Structure

project-health-score-card/<br>
├──> data/<br>
│   └──> project_data.xlsx<br>
├──> images/<br>
│   └──> dashboard_screenshot.png<br>
└──> README.md<br>


