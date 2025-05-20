# Resource Allocation Tracker

This repository contains `resource_allocation_tracker.csv`, a resource tracking spreadsheet designed for visualisation in Power BI. The data reflects the allocation of people (resources) to products on a weekly basis. Each row in the CSV specifies a resource’s weekly allocation percentage to a given product, including start and end dates, product and resource details, and any relevant notes.

## What is `resource_allocation_tracker.csv`?

- **Purpose:**  
  Tracks how developers and other resources are assigned to different products, projects, or initiatives each week throughout the year.
- **Usage:**  
  The CSV is used as a data source for Power BI dashboards, enabling reporting and analysis of team/product allocations over time.

### Key columns:
- `ResourceID`, `ResourceName`, `ResourceType`: Who is being allocated.
- `ProductID`, `ProductName`: Where their allocation is going.
- `Year`, `Week`, `StartDate`, `EndDate`: The time window for the allocation.
- `AllocationPercentage`: Percentage of a resource’s time allocated.
- `Notes`: Any additional context, such as split allocations or notes on duration.

## How to Update the File

You have two options to keep this file up-to-date:

### 1. Manual Edits

- Open `resource_allocation_tracker.csv` in your preferred spreadsheet tool (Excel, Google Sheets, etc.) or a text editor.
- Add, modify, or remove rows as needed.
- Commit and push your changes back to the repository.

### 2. Use GitHub Copilot

You can leverage GitHub Copilot’s chat and code suggestion capabilities to update this tracker efficiently:

- **Example queries:**  
    - “Add 100% allocation for Jane Doe to Product X for weeks 10–15.”  
    - “Split Alex’s allocation 50/50 between Product A and Product B starting week 20.”  
    - “Remove all allocation rows for resource R009.”
- Copilot can generate the necessary CSV row(s) or batch modifications for you.  
- To use Copilot Chat, simply ask your question (as in the examples above), and Copilot will suggest the precise changes or even update the file automatically if you use Copilot in your development environment.

> **Tip:** When using Copilot, be specific about the resource, product, percentage, and week(s) to ensure accurate updates.

## Visualising the Data

- Import `resource_allocation_tracker.csv` into Power BI or any compatible BI tool.
- Build dashboards to visualise weekly allocations, resource utilisation, or product staffing over time.

## Contribution Guidelines

- Ensure new rows follow the existing column structure.
- Use consistent naming for resources and products.
- When splitting allocations, ensure the sum for a resource per week does not exceed 100%.
- Add helpful notes for any non-obvious allocations (e.g., temporary splits, transitions).

---

Feel free to use GitHub Copilot as your assistant to automate and streamline updates to this tracker!
