HTML  -it stands for hyper text markeup language.
we use html for creating str of the website.
we called html as a markeup language bcz it cntain secliton of the web page.
all html are written in tag line.
hr -horizontal line.
p - brake
br -brake
src,height,width,alt are the attributeof the image tag.
href-hyper referance (referance to the another page/eliment)
                                                       
 HTML FORMATING-
................

<mark>-bold text
<b>-bold text
<i>-italik text
<em>-emphasized text
<ins>-inserted text
<del>-deletion text
<sub>-subcripted text
<sup>-super subcripted text

HTML TABLE-
...........

html table gives us a table like structure where we can insert our data in row and column format.
<table>-main tag
<tr>-table row
<th>-table heading
<td>-table data

list are of 2 types.
    1-unordered list-<ul>
    2-orderred list-<ol>

    HTML BLOCK LEVEL ELIMENT-
    .........................

.html contain 2 types of block level element to specify the structure of a web pages
        1 <p>-paragraph
        2 <div>-division

HTML FORMS-
............

html form provides a form like structure so that we can give our data by use of these forms.


CSS-
....

-css stands for cascading stylish sheet.
-we used css for designing and stylint the web pages.
syntax:-h1{ selector
            color : red -( value)
                |
            (property)
        }
-basically css are 3 types:-
        1- inline css
        2- internal css
        3- external css

1- inline css:-
    ............

<body>
    <h1 style="color:red"> today is thusday</h>
    <pstyle="background:yellow"> today we started css</p>
</body>

2- internal css:-
    ............

<head>
    <style>
        h1{
            color:red;
            }
            p{
                background_color:blue;
            }
            </style>
        </head>

3- external css:-
    .............                                                                   
                                                                                     

- it is a linkage to the outer css file to our main HTML elimant.           

        index HTML                                                                  dtyle.css:-
        ...........                                                                 ...........
<head>                                                                  h1{
    <link rel="stylesheet"                                                 color:red;
    href="style.css">                                                      }
</head>
<body>
    <h1>today is a beautiful day<h1>
    </body>

CSS SELECTOR :-
.............

css selector are of 5 types -
    1. id selector
    2. class selector
    3. univesrsal selector
    4. group selector
    5. eliment selector

- selector means seleting a eliment which we have to designet.

1- ID SELECTOR:-
    ...........

- id selector are those selector which unique design / we select only one eliment in HTML file.
- it is denoted by "#"
ex:-
...
        HTML                                                                style.css
       .......                                                              ..........

 <html>                                                                     #TAT {
      <head>                                                                color:green;
        <link rel="stylesheet"                                              }
             href="style.css">                                              h1{
         <head>                                                              color:red;
         <body>                                                              }
            <h1 id="TAT">today is tuesday</h1>                              
            <h1>we learn css</h1>
            <h1>we write code</h1>
        </body>
        </html>

CLASS SELECTOR:-
................

- we used to class selector for repeating the similar design in multiple times.
- "." property we used to specify the class selector in our css file.
- class denoted by "." .

UNIVERSAL SELECTOR:-
...................

- we used universal selector to design whole html page in a single design.
- "*" property we used to specify the class selector in our css file.

*{
    color:red;
    text-aligen;
}

GROUP SELECTOR:-
................
- we used group selector to create one design in which wwe have selected the tags.
- group selector we used by creating the group.

h1,p{
    color:red;
    text-align:center;
    }


ELIMENT SELECTOR:-
.................
- by selecting one single single eliment we have to design is called the eliment selector.

h2{
    background-color:aqua;
}

