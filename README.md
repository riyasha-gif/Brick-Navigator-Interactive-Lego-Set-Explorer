# Brick-Navigator-Interactive-Lego-Set-Explorer:
![Screenshot](https://github.com/riyasha-gif/Brick-Navigator-Interactive-Lego-Set-Explorer/blob/main/Screeshot.png)
# Overview:
Brick Navigator is a data-driven project built entirely in Power BI to solve a common problem for Lego collectors:set discovery paralysis..The tool transforms a massive dataset of Lego sets into an interactive, intuitive user interface, allowing collectors to efficiently narrow down their search criteria based on key variables like price, theme, and age range.

# Key Features:
Dynamic Filtering:
Utilize slicers for Theme Group, Theme, and Age Range to quickly filter the dataset.

Drag-and-Drop Price Parameter: 
An interactive parameter allows users to dynamically adjust the maximum price ceiling for their search.

KPI Summary:
Instant visibility into key metrics via KPI cards, including Total Sets, Average Pieces, and Average Price.

Single-Set Detail View: 
Clicking on a single set in the main table populates a dedicated detail area, displaying its Name, Picture (Image), Price, Year, Avg Pieces, and Age. Note: This view is intentionally limited to single selection.

Visual Tooltips: 
Hovering over any set in the table displays the set's picture using a custom tooltip page.

Advanced Decomposition Tree: 
A dedicated navigation page featuring a Decomposition Tree that analyzes the structure of Total Sets across Category, Theme Group, and Name.

# Power BI Skills Demonstrated:

Data Transformation (Power Query):

Cleanup of raw CSVs, removal of null/empty rows, data type conversions, and creation of calculated columns (Age Range, Price Range).

Data Modeling & DAX: 

Creation of explicit measures for KPI cards (Total Sets, Avg Pieces, Avg Price).

UX/UI Design: 

Implementation of dynamic interactions, single-select visualizations, and action buttons for navigation (Bookmarks).

Advanced Visualization:

Utilization of the Decomposition Tree for hierarchical analysis and custom Tooltip Reports for image display.

Interactive Components:

Use of Parameters (What-If Analysis) for the dynamic Price Range filter.







Navigation & Reset: Built-in buttons for seamless navigation to the Decomposition Tree and a "Clear All Filters" button implemented using Power BI Bookmarks.



