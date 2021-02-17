# **Chapter 7: Forms**
## **Why Forms?**
### The best known form on the web is probably the search box that sits right in the middle of Google's homepage.
### - In addition to enabling users to search, forms also allow users to perform other functions online. You will see forms when registering as a member of a website, when shopping
online, and when signing up for newsletters or mailing lists

## **Form Controls**
### There are several types of form controls that you can use to collect information from visitors to your site.
### ***ADDING TEXT:***
- Text input (single-line)
- Password input
 -Text area (multi-line)
### ***Making Choices:***
- Radio buttons
- Checkboxes
- Drop-down boxes

### ***Submitting Forms:***
- Submit buttons
- Image buttons
### ***Uploading Files:***
- File upload
 ## **How Forms Work**
 1- A user fills in a form and then presses a button to submit the information to the server.
 2- The name of each form control is sent to the server along with the value the user enters or selects.
 3- The server processes the information using a programming language such as PHP, C#, VB.net, or Java. It may also store the information in a database.
 4- The server creates a new page to send back to the browser based on the information received.
 ~~~
 * username=Ivy            
 * vote=Herbie
 ~~~
 
If the form control allows the user to enter text, then the value of the form control is whatever the user has typed in.

If the form control allows you to choose from a fixed set of answers (e.g. radio buttons, checkboxes or a drop down list), the web page author will add code that gives each option an automatic value.
## **Form Structure**
~~~
<form action="http://www.example.com/subscribe.php"
method="get">
<p>This is where the form controls will appear.
 </p>
</form>
~~~

- '<form>' :Form controls live inside a '<form>' element. This element should always carry the action attribute and will usually have a method and id attribute too.
- action: Every '<form>' element requires an action attribute. Its value is the URL for the page on the server that will receive the information in the form when it is submitted
- method :Forms can be sent using one of two methods: get or post.
