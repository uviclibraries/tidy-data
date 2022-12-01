---
layout: default
title: 1 Columns Headers are Values
nav_order: 2
parent: Workshop Activities
---

# Columns Headers are Values

### Tidy Data Rule(s) Broken: Each variable forms a column


1. Open a new project in Excel
2. Open Power Query Editor from the Data tab in Excel

    a. Select "Get Data"
    
    b. Scroll down to "launch Power Query Editor..."

<iframe src="images\navigation\open.mp4" width="560" height="315" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### IMPORT DATA:

3. On the **home** tab, navigate to and select **new data source**, hover over **File** and select **Excel Workbook**. Notice that there are many different available data sources that Power Query can pull form.

4. Import the **to-tidy.xlsx** [file]() from where you downloaded it.

5. In the Navigator window that pops up check off **Select multiple items** then check off all the sheets from the **to-tidy.xlsx** workbook. Click **OK**.

6. From the menu on the left hand-side, select **col-vals**

<details>
<summary>Click for Navigation help</summary>
<img src="images\load-all.gif"> 
</details>

### ADJUST HEADERS:

7. Sometimes Power Query does not automatically detect that the table has headers. Click on the little table icon on the top left-hand corner of your data table. Select "Use First Row as Headers" from the dropdown menu.

<details>
<summary>Click for Navigation help</summary>
<img src="images\col-vals-promote-header.gif"> 
</details>

### UNPIVOT COLUMNS:

The "messiness" of this table is because of the headers "issued" and "available" are actually values indicating the availability of a book. The values that they hold are the Book Ids, which should be in their own column with a descriptive heading.

8. Select both the **issued** and **available** columns by holding *CTRL* if you're on windows and *command* of you're on a Mac and clicking on their headers.

9. Once bother the columns are highlighted, right click on either header, select **unpivot columns** from the dropdown menu.

<details>
<summary>Click for Navigation help</summary>
<img src="images\col-vals-unpivot.gif"> 
</details>

### GIVE NEW COLUMNS DESCRIPTIVE NAMES:

10. Now the columns have the headings "Attribute" and "value" which are not very descriptive. Change the names by double clicking on the header. Use something descriptive that someone who has never seen your data before might understand, for example, "Availability" and "ID" 

<details>
<summary>Click for Navigation help</summary>
<img src="images\col-vals-rename-headers.gif"> 
</details>

[NEXT STEP: Multiple Variables are Stored in One Column](2-multiple-variables.md){: .btn .btn-blue }