# bronzeAgeComics

## attribute values: id, class, rel

### id attribute values
This design relies on three unique identifiers for representations: 

#### comics
Applied to a div tag. The list of comics in this representation. This list may contain only one comic.

#### issues
Applied to the div tag. The list of issues in this representation. This list may contain only one issue.

#### queries
Applied to a div tag. The list of valid queries in this representation. This is a list of simple queries (represented by the HTML anchor tag).



### Class attribute values 
There are a number of class attributes that can appear within a representation. Clients should be prepared to recognize the following values: 

#### all
Applied to a UL tag. A list representation. When this element is a descendant of DIV. id="comics" it MAY have one or more LI. class="comic" descendant elements. When this element is a descendant of DIV. id="issues" it MAY have one or more LI.class="issue"descendant elements. 

#### comic
Applied to a LI tag. Contains information of a specific comic.

#### comic-text
Applied to a SPAN tag. Contains the comic entry number.

#### description
Applied to a SPAN tag. Contains a description of the issue.

#### issue
Applied to a LI tag. Contains information of a specific issue.

#### issuenumber
Applied to a SPAN tag. Contains the issue's number.

#### issue-text
Applied to a SPAN tag. Contains the issue entry.

#### single
Applied to a UL tag. A list representation. When this element is a descendant of DIV. id="issues" it MAY have one or more LI.class="issue"descendant elements. 




###Rel attribute values
This design also identifies a number of possible simple state transitions, or static links, that may appear within representations. 
These will appear as HTML anchor tags with the following rel attribute values:

#### comic
Applied to an A tag. Contains the text description of the title of a comic.

#### creator
Applied to an A tag. A reference to a writer/artisit/inker.

####issue
Applied to an A tag. Contains the text description of the issue number of a comic.

#### publisher
Applied to an A tag. A reference to the comic book's publisher.