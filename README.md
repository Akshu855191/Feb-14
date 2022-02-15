Feb 14
CSS concepts

1. Introduction to css
Q. Why do we need CSS?
Ans:- - To style (looks) the HTML document.
- To give layout
- Cascading Style Sheet.
- We are currently on CSS3 (1999) x
- CSS was started in 1996
- We are on CSS 4.15 (DEC2019)
- CSS is a stylesheet language.
- Stylesheet languages:-
  - 1. xml(Extensible Stylesheet Language).
  - 2. DSSL(Document Style Semantics and Specification Language.)
  - 3. SASS(Syntatically Awesome Stylesheet)
  - 4. JSSS(Javascript Stylesheet)

2. 3 ways of adding css
- Inline CSS( Adding the CSS as a style attribute)
  E.g:-   <h1 style="color: red; background-color: brown;">Welcome to my page</h1>
- Internal CSS(Adding style tag in the document)
  E.g    <style>
        h2{
            color: red;
            text-align: center;
            background-color: blue;
        }
    </style>
- External CSS(All the CSS will be in a separate css)
   - Create a new file link it with main file by using
   <link rel="stylesheet" href="Link of that file ./" />

3. css selectors
 - A rule of text used to select which element (or elements)
   will have that specific style applied.
 - Basically, any eement matches the rule will have the style
   applied.

   Assignment1:-
   

   * Types Selectors:-(h1,p,form,table,button,input,header,selector,etc..)
   * Attribute Selector:- [key="value"] Select the element based on the attribute.
   * Id selector(#):- Id selector is used for selecting a particular element which gives the id. It has to be uniq.Example:- id="name"  // id="Roll-no"
   Id should not be same. We can access using #id-name.
   * Class selector(.):- Class selector is used to style particular class which have to given to html elements. Example:- class name="name"   //
   We can access class by using .class name 



4. color / background-color / taxt allign / margin / border / float
5. Shorthand for margin and border. 


-Specificity (Priority)