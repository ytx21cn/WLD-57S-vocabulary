# WLD-57S-vocabulary

UC Davis WQ 2017 Workload 57S Vocabulary

This is the list for my recorded vocabularies in the WLD 57S class.

https://ytx21cn.github.io/WLD-57S-vocabulary/

Read about Entry Leve Writing Requirement of UC Davis: http://elw.ucdavis.edu/elw-info

## Collaboration
To all WLD 57S students in Professor Ellen Abrams' class:  
If you want to collaborate with me, please send me [pull requests](https://github.com/ytx21cn/WLD-57S-vocabulary/pulls) and indicate your **real** name.  
* Help for pull requests: https://help.github.com/articles/about-pull-requests/

## My Coding Style
**Here are some brief descriptions of my coding styles. If you want to collaborate with me, you should agree with these coding styles before you contribute.** This is the consideration for maintaining the consistency of styles of codes written by different people, and for the ease of reading and writing codes.

### Directory Structure of the Repository
#### Course Materials
* Links to vocabularies from **all** the course materials are placed under **three** directories: **EL** (stands for _Exploring Language_, not yet created), **SSW** (stands for _Strategies for Successful Writing_), and **FromInstructor**.
  * **Note:** The directory names are **case-sensitive**. Using the incorrect cases in a hyperlink will result in an invalid link.
* Each `.html` file under each directory for course materials is named using the title of the passages in which the vocabulary words show up. For each file name, **turn the spaces into hyphens ("-")**, and use **all lowercase**. For example, the words coming from the reading **_The Allegory of the Cave_ by Plato** are listed in the file named `the-allegory-of-the-cave.html`.

#### Stylesheet
* There is currently one [stylesheet](https://github.com/ytx21cn/WLD-57S-vocabulary/blob/master/css/styles.css), which contains the styling information for **all** the pages in this repository. I have created it just for the ease of reading pages -- do not expect a fantastic appearance for the pages. **_And, generally, you do not need to edit it._**
* **How to link the stylesheet to the pages:**
 * For `index.html` page: `<link rel="stylesheet" href="css/styles.css" >`
 * For vocabulary pages: `<link rel="stylesheet" href="../css/styles.css" >`
 * Include these code in the `<head></head>` tags before the `<body></body>` tags.

### `Index.html` Page ###
This is the index page for the whole GitHub project.

* Link to the `index.html` file of this repository: https://github.com/ytx21cn/WLD-57S-vocabulary/blob/master/index.html  
* Link to the index page on the GitHub page: https://ytx21cn.github.io/WLD-57S-vocabulary/

#### Organization ####
First, write the **Level 1 header** of the page: `<h1>UC Davis Winter Quarter 2017 <a href="http://elw.ucdavis.edu/elw-info" target="_blank">WLD 57S</a> Vocabulary</h1>`. Note that there is a link to the [UC Davis ELWR information page](http://elw.ucdavis.edu/elw-info).  

Second, set up the **Level 2 headers** of the page: **_Exploring Language_**, **_Strategies for Successful Writing_**, and **Materials from Instructor**.

Third, set up the **Level 3 headers** under each Level 2 header, by **months**: January, February, and March.

The last step is creating a **list of passages** read in each month, under each Level 3 header.  
* For passages from textbooks, follow this format, and list them in **page number order**:  
 _Passage (in **italics**)_ by Author (pp. START - END)
* For passages from instructor, follow this format, and list them in **alphabetical order**:  
 _Passage (in **italics**)_ by Author
* When creating lists, use `<ul></ul>` to enclose a list, and use `<li></li>` between each pair of `<ul></ul>` to enclose each list item.
* Turn each _**title** (not including authors' names)_ into a hyperlink that leads to corresponding pages, e.g. [`<li><em><a href="SSW/the-appeal-of-the-androgynous-man.html">The Appeal of the Androgynous Man</a></em> by Amy Gross (pp. 30-31)</li>`](https://ytx21cn.github.io/WLD-57S-vocabulary/SSW/the-appeal-of-the-androgynous-man.html)

### Vocabulary Pages
* The heading is enclosed by `<h1></h1>`. Include the _name of the passage_ and name(s) of the author(s).
* Below the heading there must be a **"← Return to Main Page"** link: `<a href="../index.html">← Return to Main Page</a>`.
* List the word entries in **alphabetical** order.
* Use `<div></div>` to enclose each entry. Then, for each entry, use two pairs of `<p></p>` tags.
 * The first pair contains the **word entry (enclosed by `<strong></strong>`)** and its _part of speech (enclosed by`<em></em>`)_.
 * The second pair contains its definition or explanation.
* Leave **one blank line** between two pairs of `<div></div>` tags, in order to improve readability of codes.
* Here is one sample that shows the formatting of the code: 
`<div>
  <p><strong>surmise</strong> <em>v.</em></p>
  <p>To conjecture or guess.</p>
 </div>

 <div>
  <p><strong>trifle</strong> <em>n.</em></p>
  <p>A thing of little value or importance.</p>
 </div>`
