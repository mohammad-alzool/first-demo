# CSS
<p>&nbsp;</p>

![css](img/css2.png)
<p>&nbsp;</p>
<p>&nbsp;</p>

CSS (Cascading Style Sheets) is a style sheet language used for describing the presentation of a document written in a markup language such as HTML. CSS is a cornerstone technology of the World Wide Web, alongside HTML and JavaScrip

<p>&nbsp;</p>
<p>&nbsp;</p>

## How Does CSS Work?

CSS brings style to your web pages by interacting with HTML elements. Elements are the individual HTML components of a web page—for instance a paragraph—which in HTML might look like this:

\<p> This is my paragraph! \</p>

If you wanted to make this paragraph appear pink and bold to people viewing your web page through a web browser, you’d use CSS code that looks like this:

p \{ color:pink; &nbsp; font-weight:bold;  }

In this case, “p” (the paragraph) is called the “selector”—it’s the part of CSS code specifying which HTML element the CSS styling will effect. In CSS, the selector is written to the left of the first curly bracket. The information between curly brackets is called a declaration, and it contains properties and values that are applied to the selector. Properties are things like font size, color, and margins, while values are the settings for those properties. In the example above, “color” and “font-weight” are both properties, and “pink” and “bold” are values. The full bracketed set of

{  color:pink; &nbsp; font-weight:bold;  } 
is the declaration, and again, “p” (meaning the HTML paragraph) is the selector. These same basic principles can be applied to change font sizes, background colors, margin indentations, and more. For instance. . .

body  {  background-color:lightblue;  }
. . .would make your page’s background light blue, or. . .

p  {  font-size:20px;  color:red;  }
. . .will create a 20 point font paragraph with red letters.




## CSS Example


body {

  background-color: lightblue;

}


<p>&nbsp;</p>

h1 {

  color: white;


  text-align: center;

}
<p>&nbsp;</p>
p {
   
  font-family: verdana;
 
  font-size: 20px;

}