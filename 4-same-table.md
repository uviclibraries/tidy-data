---
layout: default
title: 4 Multiple Types of Observational Units are Stored in the Same Table
nav_order: 2
parent: Workshop Activities
---

# Multiple Types of Observational Units are Stored in the Same Table
### Tidy Data Rule(s) Broken: Each type of observational unit forms a table
<br>
<mark>Select the "should-be-multiple" table from the left pane.</mark>
<br><br>

This table holds course descriptions and professor's  Google Scholar citation statistics. These are 2 observations although they do have the "professor" in common.

### DUPLICATE THE TABLE:

1. In the left pane, right click on the "should-be-multiple" query. Select **Duplicate from the drop-down menu**

<details>
<summary>Click for Navigation help</summary>
<img src="images\should-be-multiple-duplicate.gif"> 
</details>

### DELETE COLUMNS:
1. In the original "should-be-multiple" table. Select all the columns that are related to citations (other than the professor). To do so hold *CTRL* (Windows) or *Command* (Mac) and click on the headers. If the columns are highlighted, they are selected.

2. On the **Home** tab in the **Manage Columns** section, click **Remove Columns**

<details>
<summary>Click for Navigation help</summary>
<img src="images\should-be-multiple-delete-citation.gif"> 
</details>

### RENAME TABLE:
1. To differentiate your new table from the other one, name it to identify the observation (eg. "Courses")

<details>
<summary>Click for Navigation help</summary>
<img src="images\should-be-multiple-rename-courses.gif"> 
</details>

### DELETE COLUMNS IN OTHER TABLE:

1. Switch to the "should-be-multiple (2)" table.
2.  Select all the columns that are related to courses (other than the professor). To do so hold *CTRL* (Windows) or *Command* (Mac) and click on the headers. If the columns are highlighted, they are selected.
3. On the **Home** tab in the **Manage Columns** section, click **Remove Columns**

<details>
<summary>Click for Navigation help</summary>
<img src="images\should-be-multiple-delete-courses.gif"> 
</details>

### REMOVE DUPLICATES:

1. Now you have repeated rows. To delete repeats, right click on the header "Professor" and select **Remove Duplicates**  

<details>
<summary>Click for Navigation help</summary>
<img src="images\should-be-multiple-delete-duplicates.gif"> 
</details>

### RENAME TABLE IN OTHER TABLE:
1. To differentiate your new table from the other one, name it to identify the observation (eg. "Google Scholar Citations")

[NEXT STEP: Should be in the Same Table](5-multiple-tables.md){: .btn .btn-blue }