---
layout: default
title: 2 Multiple Variables are Stored in One Column
nav_order: 2
parent: Workshop Activities
---

# Multiple Variables are Stored in One Column
### Tidy Data Rule(s) Broken: Each variable forms a column
<br>

<mark>Select the "multiple-variables" table from the left pane.</mark>

<br>

### SPLIT BY DELIMITER:

2. Notice that the "Book" column includes both the **title** and the **author**? These are 2 different variables. In analysis you might want to do something like count the number of books an author has written. 

3. Right click on the "Book" header. Hover over **Split Column**, then select **By Delimiter...**

4. In the **Split Column by Delimiter** window
- [WINDOWS] click on the **Select or enter delimiter** option <br>
- [MAC] Use the drop-down-menu titled **Separator** <br>
and choose **--Custom--** from the drop-down menu.

5. You may have noticed that the title and author are separated using the word "by" in the "Book" column. This will be the delimiter. **NOTE: if the variables are separated by any spaces, these should be included in the delimiter you use or else there will be [white space](https://en.wikipedia.org/wiki/Whitespace_character) which software will recognize as a character.** Type in <mark>&nbsp;&nbsp;by&nbsp; </mark> (with a space on both sides) into the input box and select **OK**.

<details>
<summary>Click for Navigation help (all steps in the "split by delimiter" section)</summary>
<img src="images\multiple-variables-split-on-by.gif"> 
</details>

### RENAME HEADERS:

6. Rename the columns to be more descriptive by double clicking on them (eg. "Title" and "Author")

<details>
<summary>Click for Navigation help</summary>
<img src="images\multiple-variables-renmae-headers.gif"> 
</details>

[NEXT STEP: Variables in Rows and Columns](3-rows-and-cols.md){: .btn .btn-blue }