Anchor Elements
---
To create a link in HTML, we use the anchor element. An anchor element is defined by wrapping the text or another HTML element we want to be a link with an <a> tag.
To tel the anchor element where to link it, we need to use HTML attribute called `href`. Without this attribute anchor tag will look like a plain text.

! An attribute is usually made up of two parts: a name, and a value; however, not all attributes require a value.

! Default behaviour of most browsers is when tou clicked a link it opens it in the same page (or tab). To change this behaviour we need to use `target` attribute.

While `href` specifies the destination link, `target` specifies where the linked resource will be opened. If it is not present, then, by default, it will take on the `_self` value which opens the link in the current tab. To open the link in a new tab or window (depends on browser settings) you can set it to `_blank`.

! `rel` attribute means relation between current page and the linked document. Example of `rel` attributes values:

`noopener`: The noopener value of the `rel` attribute ensures that a link opened in a new tab or window cannot interact with or access the original page. Without it, the new page can use JavaScript to manipulate the original page, which poses a security risk.

`noreferrer`: The `noreferrer` value of the `rel` attribute provides both privacy and security. It prevents the new page from knowing where the user came from (hiding the referrer) and also includes the behavior of `noopener`, preventing the new page from accessing the original page.

Absolute links: other webpages `scheme://domain/path`
Relative links: inside of our webpage

`<img>` element is a void element. It embeds image using `src` attribute.

! `alt` attribute is used to describe image if it is not loaded somehow or to impaired users.

! You can change the size of image using `width` and `height` attributes.
