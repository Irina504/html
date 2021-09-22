# HTML Comprehension Questions

## Q1 - For each of the following HTML documents, is the HTML valid?

Type true/false in the provided [ ].

a) [False] `<div><span>hello</div></span>`

b) [False]

```html
<ul>
<li>one</li>
</ol>
```

c) [False] `<ul></ul><img/><ol><li>one</li></ol>`

## Q2 - What is a screenreader and why should we care about them?
A screen reader is an assistive technology, primarily used by people with vision impairments. It converts text, buttons, images and other screen elements into speech or braille.

_Feel free to use the powers of Google here, but please provide link(s) to your source(s)_ https://axesslab.com/what-is-a-screen-reader/
                https://www.nomensa.com/blog/what-screen-reader

## Q3 - For each of the following cases, which tags will be needed?

a) You want to create a webpage with the photos from your latest vacation
<img/>

b) You want to create a website that lists all the art gallery websites in your city and links to their website.
<ol>
<li>
<a>

c) You want to sell designer hats. You need to receive orders from the user.
<form>
<label>
<input>
<button>

## Q4 - Can a `button` be a child of a `button`? Explain your reasoning
No. A'button'tag element can't be followed by another clickable element. 

## Q5 - What is the most generic tag you can use?
<div>

## Q6 - What do the following achronyms stand for?

a) `a` anchor

b) `ol` ordered list

c) `ul` unordered list

d) `li` list items

e) `tr` table row

f) `th`table header cell

g) `td` table data cell

## Q7 - Usually, `td` elements are children of what kind of elements?
'tr'

## Q8 - What is the difference between td and th?
'td' refers to table data cell while 'th' refers to table header cells. 
This distinction gives user agents a means to render such cells distinctly, for instance by using a larger or heavier font for header cells. It is also needed when rendering to speech

## Q9 - Which tag makes the text appear bigger: h1 or h3?
h1

## Q10 - In which situation can you use self closing tags?
When we need to use "void elements", such as links and images. These tags have no content, they just point out to an elements installed on the page. 

## Q11 - What is autofilling and why is it important?
Autofilling is the browsers feature to automatically enter data previously stored and is a faster way to fill out forms. 

## Q12 - Which attributes are always present in an img element?
src, alt

## Q13 - Which attribute is always present for an anchor tag?
href