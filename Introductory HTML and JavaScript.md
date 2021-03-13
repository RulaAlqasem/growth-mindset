

HAW TO Creating a Web Page on a PC?
By using notepad++ type your code on it then save the file with html extension in some where you remember .
Then go to your web browser to the file menu and open your file .

All html contain head and body tag ,in the head you put the title and the CSS link
In the body you put header main and footer .

lang item: two parts a name and a value to determinate the language


# ch8: The different versions of HTML

**HTML 4** *Released 1997*:authors are not recommended to use it any more.

**XHTML 1.0** *Released 2000*:HTML4 should be reformulated to follow the rules of XML and it was renamed XHTML
 
 **HTML5** *Released 2000* :not yet completed, you can safely take advantage of the new features of the language as long as you endeavour to ensure that users with older browsers will be able to view your pages.






|COMMAND|WHAT ITS DOING |NOTE|
|---|---|---|
| !-- --|Comments in html|.|
|   id="pullquote"|ID Attribute|Its value should start with a letter or an underscore  allows you to style it differently than any other instance of the same element on the page|
|p class="important" AND p class="important admittance|Class attribute| allows you to style IMPURTANT values differently than any other value on the page|
|h1, p, ul, and li|Block Elements|A Examples of block elements | 
  | a, b, em, and img|Inline Elements|.|
|div| allows you to group a set of elements together in one block-level box|.|
|span| used to Contain a section of text where there is no other suitable element to differentiate it from its surrounding textor to Contain a number of inline elements|.|
|iframe| The term iframe is an abbreviation of inline frame|.|

# ch 17 :HTML5 Layout
HTML5 introduces a new set of elements that allow you to divide up the parts of a page.
+ The *header* and *footer*:
  - elements can be used for The main header or footer that appears at the top orbottom of every page on the site. A header or footer for an individual       *article* or *section* thin the page.
+ The *nav* element
  - is used to contain the major navigational blocks on the site such as the primary site navigation.
+ The*article* element 
  - acts as a container for any section of a page that could stand alone and potentially be syndicated. purposes, depending on whether it is inside an *article* element or not.
+ the *hgroup* element
  - is to group together a set of one or more *h1* through*h6* elements so that they are treated as one single heading.
+ the*figure* element
  - It can be used to contain any content that is referenced from the main flow of an article (not just images)
+ the *div* element
  - it will remain an important way to group together related elements, because you should not be using these new elements that you have just met for purposes other than those explicitly stated.

# Ch18 :process that you can use when you are creating a new website:

1. Who is the Site For?  People and company you would expect to be interested in the subject of your site.
1. why visitors come to the site?
1. specific goals of the visitors. These are the triggers making them come to the site now
1. What Your Visitors are Trying to Achieve
1. What Information Your Visitors Need
1. How Often People Will Visit Your Site

**To Mack it more organize and easier to programing make a Site Maps and Wireframes**

It's very important to understand who your target audience is, why they would come to your site, what information they want to find and when they are likely to return. X Site maps allow you to plan the structure of a site. X Wireframes allow you to organize the information that will need to go on each page. X Design is about communication. Visual hierarchy helps visitors understand what you are trying to tell them. X You can differentiate between pieces of information using size, color, and style. X You can use grouping and similarity to help simplify the information you present.

# to learn java scripts you have to learn html and css first 
**a script** : is a series of short instructions, each of which is performed in order to solve the problem in hand
you cane compare the  scripts with 
* RECIPES: the scripts are instructions  the computer can follw step by step .
* HANDBOOKS: a browser may use different parts of script depinding on haw the user interact with the web page .
* MANUALS: scripts can open differentg type of the cod depinding on the situation around them .

## WRITING A SCRIPT:
1. DEFINE THE GOAL :the task you want to achieve. 
2. DESIGN THE SCRIPT : split the goal out into a series of tasks that contain the order you want to use .
3. CODE EACH STEP: writ Each one  of the steps withe  JavaScript language FROM STEPS TO CODE:
* you need to get to grips with the:
  * Vocabulary: The words that computers understand
  * Syntax: How you put those words together to create instructions computers can follow
*  also need to learn how a computer achieves different types of goals using a programmatic approach to problem-solving.  You need to learn to "think" like a computer because they solve tasks in different ways than you or I might approach them. 

## DEFINING A GOAL & DESIGNING THE SCRIPT

* EXPRESSIONS:
  * two types of expressions. 
    1. EXPRESSIONS THAT JUST ASSIGN A VALUE TO A VARIABLE :In order for a variable to be useful, it needs to be given a value                                                   example :var color = 'beige';  The value of co 1 or is now beige.
    1. EXPRESSIONS THAT USE TWO OR MORE VALUES TO RETURN A SINGLE VALUE : You can perform operations on any number of individual values (see next page) to determine a single value. 
    example: var area = 3 * 2;  The value of area is now 6.  


## arithmetic operators :
name|OPERATOR| PURPOSE 
|---|---|---|
|ADDITION|  +|  Adds one value to another|
|SUBTRACTION| -|  Subtracts one value from another|
| DIVISION | / | Divides two values|
| MULTIPLICATION | *  | Multiplies two values using an asterisk|
|INCREMENT|  + + | Adds one to the current number |
|DECREMENT | -- | Subtracts one from the current number |
|MODULUS| % | Divides two values and returns the remainder|


## STRING OPERATOR  

* var name  = 'name of file'
* var number = 12
**you can use +  to  mix strings and numbers
<<<<<<< HEAD
If you try to use any of the other arithmetic operators on a string, then the value that results is usually a value called NaN. This means "not a number."
=======
If you try to use any of the other arithmetic operators on a string, then the value that results is usually a value called NaN. This means "not a number."**

## The key to understanding how CSS works is to imagine that there is an invisible box around every HTML element.
 block level elements: h1-h6 ,p tag
 inline elements : b tag  ,i tag  ,img tag ,em tag ,span tag 
css rule had a two part :
selectors:indicat wiche ilement the rule applies to
declaration:indicate how the element refarred to in the selector should be styled.
CSS declarations sit inside curly brackets and each is made up of two  parts:
Properties: indicate the aspects  of the element you want to  change. For example, color, font, width, height and border.
Values :specify the settings  you want to use for the chosen  properties. For example, if you want to specify a color property  then the value is the color you  want the text in these elements to be.
The link tag: element can be used in an HTML document to tell the  browser where to find the CSS  file used to style the page.
href :This specifies the path to the CSS file
type :This attribute specifies the type of document being linked to. The  value should be text/css.
rel This specifies the relationship  between the HTML page and  the file it is linked to. 
function :its alike a file that you can save comand in it to be faster and to not repeat the comand mor than one 
you have to call it after you write it .

## we can represint the color wit more than one way :
name: blu,red,green...
hexadecimal number: #00 00 ff "blue",#00 ff 00 "green...
rgba:"red green blue " :from 0-255  ex: 000 000 255 "blue"
hsl: hue saturation light , 
hu :colore dgree on the colores weel 
saturation :ammaunt of the gray 
light :ammount of the white .
 we can use rgba or hsla and this is for opacity .


