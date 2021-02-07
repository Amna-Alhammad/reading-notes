 ## **HTML Chapter 2: Text**
 ### 1- **Headings : `<h1>`**
  - HTML has six "levels" of
headings:`<h1>` is used for main headings`<h2>` is used for subheadings.

- Browsers display the contents of headings at different sizes. The contents of an `<h1>` element is the largest, and the contents of an `<h6>` element is the smallest.
 ~~~
 <h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>
 ~~~

  ### 2- **Paragraph : `<p>`**
  - To create a paragraph, surround the words that make up the paragraph with an opening `<p>` tag and closing `</p>` tag.


 ### 3- **Bold `<b>` & Italic `<i>` :**

 - By enclosing words in the tags `<b>` and `</b>` we can make characters appear bold.

 - By enclosing words in the tags `<i>` and `</i>` we can make characters appear italic.

### 4- **Superscript `<sup>` & Subscrip `<sub>` :**
 - The `<sup>` element is used to contain characters that should be superscript such as the suffixes of dates or mathematical concepts like raising a number to a power .
 - The `<sub>` element is used to contain characters that should be subscript. It is commonly used with foot notes or chemical formulas .

### 5- **Line Breaks`<br />` & Horizontal Rules `<hr />` :**
-`<br /> :` As you have already seen, the browser will automatically show each new paragraph or heading on a new line. But if you wanted to add a line break inside the middle of a paragraph you can use the line break tag `<br />`.
- `<hr /> :`To create a break between themes — such as a change of topic in a book or a new scene in a play — you can add a horizontal rule between sections using the `<hr />` tag.

### 6- **Strong `<Strong>` & Emphasis `<em>` :**
- The use of the `<strong>` element indicates that its content has strong importance. For example, the words contained in this element might be said with strong emphasis. By default, browsers will show the contents of a `<strong>` element in bold.

- The `<em>` element indicates emphasis that subtly changes the meaning of a sentence. By default browsers will show the contents of an `<em>` element
in italic.

 ### **What is the White Space ?**

 - white space collapsing: When the browser comes across
two or more spaces next to each
other, it only displays one space.
Similarly if it comes across a line
break, it treats that as a single
space too.