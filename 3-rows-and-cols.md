---
layout: default
title: 3 Variables are Stored in Both Rows and Columns
nav_order: 2
parent: Workshop Activities
---

# Variables are Stored in Both Rows and Columns
### Tidy Data Rule(s) Broken: Each variable forms a column, and Each observation forms a row

Select the "cols-and-rows" table from the left pane.

### ADJUST HEADERS:

1. Sometimes Power Query does not automatically detect that the table has headers. Click on the little table icon on the top left-hand corner of your data table. Select "Use First Row as Headers" from the dropdown menu.

<details>
<summary>Click for Navigation help</summary>
<img src="images\cols-and-rows-promote-header.gif"> 
</details>

### UNPIVOT COLUMNS:

Several of the headers in this table are dates. Dates are a value which can be stored under a column header called "Date" or similar depending on the observation

1. Select all the columns with dates as headers. To so this you may either 
    1. Selecting all columns by pressing *CTRL A* (for Windows) or *Command A* (for Mac) and unselecting the "librarian" and "Measure" by holding down *CTRL* or *Command* and clicking on the headers.
    2. OR hold down *CTRL* or *Command* and click on all the headers.
2. All of the date headers should now be highlighted. Right click on any of the highlighted headers. From the drop-down, select *unpivot columns*.

<details>
<summary>Click for Navigation help</summary>
<img src="images\cols-and-rows-unpivot-cols.gif"> 
</details>

### PIVOT COLUMN:

The "Measure" column is different appointment variables for Librarian Reference. Thses should be headers instead whose values are currently in the column "Value".

1. Select the "Measure" column by clicking on the header. The column should now be highlighted.
2. In the top pane, navigate to the **Transform** column. In the **Any Column** section select **Pivot Column**. 
3. In the **Pivot Column** window, select "value" from the drop down menu. These are the values that will be under the new headers.

<details>
<summary>Click for Navigation help</summary>
<img src="images\cols-and-rows-pivot-measures.gif"> 
</details>

### RENAME AND CHANGE TYPE:
1. The column that holds the dates is still called "Attribute". Change the name to "Date" by double clicking on the header.

<details>
<summary>Click for Navigation help</summary>
<img src="images\cols-and-rows-rename-change-type.gif"> 
</details>

[NEXT STEP: Should be Multiple Tables](4-same-table.md){: .btn .btn-blue }