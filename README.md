<h2>(26/03/17) Docbones.css Project Thoughts</h2>

I will readily admit that this project rates very low on the originality front but was a very 
useful, and functional, exercise all the same. After the amount of time I spent just initialising
certain elements in the Google Search project I wanted to create some sort of template that I could
use in future without having to code everything from scratch. I'm well aware of this being the purpose
of things like Bootstrap but there are two reasons why I wanted to give this a go:

1) Bootstrap seems, ironically, a little TOO well-fleshed out. In that it's a little too heavy
and complete for my current very light needs. I wanted to use something that only provided the 
true barebones of a template. Seeing as how I needed so little I thought I could try to code it myself.

2) Simply using Bootstrap, though useful, does not cement understanding. If I rely on a framework
like Bootstrap too much I believe, whether rightly or wrongly, that I'll lose some important aspect
of understanding CSS due to getting down and wrestling with it or a regular basis. Once I get into more
complicated projects I'm sure I'll be glad to have it but at this early stage I want to continue to
build upon my familiarity. 

===========
<h3>Technique Thoughts</h3>
Without having any idea of how to build a template I settled upon using the excellent Skeleton.css 
(http://getskeleton.com/) as 'inspiration'. That is, I lifted a lot of styling and layout decisions
from Skeleton and customised it to my own liking. 

Some notes:

- Skeleton relies on floats for its grid layouts but, after the Google search experience, I was 
adamant that Flexbox could do a far better job. As such I used Flexbox and am very happy with the 
result. The HTML may get a little excessive but the CSS itself is very clean and easily adaptable.

- I'd like to build a better understanding of the relationship between various font-size specifications
across elements. 

- Added to the above a greater understanding of rem and em units seems a necessity. 

- Replacing common definitions like 'row' and 'container' 
