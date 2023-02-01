---
layout: default
title: 5 A Single Observational Unit is Stored in Multiple Tables
nav_order: 2
parent: Workshop Activities
---

# A single Observational Unit is Stored in Multiple Tables
### Tidy Data Rule(s) Broken: Each type of observational unit forms a table
<br>

Take a look at all the tables with "multiple-tables" in their name. Notice that they all have the same variables (headers) and observational units (student mental health)? These tables are separated by date the survey was taken, however, date is a **variable**, not an **observational unit**.
<br><br>
<mark>1. Select the "multiple-tables-1" table from the left pane.</mark>
<br><br>

### APPEND TABLES:

1. On the **Home** tab in **combine** section, click the arrow on the right of **Append Queries**, choose **Append Queries as New**.
2. In the **Append** window, select **Three or more tables**.
3. Hold down *CTRL* (Windows) or *Command* (Mac) and select the OTHER two tables ("multiple-tables-2" & "multiple-tables-3"). If they are selected they will be highlighted.
4. Click **Add>>** then **OK**.
5. The table is now titled "Append1" give it a more descriptive name (eg. Student Mental Health Survey)

<details>
<summary>Click for Navigation help [WINDOWS]</summary>
<iframe src="images\multiple-tables-append.mp4" width="560" height="315" frameborder="0" allow="accelerometer; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</details>
<details>
<summary>Click for Navigation help [MAC]</summary>
<img src="images\append-mac.gif" >
</details>
<br>

This is the last of the power query steps. In the top navigation pane, in the **Home** tab, select **Close & Load**. Your data should now save as tables in sheets of your Excel Workbook (it may take a few seconds to load).

[NEXT STEP: Variables in Excel](6-variables-in-excel.md){: .btn .btn-blue }
