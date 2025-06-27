- Almost all elements on an HTML page are just pieces of content wrapped in opening and closing HTML tags. E.g.
```html
<p> this is a paragpraph </p>
```

- Using the correct tags can have a big impact on two aspects of your sites:
  1. How they are ranked in search engines
  2. How accessible they are to users who rely on assistive technologies, like screen readers, to use the internet.

Using the correct elements for content is called semantic HTML. We will explore this in much more depth later on in the curriculum.

- Some HTML elements do not have a closing tag. These elements are called as 'void elements'.
```html
<img>,  <br> ...
```

! You might also see these referred to as self-closing tags. But those are just void elements with a forward slash(/) at the end like: `<br />` or `<img />`. You’re likely to see self-closing tags used often for historical reasons. Browsers will be able to render them just fine, but the latest version of the HTML specification discourages their use and considers them invalid.

HTML Boilerplate
---
- It is worth noting that we named our HTML file `index`. We should always name the HTML file that will contain the homepage of our website `index.html`. This is because web servers will by default look for an `index.html` page when users land on our websites – and not having one will cause big problems.

- After we declare the doctype, we need to provide an <html> element. This is what’s known as the root element of the document, meaning that every other element in the document will be a descendant of it. This becomes more important later on when we learn about manipulating HTML with JavaScript. For now, just know that the <html> element should be included on every HTML document.

- The <head> element is where we put important meta-information about our webpages, and stuff required for our webpages to render correctly in the browser. Inside the <head>, we should not use any element that displays content on the webpage.

- The final element needed to complete the HTML boilerplate is the <body> element. This is where all the content that will be displayed to users will go - the text, images, lists, links, and so on.

Working with Text
---
- If we want to create paragraphs in HTML, we need to use the paragraph element, which will add a new line after each of our paragraphs. A paragraph element is defined by wrapping text content with a `<p>` tag.

- Headings are different from other HTML text elements: they are displayed larger and bolder than other text to signify that they are headings. There are 6 different levels of headings starting from `<h1>` to `<h6>`. The number within a heading tag represents that heading’s level. The largest and most important heading is h1, while h6 is the tiniest heading at the lowest level.

- The `<strong>` element makes text bold. It also semantically marks text as important; this affects tools, like screen readers, that users with visual impairments will rely on to use your website. The tone of voice on some screen readers will change to communicate the importance of the text within a strong element. To define a strong element, we wrap text content in a `<strong>` tag.

! Sometimes you will want to make text bold without giving it an important meaning. You’ll learn how to do that in the CSS lessons later in the curriculum.

- The `<em>` element makes text italic. It also semantically places emphasis on the text, which again may affect things like screen readers. To define an emphasised element, wrap the text content in an `<em>` tag.

- When we nest elements within other elements, we create a parent and child relationship between them. The nested elements are the children and the element they are nested within is the parent.

- HTML comments are not visible to the browser; they allow us to comment on our code so that other developers or our future selves can read them and get some context about something that might not be clear in the code.
