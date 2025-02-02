<h2>Semantic content sections</h2>

The next elements are the main elements to use when adding content to the
document. For example, using the article element instead of an arbitrary div
element allows the browser to infer that this is the main content of the page. These
elements should be used to give structure to a document and not be used for styling
purposes. Semantic elements make our HTML document more accessible using an
ever-increasing amount of different devices.

<h3>body</h3>
The body element is the main content section of the document. There must be only
one main element, its syntax is as follows:

```
<body></body>
```

<h4>Attributes</h4>
The attributes of the body element include the inline event attributes.

<h4>Description</h4>
The body element is the main content section of most documents. It must be the
second child element of html, and there should only be one body element in a
document.

<h5>Here is an example of the body element:</h5>

```
<body>
<span>Example Body</span>
</body>
```

<h3>section</h3>
The section element describes the content section of a document. For example, this
can be a chapter of a book:

```
<section></section>
```

<h4>Description</h4>
The section element is a new element that was introduced in HTML5. A section
element should group the content together. While not a requirement, using a
heading element as the first element in the code is a best practice. The section should
be viewed as another part of the outline of the document. It groups related items into
an easily targeted area. You can use this element multiple times in a document.
Here is an example of the section element:

```
<section>
<h2>Section Heading</h2>
<p>Section content.</p>
</section>
```

<h3>nav</h3>
The nav element is the navigation element:

```
<nav></nav>
```

<h4>Description</h4>
The nav element is another semantic element introduced with HTML5. This lets the
browser know that the content of this element is the parent and is for navigation.
The nav element enhances accessibility by giving screen readers a landmark for
navigation. This element should wrap any site navigation or other links that are
grouped together for ease of navigation. You can use this multiple times.
Here is an example of using the nav element:

```
<nav>
  <ul>
    <li><a href="#">Home</a></li>
  </ul>
</nav>
```

<h3>article</h3>
The article element is designed to wrap content that can stand on its own:

```
<article></article>
```

<h4>Description</h4>
The article element is a new element introduced in HTML5. The article element
is similar to the section element; in that, it denotes that the content in the element
is the core part of the page. The article element should be a complete composition
that can stand on its own. For example, in a blog, the actual blog post should be
wrapped with an article element.

Content can then be further broken down using either an article element or a
section element. There is no standard rule for when to use either. However, both
should be related to the content in the outer article element.
Here is an example of the article element being used:

```
<article>
<header>
<h1>Blog Post</h1>
</header>
<p>This post covers how to use an article element...</p>
<footer>
<address>
Contact the author, Joshua
</address>
<footer>
</article>
```

<h3>Headings</h3>
The heading elements are the elements that specify different levels of headings
according to their importance:

```
<h1></h1>
<h2></h2>
<h3></h3>
<h4></h4>
<h5></h5>
<h6></h6>
```

<h4>Description</h4>
These should be used to give relative importance to different headings. For example,
h1 should be used for the title of the document. The importance of a heading goes
down as the heading value goes up, that is, h6 is the least important level of heading
in the example that follows.

Here is an example using all the headings:

```
<h1>Heading Importance 1</h1>
<h2>Heading Importance 2</h2>
<h3>Heading Importance 3</h3>
<h4>Heading Importance 4</h4>
<h5>Heading Importance 5</h5>
<h6>Heading Importance 6</h6>
```

<h4>See also</h4>
You can also refer to the global attributes to learn the heading element in more
detail.

<h3>header</h3>
The header element groups the content that is considered to be the header for a
particular group of content, its syntax is as follows:

```
<header></header>
```

<h4>Description</h4>
The header element is usually one of the first content elements on the page. It will
most likely contain navigation options, a logo, and/or a search box. The header
is usually repeated on multiple pages of a website. Each section or article can also
contain a header. This is a new element introduced in HTML5.
Here is an example of the header element:

```
<header>
<img src="logo.png" />
</header>
```

<h4>See also</h4>
You can also refer to the global attributes to find out about the header element in
more detail.

<h3>footer</h3>
The footer element provides a footer of a particular group of content, its syntax is as
follows:

```
<footer></footer>
```

<h4>Description</h4>
The footer element wraps all the content that is considered to be the footer of the
document. Usually, this will include copyright, author, and/or social media links. Of
course, what you decide to put into a footer is arbitrary. Each section or article can
also contain a footer.

<h4>Here is an example of the footer element:</h4>

```
<footer>
  Written by: Joshua Johanan
</footer>
```

<h3>address</h3>
The address element is used for the contact address of the author or organization, its
syntax is as follows:

```
<address></address>
```

<h4>Description</h4>

Use the address element when you have the contact information of the user. The
address element will add semantic value to the content, contrary to a regular div
element.
Usually, this will be placed in the footer, but it can be used in an article or body
section. It will apply to the nearest article element or to the entire document. Do
not use any of the content section elements in an address element.
Here is the address element in use:

```
<footer>
<address>
Please contact me at my <a href="#">website</a>
</address>
</footer>
```



