# davidandkat-source

This is the repository to control my personal website, [davidandkat.net](https://www.davidandkat.net).
Over the coming months, I intend to apply what I learn from [The Odin Project](https://www.theodinproject.com) to this project in order to make it a decent experience.
So far, it is just plain HTML with a little CSS and some markdown that I converted to HTML as a test.

## Plan

The plan is to slowly build out some actual content along the lines of math tutorials, and so on.
Just a place to put up my various interests.

## Converting markdown to HTML

To convert the markdown into HTML:

`pandoc -s -f markdown -t html5 -o <output>.html <input>.md`

If no style included in markdown header: 

`--css=style.css`

## Using mathjax

I'll include LaTeX via [mathjax.org](https://www.mathjax.org)'s javascript. 
So far this seems to work really well. 

## Plan

I want to add an extensive math tutorial of simple ways to get to the end of say college algebra. 
