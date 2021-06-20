# Reading 02

## Headings types :
HTML has six "levels" of
headings:
//<h1> is used for main headings
//<h2> is used for subheadings
If there are further sections
under the subheadings then the
<h3> element is used, and so
on...

![headings](https://data-flair.training/blogs/wp-content/uploads/sites/2/2020/06/Headings-in-HTML.jpg)


## Bold & Italic:
By enclosing words in the tags
//<b> and </b> we can make
characters appear bold.

By enclosing words in the tags
//<i> and </i> we can make
characters appear italic.

![bold](https://developersdesire.files.wordpress.com/2014/09/biu-page-0.jpg)

## Superscript & subscript:
//<sup>: The <sup> element is used
to contain characters that
should be superscript such
as the suffixes of dates or
mathematical concepts like
raising a number to a power such
as 22.

//<sub>: The <sub> element is used to
contain characters that should
be subscript. It is commonly
used with foot notes or chemical
formulas such as H20.

## Line Breaks & horizantal rule:
//<br />:As you have already seen, the
browser will automatically show
each new paragraph or heading
on a new line. But if you wanted
to add a line break inside the
middle of a paragraph you can
use the line break tag <br />.
//<hr />:To create a break between
themes — such as a change of
topic in a book or a new scene
in a play — you can add a
horizontal rule between sections
using the <hr /> tag.

## Visual Editors & their code views:
Visual editors often resemble
word processors. Although
each editor will differ slightly,
there are some features that
are common to most editors
that allow you to control the
presentation of text.

## css:
CSS allows you to create rules that specify how the content of
an element should appear. For example, you can specify that
the background of the page is cream, all paragraphs should
appear in gray using the Arial typeface, or that all level one
headings should be in a blue, italic, Times typeface.
![css](https://www.freetutorialsplus.com/css-tutorial/images/css-illustration.png)

### CSS Associates Style rule with html elements:
CSS works by associating rules with HTML elements. These rules govern
how the content of specified elements should be displayed. A CSS rule
contains two parts: a selector and a declaration.
![css declaration](https://www.w3schools.com/css/img_selector.gif)

### There are three options for styling HTML elements:
- inline :styling happen inside tag
- internal css :by using Usi ng Internal CSS
- external css:by using Using External CSS file


## CSS Selectors:
There are many different types
of CSS selector that allow you to
target rules to specific elements
in an HTML document.
![css selectros](https://devopedia.org/images/article/274/2595.1589957381.png)

## css rules cascade:
The cascade is an algorithm that defines how to combine property values originating from different sources. It lies at the core of CSS, as emphasized by the name: Cascading Style Sheets. This article explains what the cascade is, the order in which CSS declarations cascade, and how this affects you, the web developer.

### External style sheets?

An external style sheet is a separate file where you can declare all the styles that you want to use on your website. You then link to the external style sheet from all your HTML pages.

This means you only need to set the styles for each element once. If you want to update the style of your website, you only need to do it in one place.

## Linking html to javascript

If you want to run the same JavaScript on several pages in a web site, you should create an external JavaScript file, instead of writing the same script over and over again. Save the script file with a .js extension, and then refer to it using the src attribute in the    tag. 

### Script defention:
A script is a series of instructions that a computer can follow one-by-one.
Each individual instruction or step is known as a statement.
Statements should end with a semicolon.

#### COMMENTS:You should write comments to explain what your code does.
They help make your code easier to read and understand.
This can help you and others who read your code.

ex. /* Th i s script displays a greeting to the user based upon the current time.
It is an example from JavaScript & jQuery book */

### WHAT IS A VARIABLE?
A script will have to temporarily
store the bits of information it
needs to do its job. It can store this
data in variables.
##### how to declare variable?

var x=5;

### DATA TYPES:
1. numric 
2. string
3. boolean


### RULES FOR NAMING variables:
1. The name must begin with
a letter, dollar sign ($),or an
underscore (_). It must not start
with a number.
2. The name can contain letters,
numbers, dollar sign ($), or an
underscore (_). Note that you
must not use a dash(-) or a
period (.) in a variable name.
3. You cannot use keywords or
reserved words
4. All variables are case sensitive,
5. If your variable name is made
up of more than one word, use a
capital letter for the first letter of
every word after the first word.

## ARRAYS:
An array is a special type of variable. It doesn't
just store one value; it stores a list of values.
![array](https://miro.medium.com/max/1368/1*Gs9AECdBgWc-eG5Tjit-EQ.png)
note: You should consider using an
array whenever you are working
with a list or a set of values that
are related to each other.

### EXPRESSIONS:An expression evaluates into (results in) a single value. Broadly speaking
there are two types of expressions.

#### types:
1. EXPRESSIONS THAT JUST ASSIGN A
VALUE TO A VARIABLE
2. EXPRESSIONS THAT USE TWO OR
MORE VALUES TO RETURN A
SINGLE VALUE

##Decision making:
n any programming language, the code needs to make decisions and carry out actions accordingly depending on different inputs. For example, in a game, if the player's number of lives is 0, then it's game over. In a weather app, if it is being looked at in the morning, show a sunrise graphic; show stars and a moon if it is nighttime. In this article, we'll explore how so-called conditional statements work in JavaScript.
![decision making](https://www.bookofnetwork.com/images/javascript-images/JS_condition-img_24Feb17_1749.png)
