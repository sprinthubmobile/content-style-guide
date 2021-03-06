# Welcome to the Sprinthub Content Style Guide

This style guide is primarily for Sprinthub employees, but we hope it’s helpful to other organizations as well.

If you're looking for the Sprinthub Content Style Guide website, visit [styleguide.sprinthubmobile.com](http://styleguide.sprinthubmobile.com).

Whether or not you work at Sprinthub, we welcome your thoughts and suggestions. To learn more about sending us feedback or adapting this guide to create your own, see the Contributing file.

## Modifying the Guide

You can change this guide by adding new files to, or modifying the files in, the `content/guides` directory.
This guide is a collection of Markdown files. This is a plaintext format that easily converts to HTML. Read more about it [here](http://daringfireball.net/projects/markdown/). Be sure you name your files without spaces with either an `.md` or `.markdown` extension.

This guide is built using Hugo, the static site generator. Learning how to use Hugo will help
you become more efficient in modifying this guide.

When changes are committed to the master branch, the guide is updated automatically.

## Markdown

Markdown is handy because you can write your content without HTML tags. Here are some tips to help you control the layout of your text.

### Line Breaks

If you want a line to break to the next line but don’t want to start a new paragraph, end the line with two spaces. This will render a `<br>` tag.

### Widows

The best way to prevent widows is to type `&nbsp;` in the space between the last two words in a title or paragraph.

### Tables

Tables can be written in Markdown by following this general style:

```markdown
| header 1 | header 2 |
| -------- | -------- |
| cell 1   | cell 2   |
| cell 3   | cell 4   |
```

The spacing is not important for the table to be rendered properly, and the cells do not have to line up. However it does help with readability when creating and editing tables.

### HTML Tags in Text

When displaying HTML tags as text in content, be sure to wrap them in backticks, eg: \``<h3>`\`.
