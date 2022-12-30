# Zero To Hero CSS
## What is CSS?
* it stands for cascading style sheet
* its used to make web site look better
* they can be used for: 
	* styling
	* layouts & Design
	* Animations
	* Font changes
	* grid systems
	* and many more
* CSS files are saved with the .css extension, and are liked using HTML tags

## what is a CSS selector?
* A CSS selector is the first part of a CSS Rule.
* they ae ways of grabbing and manupilating HTML
* Different selectors have different purposes
* **Element selector**: a way to select all the elements with a given tag name in a document, and apply the same styles to each element with the tag name.
* **class selector** : a way to select all the elements with a given class name in a document, and apply the same styles to each element with the class name.
* **ID selector** : a way to select all the elements with a given ID in a document, and apply the same styles to each element with same id.

## Classes & IDs in HTML
### class selecor
* we use a period character(.) followed by the name of the class
* most browsers support this
### id
* we use a harsh tag(#) followed by the id name


* we use a class when we need to use the same selector more than once within a page
* ID is specific to a single element, classes can be assigned to multiple elements on a page or throughout the website. They are not unique.

* selectors have different powers:
	* Below are the order of specificity rule which has precedence respectively: 1) Inline style: Inline style has highest priority among all.
	* Id Selector: It has second highest priority.
	* Classes, pseudo-classes and attributes: These selectors has lowest priority.
## pseudoselectors
* used commonly when something is done on the website(interactivity)
* after stating the selector we use a colon followed by the pseudoselector name
## advanced selectors
* when we say 'h2 + a' we mean that ever h2 header followed by a link will have certain properties that will be specified, where h2 is a parent element
### 1)Adjucent sibling selector
* It selects all the elements that are adjacent siblings of specified elements. It selects the second element if it immediately follows the first element. 
* for example:

```
h4+ul{
    border: 4px solid red;
}

```

* this select ul tags that immedietly follow h4 tag
### 2)Attribute Selector
*  It selects a particular type of inputs.
#### syntax
'''
input[type="checkbox"]{
    background:orange;
}
'''
####example

```
<html>
   <head>
      <title>Attribute</title>
      <style type="text/css">
         a[href="http://www.google.com"]{
         background:yellow;
         }
      </style>
   </head>
   <body>
      <a href="https://www.geeksforgeeks.org">geeksforgeeks.com</a><br>
      <a href="http://www.google.com" target="_blank">google.com</a><br>
      <a href="http://www.wikipedia.org" target="_top">wikipedia.org</a>
   </body>
</html>
```

### 3)nth-of-type Selector
* selects an element from its position and types. 

```
div:nth-of-type(5){
    background:purple;
}
```

### 4)Direct Child Selector





















