# Power BI Demo

This repository is a Power BI demonstration project illustrating core reporting, data modeling, and dashboard features using real-world sample data.

## Features

- Interactive dashboards with multiple visual types
- Power Query data transformation steps
- DAX measures and calculated columns
- Guidance for publishing to Power BI Service

## Getting Started

1. Download and install [Power BI Desktop](https://powerbi.microsoft.com/desktop).
2. Clone this repository.
3. Open `PowerBI_Demo.pbix` in Power BI Desktop.
4. Preview different report tabs and explore datasets.

## File Structure

- `/data`: Datasets
- `/assets`: Images used in visuals
- `PowerBI_Demo.pbix`: Power BI report file
- `/docs`: Extended documentation

ower BI Beginner Activity: Guided Hands-On Homework
This activity will walk you through the core steps demonstrated in the "Microsoft Power BI for Beginners – 2 Hour Power BI Crash Course!" video by Simon Sez IT. You will learn to import data, prepare it for analysis, create a data model, build computations, and design interactive reports. Complete each step using the video for reference, but do not skip ahead to answers. Document your work and be prepared to share screenshots and short explanations.

### Instructions
Use Power BI Desktop (latest version recommended).

Use the sample data provided with the video or similar datasets (CSV/Excel with sales, locations, products, etc.).

Work through each section sequentially.

Do not enter or copy any solution from the video—focus on understanding the process.

Write down your steps, screenshots, and reflections for each activity section.

### 1. Introduction and Setup
Briefly describe what Power BI is and list some potential use cases.

Download and install Power BI Desktop.

Explore the main interface: identify and briefly describe the three primary views in Power BI Desktop.

### 2. Importing and Preparing Data
Import all CSV or Excel files from a specified folder into Power BI.

List the files you imported.

Open Power Query Editor.

Identify and remove at least two unnecessary columns from one dataset.

Find a column that needs formatting (e.g., numbers as text or dates as text); perform the correct data type transformation.

Split one column containing compound data (e.g., city and state together) into two separate columns.

### 3. Building Lookup Tables and Preparing Relationships
From your data, create a lookup (dimension) table for either products, locations, or another category.

Remove duplicates to ensure only unique values remain.

Add an index column to this table for use as a unique identifier.

Merge (join) the main sales or transactions table with a lookup table to bring in unique IDs.

Remove any redundant columns resulting from this process.

### 4. Modeling Data and Relationships
Switch to Model view.

Create one-to-many relationships between your main table and your lookup tables using corresponding keys.

Draw or list the relationships you created.

### 5. Adding Calculations with DAX
Create a Dates table using a DAX formula (do not use pre-built date tables).

Add columns for year and month.

In your main table, add a calculated column that represents something important (e.g., revenue as unit price × quantity).

Create one DAX measure (e.g., total sales, average quantity, etc.) and explain in your own words what it calculates.

Organize your measures into a dedicated table or section for easy access.

### 6. Designing a Power BI Report
Create a report page.

Add at least three different types of visuals (e.g., card, bar chart, line chart, table, etc.).

Add report elements: a title, a text box for instructions, and a simple company logo or image.

Use formatting tools to improve the look of your visuals.

### 7. Adding Interactivity
Add a slicer to your report for one field (e.g., product, year, or location).

Create bookmarks or navigation buttons to switch between two different report pages.

Set up interactive filters, so visuals update based on the slicer or selection.

### 8. Publishing (Optional/Advanced)
Attempt to publish your report to Power BI Service (online).

If you can, take note of any requirements (such as an institutional or Office 365 account).

Explore the dashboard feature and pin at least one visual as a tile.

Submission Checklist
For each step, include:

Written summary of actions taken.

Screenshots of your Power BI interface where possible.

Any observations, difficulties, or reflections.

Omit all direct answers (no DAX code or exact values).

Attach your .pbix file if submitting digitally.

Tip: Focus on process and understanding, not perfect answers. Reference the video only to clarify steps, not for solutions. Be ready to discuss your workflow and any areas you found challenging.
