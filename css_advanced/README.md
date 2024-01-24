## CSS ADVANCED

## What is CSS?

CSS is not a “programming language” either, as you can’t program a computer to do everything you want with it, it is a “stylesheet language”; its only purpose is to apply style to HTML documents.

To write CSS code, you just write “CSS rules”, each of which contain two things:

First, what HTML tags you want to apply styling to (for instance: all links, all images, all paragraphs, etc.). This part of the CSS rule is called “the selector”, because it allows you to select what HTML tags you want to style.
Second, what styling you want to apply to them (for instance: have the text be a certain color, have it display in bold or italic characters, have the background be an image, …). This part is called setting the CSS properties.
For instance:

a {
  color: red;
}
This piece of CSS selects all links in the page (the selector targets the <a> tags), and sets one property to them: they have to be red.

You can have several properties in the same selector. For instance

a {
  color: red;
  font-weight: bold;
}
Links will now be red and bold.

You can also have several selectors per rule, for instance:

a, h1 {
  color: red;
  font-weight: bold;
}
All links and level-1 headings will be red and bold.

The list of existing CSS properties is pretty straightforward, but selectors can get pretty smart. For instance:

if you want to be selecting only a few links of your choosing, you can add a “class” attribute to them (like this: <a class="active_page">), and select only those ones, using the a.active_page selector. This works with absolutely all existing HTML tags, and you can use any class name you like.
if you want to select only the links pointed to webpages that were previously visited by your user, you can use the selector a:visited. “:visited” is called a pseudo-class. Another nice pseudo-class is “:hover”, for HTML tags that the user currently has her mouse on.

## CSS WebPage to copy Final View

![image](https://github.com/Moonwalkert3ch/atlas-web-development/assets/132849866/e0b66bed-7001-47e4-8665-e6f90bf0d289)
