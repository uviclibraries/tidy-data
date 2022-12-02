---
layout: default
title: 6 Variables in Excel
parent: Workshop Activities
---

# Variables in Excel

### VARIABLE TYPES:
1. Open [file-name] in Excel.
2. Select all filled cells by clicking and holding cell **1A** and dragging to cell **6F**
3. Navigate to the **Insert** tab and click the **Table** icon in the **Tables** section.
4. Make sure the **My table has headers** option is checked off and press **OK**.
5. Click on the **F** to select the "Open" column.
6. In the **Home** tab, in the **Number** section, click on the drop-down. Select **Time**.
7. Do the same for all the columns. The types should be
    1. "start date": **Date**
    2. "FTE employees": **Number**
    3. "Profit": **Currency**
    4. "Store type": **Text**
    5. "Store name": **Text**

<details>
<summary>Click for Navigation help</summary>
<iframe src="images\variables-in-excel-types.mp4" width="560" height="315" frameborder="0" allow="accelerometer; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</details>

### DATA VALIDATION:
1. Select the **F**/"Open" column again.
2. In the **Data** tab, in the **Data Tools** section, click **Data Validation**, select **Data Validation** from the drop-down. Select **Yes** in the window that pops up.
3. In the **Allow** input box, choose **Time**.
4. A store can open anytime of day, so we can set the **Start time** to **12:00:00 AM** and the **End time** to **11:59:59 PM**.
5. Click **Ok**.
6. Moving on to **start date**, choose **greater than** from the input box. Set the **start date** to **1-Jan-13**. In this case the start date is arbitrary, but if you were setting the date for a program, for example, you would set the validation to the start date of the program to the end date of the program. This would help avoid incorrect data collection, which produces outliers and missing data. 
7. For "FTE employees" choose **Decimal** and **greater than or equal to** 0 (a store cannot have negative employees).
8. Choose **Decimal** and **greater than or equal to** 0 for "Profit" as well. 
9. For "Store type" we can create a **List**. Type in **Coffee Shop, Clothing Store, Book Store** to the **Source** input box.
10. No validation is necessary for the store name
11. Try typing an inconsistent value into the table and see what happens.

<details>
<summary>Click for Navigation help</summary>
<iframe src="images\variables-in-excel-data-validation.mp4" width="560" height="315" frameborder="0" allow="accelerometer; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</details>

### Filtering
Often tables will be separated on values instead of observations because we want to make the data more readable to humans (instead of computers). Filters are a great way to keep your data tidy, but still be able to observe a specific value or group of values.

1. Since our data is already a table, filter drop downs are already applied. Click the arrow in the "store type" header uncheck **(Select All)** and check **Book store**. Press **OK**.
2. To clear the filter, open the filter window again using the same box in the corner of the header. You can now see that a filter icon is applied. Select **Clear Filter from "Store type"**.
3. Different data types also offer specific filters. In the "start date" filter drop-down hover over **Date Filters**. Take a look at all the filter options. Choose **Customer Filter...** at the very bottom.
4. In the **Custom AutoFilter** window, choose **is after And is before**. Then you can set a date range using the input box, or by clicking on the table icons on the far right. Once you have selected a start and end date, click **Ok**.
5. Test out some of the other filters in this table and the one's from the data tidying steps.

<details>
<summary>Click for Navigation help</summary>
<iframe src="images\variables-in-excel-filter-table.mp4" width="560" height="315" frameborder="0" allow="accelerometer; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</details>

You can also filter without a table by highlighting the descired cells and selecting **Sort and Filter** > **Filter** from the **Home** tab.

<details>
<summary>Click for Navigation Help</summary>
<iframe src="images\variables-in-excel-filter-without-table.mp4" width="560" height="315" frameborder="0" allow="accelerometer; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</details>

Congrats! You're done :)

[NEXT STEP: Additional Resources](additional-resources.md){: .btn .btn-blue }