a# Lesson 4: Elements & Attributes

Read this first: https://www.w3schools.com/html/html_elements.asp
And this: https://www.w3schools.com/html/html_attributes.asp

Element: An HTML element is defined by a start tag, some content, and an end tag.
Attribute: HTML attributes provide additional information about HTML elements.

This is an element: `<p>This is some text</p>`

In it, you can see:
- a start tag: `<p>` letting you know the element is starting
- some content that will be displayed on screen: `This is some text`
- a close tag `</p>` letting you know the element is ending

This is an attribute: `href="https://www.google.com"`. This is specifically an attribute for an anchor tag `<a></a>`. Anchor tags point you to another web page on the internet. But without extra information (an attribute) describing that interaction, the anchor tag will not know what to do. Here's the complete example:

`<a href="https://www.google.com>Google</a>`;

Here you see:
- a start tag `<a>`
- *inside* that tag you have an attribute describing where the anchor tag is supposed to go: `href="https://www.google.com"`
- you see some content that will be displayed on screen `Google`
- and the end tag `</a>` letting you know the element is ending

Here's another example:

`<img src='images/john-smith-professional-headshot.jpg' alt="John Smith's Professional Headshot" />`

The `<img />` element is self-closing, but on it's own just states that there *should* be an image on the screen, but without the **attributes** the browser doesn't have enough information to do anything.

So we add the `src=""` attribute to point at the source of the image, which is a file on our machine.

and the `alt=""` attribute to add some alternate text in case the image fails to load.

Your assignment for this lesson is to:
1. Add a heading 1 to the header with your name in it
2. Create a folder in `src` called `images`
3. Put an image of yourself from your PC in the newly created `src/images` folder
4. Add that image to the main section of your website with an alternate text of your name
5. Add a link to the navigation section that takes you to MSN.com, the link should read "MSN" on screen

When you are finished:
1. Add you code to a commit
2. commit your code
3. push your code to GitHub