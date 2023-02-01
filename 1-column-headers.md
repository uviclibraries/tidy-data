---
layout: default
title: 1 Columns Headers are Values
nav_order: 2
parent: Workshop Activities
---

Instructions were designed for windows, but include Mac images and instructions in situations where the navigation is different.

# "UNDO" in Power Query

Before you begin, you should know that Power Query has no "undo" in the traditional sense. To remove a previous action on your data hover over the step in **APPLIED STEPS** in the **Query Settings** pane on the right. A red **X** should appear next to the step, click it to delete the step. If the Query Settings are not open:
1. Click on the **File** tab in the top left-hand corner
2. Select **Options and Settings**
3. Select **Options**
4. Under **GLOBAL** Select **Power Query Editor**
5. Make sure **Display the Query Settings pane** is checked off
6. Click Okay

<iframe src="images\query-settings.mp4" width="560" height="315" frameborder="0" allow="accelerometer; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<br>

# Columns Headers are Values

### Tidy Data Rule(s) Broken: Each variable forms a column

<br>
1. Open a new project in Excel
2. Open Power Query Editor from the Data tab in Excel

    [WINDOWS]
    a. Select "Get Data"
    b. Scroll down to "launch Power Query Editor..."

    [MAC]
    a. Click "Get data (Power Query)

<details>
<summary>See Navigation for Windows</summary>
<iframe src="images\navigation\open.mp4" width="560" height="315" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</details>
<details>
<summary>See Navigation for Mac</summary>
<img src="images\open-on-mac.gif">
</details>

<br>

### IMPORT DATA:

3.  [WINDOWS] <br>
    On the **home** tab, navigate to and select **new data source**, hover over **File** and select **Excel Workbook**. Notice that there are many different available data sources that Power Query can pull form. <br>
    [MAC] <br>
    Select **Excel Workbook** and click the browse button.


4. Import the **to-tidy.xlsx** [file](data/to-tidy.xlsx) from where you downloaded it.

5. 
    a. [WINDOWS only] In the Navigator window that pops up check off **Select multiple items**. <br>
    b. then check off all the sheets from the **to-tidy.xlsx** workbook. Click **OK** or **Load**.

6. From the menu on the left hand-side, select **col-vals**

<details>
<summary>Click for Navigation help [WINDOWS]</summary>
<img src="images\load-all.gif"> 
</details>
<details>
<summary>Click for Navigation help [MAC]</summary>
<img src="images\Load-data-mac.gif"> 
</details>
<br>

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