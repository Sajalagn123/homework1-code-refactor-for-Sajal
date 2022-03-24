# homework1-code-refactor-for-Sajal

## Description
The Horiseon webpage looked nice and had a proper layout, however, the html and CSS files used a lot of elements that were not semantic. This makes the page inaccessible, especially when it comes to indivdiuals who want to use a screenreader to browse through the webpage.

I had already accidentally updated the images with the alts earlier on. I updated the webpage to Horiseon and then added the header tag as well as the nav tag in the header, replacing the div tag.

I updated the section with the main content by replacing the div tag with the aritcle element as the parent tag. Then I labeled the child div tags with the section element.

I updated the section with the icons on the side of the article where the benefits are listed by replacing the div tags with the aside element as the parent tag. Then I replaced the child tags with the section element.

I changed the div tags with the footer class to the footer tag while changing the corresponding CSS names from .footer to just footer. In addition, I also changed the CSS elements for the header, that the nav items are displayed correctly with inline CSS. The CSS class elements of .hero and .content were changed to the article and main element selectors since the and html class was removed since it is redundant. 

Removed all the classes from the aside section of the html code and replaced their CSS counter parts with the element aside and aside section. I also removed the classes next the section elements under the article tag and changed the CSS named to aritcle section since the classes were not neccesary anymore. I also simplified the CSS elements regarding the article portion of the webpage by combing element with a redundant repitition of the same CSS attributes. 

## Installation
To install my project, I created a repository for it on Github. After that I cloned the repository onto my desktop. I then copied the folders from my class repository and pasted them into my folder. From there, I opened the assignments into a serperate folder.
