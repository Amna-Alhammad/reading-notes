## **HTML Chapter 3: Lists**
### ***There are lots of occasions when we need to use lists. HTML provides us with three different types:***

- **Ordered lists** are lists where each item in the list is numbered. 

- **Unordered lists** are lists that begin with a bullet point
(rather than characters that indicate order).


- **Definition lists** are made up of a set of terms along with the
definitions for each of those terms.

### 1- **Ordered Lists :**
`<ol>`
The ordered list is created with the `<ol>` element.
`<li>`Each item in the list is placed between an opening `<li>` tag and a closing `</li>` tag. (The li
stands for list item.)
~~~
<ol>
<li>Home</li>       --------> 1. Home
<li>About us</li>   --------> 2. About us
<li>sale</li>       --------> 3. sale
</ol>
~~~
### 2- **Unordered lists :**
- `<ul>` The unordered list is created with the `<ul>` element.
- `<li>` Each item in the list is placed between an  opening `<li>` tag and a closing `</li>` tag. (The li stands for list item.)

~~~
<ul>
<li>Home</li>      
<li>About us</li>
<li>sale</li>
</ul>
~~~

### 3- **Definition Lists :**
- `<dl>` The definition list is created with the `<dl>` element and usually consists of a series of terms and their definitions. Inside the `<dl>` element you will usually see pairs of `<dt>` and `<dd>` elements.

- `<dt>` This is used to contain the term
being defined (the definition term).
- `<dd>` This is used to contain the
definition. Sometimes you might see a list where there are two terms used for the same definition or two different definitions for the same term.

~~~
<dl>
<dt>Sashimi</dt>
<dd>Sliced raw fish that is served with
 condiments such as shredded daikon radish or
 ginger root, wasabi and soy sauce</dd>

<dt>Scale</dt>
<dd>A device used to accurately measure the
 weight of ingredients</dd>
</dl>
~~~
#### Result
~~~
Sashimi
    Sliced raw fish that is served with
    condiments such as shredded daikon radish or
    ginger root, wasabi and soy sauce

Scale
    A device used to accurately measure the
~~~

## **What is the  nested lists?**
### You can put a second list inside an `<li>` element to create a sublist or nested list
~~~
<ul>
<li>Mousses</li>
<li>Pastries
 <ul>
     <li>Croissant</li>
    <li>Mille-feuille</li>
    <li>Palmier</li>
    <li>Profiterole</li>
 </ul>
</li>
<li>Tarts</li>
</ul>
~~~