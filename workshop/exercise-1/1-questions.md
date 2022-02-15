# HTML Comprehension Questions


## Q1 - For each of the following HTML documents, is the HTML valid?

Type true/false in the provided [ ].

a) [ false] `<div><span>hello</div></span>`

b) [ false]

```html
<ul>
<li>one</li>
</ol>
```

c) [true ] `<ul></ul><img/><ol><li>one</li></ol>`


## Q2 - What is a screenreader and why should we care about them?

_Feel free to use the powers of Google here, but please provide link(s) to your source(s)_
It helps people with visual impairment to surf the web. We should care because a lot of people need it and being accessible is cool ;P





## Q3 - For each of the following cases, which tags will be needed?

a) You want to create a webpage with the photos from your latest vacation
`<img>`

b) You want to create a website that lists all the art gallery websites in your city and links to their website.
`<ul> <ol> <a>`

c) You want to sell designer hats. You need to receive orders from the user.
`<form>`



## Q4 - Can a button be a child of a button? Explain your reasoning
No because there can't be a button inside a button, it doesn't make sense






## Q5 - What is the most generic tag you can use?
`<div>`




## Q6 - What do the following achronyms stand for?

a) `a` anchor

b) `ol` ordered list

c) `ul` unordered list

d) `li` list item

e) `tr` table row

f) `th` table header

g) `td` table data


## Q7 - Usually, `td` elements are children of what kind of elements?
`<table>` `<tr>` more specifically



## Q8 - What is the difference between td and th?

`<td>`is to add data to our table row. It kind of adds columns. `<th>`is used to name the columns, or the rows, with the scope attribute. It's not the data.

## Q9 - Which tag makes the text appear bigger: h1 or h3?

`<h1>`

## Q10 - In which situation can you use self closing tags?
When you need one? Like an `<img>`
Réponse selon les notes: If you element doesn't have any children, you can open and close it immediately
```html
<img src="stuff"/>
```


## Q11 - What is autofilling and why is it important?
it's when an input can be filling automatically by a browser because it's in a form tag. It's important because it "provides an easy way to send information to a server"


## Q12 - Which attributes are always present in an img element?
the alt attribute that explains what the image is about, for accessibility or if the page is not able to load the image properly.
they also need the src attribute with the url of the image


## Q13 - Which attribute is always present for an anchor tag?

the href attribute which is the url of the page we want to link it to.

