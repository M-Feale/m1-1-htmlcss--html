# HTML Comprehension Questions


## Q1 - For each of the following HTML documents, is the HTML valid?

Type true/false in the provided [ ].

a) [false] `<div><span>hello</div></span>`

b) [false]

```html
<ul>
<li>one</li>
</ol>
```

c) [true] `<ul></ul><img/><ol><li>one</li></ol>`


## Q2 - What is a screenreader and why should we care about them?

_Feel free to use the powers of Google here, but please provide link(s) to your source(s)_

Screen readers are tools used for accessibility. It allows users to read and navigate pages without having to use their vision. Screenreaders are important in that they allow people with disabilities, be it visual or other forms that prevent or hinder a person to read, to have access to the web in a way that is accessible to them, be it through audio or even brail (according to wikipedia). They are a tool used by a big part of the population and omitting to create websites that are readable for screenreaders makes access to those websites impossible for certain people. 




## Q3 - For each of the following cases, which tags will be needed?

a) You want to create a webpage with the photos from your latest vacation
<body>
    <h1>Vacation photos !</h1>
    <img src="url" alt="me at the beach"/>
    <img src="url" alt="me at the lake"/>
</body>

b) You want to create a website that lists all the art gallery websites in your city and links to their website.
<body>
    <ul>
        <li>
            <a href="url"> Musée d'art </a>
        </li>
        <li>
            <a href="url"> Musée des sciences </a>
        </li>
    </ul>
</body>

c) You want to sell designer hats. You need to receive orders from the user.
<body>
    <form>
        <input></input>¨
        <button></button>
    </form>
</body>




## Q4 - Can a button be a child of a button? Explain your reasoning
no, because a button cannot have a clickable child. If a button is a child of a button, pressing the child would equate to pressing the parent, thus making it redundant and useless. 





## Q5 - What is the most generic tag you can use?
the <div></div> tag can be used anywhere in the document for multiple purposes



## Q6 - What do the following achronyms stand for?

a) `a` anchor, which is a link

b) `ol` orderded list, with numbers

c) `ul` unordered list, with bullets

d) `li` list elements

e) `tr` table row

f) `th` table head  

g) `td` table data


## Q7 - Usually, `td` elements are children of what kind of elements?
a table row


## Q8 - What is the difference between td and th?
a th is a table head and indicates that it's the header of the column where as td is a table cell that contains any kind of data

## Q9 - Which tag makes the text appear bigger: h1 or h3?
h1 by default but it can be changed with the css. 


## Q10 - In which situation can you use self closing tags?
when you use the <img/> tag


## Q11 - What is autofilling and why is it important?
autofilling is a feature of browsers to fill in forms for you automatically. It is important beacause it saves time and makes filling forms easier for people with disabilities


## Q12 - Which attributes are always present in an img element?
the src attributes and the alt attributes


## Q13 - Which attribute is always present for an anchor tag?
the href attribute


