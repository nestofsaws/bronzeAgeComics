bronzeAgeComics
===============

ID attribute values 
This design relies on four unique identifiers for representations: 

comics 
Applied to a div tag. The list of comics in this representation. This list may 
contain only one comic.

issues
Applied to the div tag. The list of issues in this representation. This list may
contain only one issue.

queries
Applied to a div tag. The list of valid queries in this representation. This is a list of 
simple queries (represented by the HTML anchor tag).

titles
Applied to the div tag. The list of titles in this representation. This list may
contain only one title.


Class attribute values 
There are a number of class attributes that can appear within a representation. Clients 
should be prepared to recognize the following values: 

all 
Applied to a UL tag. A list representation. When this element is a descendant of 
DIV. id="comics" it MAY have one or more LI. class="comic" descendant elements. When this element is a descendant of DIV. id="titles" it MAY have one or 
more LI.class="title" descendant elements. 

comic
Applied to a SPAN  tag. Contains the text description of the title of a comic.

