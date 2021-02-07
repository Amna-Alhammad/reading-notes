## **Introduction**


## ***How the Web Works***
- you connect to the web via an ISP.
- your computer contacts anetwork of servers caled DNS servers.
- the DNS server returns a unique number to your computer.
- the web server send the page you requested back to your web browser. 

## **HTML Chapter 1: Structure**
### **What is HTML?**
  - HTML stands for Hyper Text Markup Language, HTML describes the structure of a Web page, it consists of a series of elements to tell the browser how to display the content. 
 - HTML Uses Elements to Describe the Structure of Pages Each element has an opening tag ``` < open tag>``` and a closing tag``` </ closing tag>```***


 ### **HTML Contains** 
- Head  ``` <head> </head>```
- Title  ``` <title> </title>```
- Body  ``` <body> </body>```
- paragraph ``` <p> </p>```
-  Heading ``` <h1> </h1> <h2></h2>......<h6></h6>```
- imge         ``` <img src="img_girl.jpg">```
- main         ``` <main> </main>```
- Footer   ```<footer> </footer> ```
- Navigation ```<nav>  </nav>```
- Division elements``` <div>``` ; to group elements in a block  

### *Opening tags can carry attributes require a name and a value.*
```<p lang="en-us">Paragraph in English</p>```



## **HTML Chapter 8: Extra Markup**

### **There is several versions of HTML, each web page should begin with a ``` <DOCTYPE html>``` declaration to tell a browser which version of HTML the page is using(although browsers usually display the page even if it is not included)**



 ## **What Versions of HTML:**
 - HTML 4  (Released 1997)
- XHTML   (Released 2000)
- HTML 5 ``` <!DOCTYPE html> ```(Released 2000)


### ***We will use version 5 of HTML.B ecause there have been several versions of HTML, each web page should begin with a DOCTYPE declaration to tell a browser which version of HTML the page is using (although browsers usually display the page even if it is not included).***

## **How can you add a Comments in HTMl?**

### If you want to add a comment to your code that will not be visible in the user’s browser, you can add the text between these characters: ``` <!-- comment goes here --> ```


## **ID Attribute:**
- Every HTML element can carry the id attribute. 
- It is used to uniquely identify that element from other elements on the page.
-  Its value should start with a letter or an underscore (not a number or any other character).
- It is important that no two elements on the same page have the same value for their id attributes (otherwise the value is no longer unique).
 ~~~
 <p id="pullquote">
 Hello World
</p>
 ~~~

## **Class Attribute:**
### The class attribute on any element can share the same value. to identify several elements as being different from the other elements on the page. to do this you can use the class attribute. Its value should describe the class it belongs to.


## **Block Elements:**
**Some elements will always appear to start on a new line in the browser window.** ***These are known as block level elements.***
Examples of block elements are ``` <h1>, <p>, <ul>, and <li>```


## **Inline Elements:**
Some elements will always appear to continue on the same line as their neighbouring elements. These are known as inline elements.
Examples of inline elements are ``` <a>, <b>, <em>, and <img> ```

## **Grouping Text & Elements in a Block:**
 ### * `<div>:`
  The ```<div>``` element allows you to group a set of elements together in one block-level box. For example, you might create a `<div>` element to contain all of the elements for the header of your site (the logo and the navigation), or you might create a `<div>` element to contain comments from visitors.
In a browser, the contents of the `<div>` element will start on a new line, but other than this it will make no difference to the presentation of the page.
 ### * `<iframe>:`
 An iframe is like a little window that has been cut into your page — and in that window you can see another page. The term iframe is an abbreviation of inline frame.

 One common use of iframes (that you may have seen on various websites) is to embed a Google Map into a page. The content of the iframe can be any html page (either located on the same server or anywhere else on the web).

 An iframe is created using the `<iframe>` element. There are a few attributes that you will need to know to use it:
 * Src: The src attribute specifies the URL of the page to show in the frame.

* Height: The height attribute specifies the height of the iframe in pixels.

* Width: The width attribute specifies the width of the iframe in pixels.

### * `<span>:`
The `<span> `element acts like an inline equivalent of the` <div>` element. It is used to either:

Contain a section of text where there is no other suitable element to differentiate It from its surrounding text.
Contain a number of inline elements.

## ** HTML Chapter 17 : HTML5 Layout**
### *HTML has several semantic elements that define the different parts of a web page:*
![layout](https://www.w3schools.com/html/img_sem_elements.gif)
~~~
    
<header> - Defines a header for a document or a section
<nav> - Defines a set of navigation links
<section> - Defines a section in a document
<article> - Defines an independent, self-contained content
<aside> - Defines content aside from the content (like a sidebar)
<footer> - Defines a footer for a document or a section
<details> - Defines additional details that the user can open and close on demand
<summary> - Defines a heading for the <details> element
~~~

## **HTML Chapter 18: PROCESS & Design**
![design](https://i0.wp.com/intenseminimalism.com/wp-content/uploads/2010/10/37signals-process.png?resize=480%2C230)

### - It's important to understand who your target audience is, why they would come to your site, what information they want to find and when they are likely to return.
### - Site maps allow you to plan the structure of a site.
### - Wireframes allow you to organize the information that will need to go on each page.
### - Design is about communication. Visual hierarchy helps visitors understand what you are trying to tell them.
### - You can differentiate between pieces of information using size, color, and style.