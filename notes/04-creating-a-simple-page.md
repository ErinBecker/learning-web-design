# Notes

## What Browsers Ignore
- multiple white spaces are colapsed to a single space
- line breaks are converted to white spaces
- tags that are incorrect are ignored
- comment tags <!-- -->

## Vocab
element - tag-content-tag
tag - the stuff in the <>s
content - the stuff between the <>s
block element
inline element
empty element
attribute - instructions that clarify or modify an element

## General
- capitalization of element names is not important in HTML, but it is in XHTML
- the title gets displayed in the browser tab
- don't select elements based on how they look, but on whether they make sense for the structure of the document
- you can change appearance of element types with a style sheet
- using proper semantic markup makes you page easier for screen readers to parse
- headings and paragraphs are block elements
- em elements are inline elements (don't start a new line)
- attributes go in the opening tag only
- attribute syntax:
    <element attributename="value">
- attribute order within an element is not important
- src and alt attributes are required for img elements
- src gives location of image file
- alt gives text to display if image is not available


## Minimal structure of all HTML documents

<!DOCTYPE html>

<html>

<head>
<meta charset="utf-8">
<title>Title here</title>
</head>

<body>
Page content goes here.
</body>

</html>

# Empty elements
<br>
<imb>
<hr>

