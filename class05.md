## **Chapter 5 :Images** 
***A picture can say a thousand words, and great images help make the difference between an average-looking site and a really engaging one.***
### **Images should...**

- Be relevant
- Convey information
- Convey the right mood
- Be instantly recognisable
- Fit the color palette

## **How can you Adding Images on your site:**

### To add an image into the page you need to use an '<img>' element. This is an empty element (which means there is no closing tag). It must carry the following two attributes:
- src :This tells the browser where it can find the image file.
- alt :This provides a text description of the image which describes the image if you cannot see it.
 ## **Height & Width of Images**
 ### -height :This specifies the height of the image in pixels.
### - width :This specifies the width of the image in pixels.
~~~
<img src="images/quokka.jpg" alt="A family of
 quokka" width="600" height="450" />
~~~
 ## **Aligning Images Horizontally**
 ### ***The align attribute was commonly used to indicate how the other parts of a page should flow around an image.***
 ### - left : This aligns the image to the left.
### - right : This aligns the image to the right.

## **Aligning Images Vertically**
### ***There are three values that the align attribute can take that control how the image should align vertically with the text that surrounds it:***
### - top : This aligns the first line of the surrounding text with the top of the image.
### - middle : This aligns the first line of the surrounding text with the middle of the image.
### - bottom : This aligns the first line of the surrounding text with the bottom of the image.

## **Image Resolution:**
### ***Images created for the web should be saved at a resolution of 72 ppi. The higher the resolution of the image, the larger the size of the file.***
## **Vector Images**
### ***Vector images differ from bitmap images and are resolution-independent. Vector images are commonly created in programs such as Adobe Illustrator.***

# **Chapter 11: Color**
## **Foreground Color**
### The color property allows you to specify the color of text inside an element. You can specify any color in CSS in one of three ways:
- rgb values These express colors in terms of how much red, green and blue are used to make it up. For example: rgb(100,100,90)
 - hex codes These are six-digit codes that represent the amount of red, green and blue in a color, preceded by a pound or hash # sign. For example: #ee3e80
- color names There are 147 predefined color names that are recognized by browsers. For example: DarkCyan.
## **Background Color**
### CSS treats each HTML element as if it appears in a box, and the background-color property sets the color of the background for that box.
~~~
body {
background-color: rgb(200,200,200);}
h1 {
background-color: DarkCyan;}
h2 {
background-color: #ee3e80;}
p {
background-color: white;}
~~~
## **Understanding Color**
### Every color on a computer screen is created by mixing amounts of red, green, and blue. To find the color you want, you can use a color picker.
![color](https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.pinterest.com%2Fpin%2F247909154473935541%2F&psig=AOvVaw2nMcPY7tEDHO3EsLFP22AM&ust=1613314149174000&source=images&cd=vfe&ved=0CAIQjRxqFwoTCPiCo96N5-4CFQAAAAAdAAAAABAT)

# **Chapter 12: Text**
## ***The properties that allow you to control the appearance of text can be split into two groups:***
- Those that directly affect the font and its appearance (including the typeface, whether it is regular, bold or italic, and the size of the text)
- Those that would have the same effect on text no matter what font you were using (including the color of text and the spacing between words and letters)
## **Typeface Terminology**
- Serif :Serif fonts have extra details on the ends of the main strokes of the letters. These details are known as serifs
- Sans-Serif : Sans-serif fonts have straight ends to letters, and therefore have a much cleaner design.
- Monospace : Every letter in a monospace (or fixed-width) font is the same width. (Non-monospace fonts have different widths.)
