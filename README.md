Markdown Cheatsheet
===================

A Brief History of Markdown
---------------------------

Markdown was created by John Gruber in 2004 as a standard for marking up
plain-text documents in as natural a way as possible so that it could then be
converted to HTML. One of the goals of markdown was that the original markdown
file was still human-readable.

Some Preliminaries
------------------

First off, enclosing text in backticks \`text\` prevents the text from being
interpreted as markdown. It is typically used for code. Secondly, you can
prevent multiple lines of text from being interpreted by enclosing the group of
lines in a "fence" of three backticks, or by indenting each line by four spaces.

```
these
lines
are
fenced
```

    these
    lines
    are
    indented

Finally, you can prevent an individual character from being interpreted by
prefacing it with a blackslash "\".

Headings
--------

```
First-Level Heading (preferred)
===============================

Second-Level Heading (preferred)
--------------------------------

# First-Level Heading

## Second-Level Heading

### Third-Level Heading

#### Fourth-Level Heading

##### Fifth-Level Heading

###### Sixth-Level Heading
```

Paragraphs
----------

Paragraphs have a blank line before and after the text, unless the paragraph is
at the start of the document. Typically, paragraphs are styled so that they have
a margin between them. In cases where you don't want a margin between the lines
(for example, a mailing address), you need to leave two spaces at the end of the
line. With the extra spaces, the paragraph will just continue like normal.

1234 Street Ave
Prince George, BC
V2N 4J2

Emphasizing Text
----------------

You can emphasize text by enclosing the text in asterisks "\*".

- One pair of asterisks makes the text *italicized* (\*italicized\*)
- A second pair of asterisks makes the text **bold** (\*\*bold\*\*)
- A third pair of asterisks makes the text ***both*** (\*\*\*both\*\*\*)

Lists
-----

- this is a list element that starts with a hyphen (preferred)
+ but list items can also start with a plus "+" sign
* or an asterisk, and you can mix-and-match (but it's not recommended)

Links
-----

A link consists of two parts, the link body, and the link URL. It's best
practice to have descriptive body text. "World Cup finals results" is better
than "Click here" as it describes what information the user will find when they
click on the link.

A normal link in markdown looks like `[link body](link URL)`.

This is a paragraph that contains a [link](http://www.longurlmaker.com/go?id=015nSitelutionsw1oMetamark0179331outstretchedsustainedfar%2BoffURL)
to some cool stuff on the Internet.

```
This is a paragraph that contains a [link](http://www.longurlmaker.com/go?id=015nSitelutionsw1oMetamark0179331outstretchedsustainedfar%2BoffURL)
to some cool stuff on the Internet.
```

### Reference-style links

Alternatively, you can use reference-style links. This allows you to define the
link reference in the document and then use the reference to make a link. Two
advantages to this method are that you can define a link once and reference it
many times, and it can make text containing links more readable.

This is a paragraph that contains a reference-style [link][link-ref] which links
to the same URL, but is easier to read when viewing the markdown. The link URL
is defined below this paragraph with the ID "link-ref".

[link-ref]: http://www.longurlmaker.com/go?id=015nSitelutionsw1oMetamark0179331outstretchedsustainedfar%2BoffURL

```
This is a paragraph that contains a reference-style [link][link-ref] which links
to the same URL, but is easier to read when viewing the markdown. The link URL
is defined below this paragraph with the ID "link-ref".

[link-ref]: http://www.longurlmaker.com/go?id=015nSitelutionsw1oMetamark0179331outstretchedsustainedfar%2BoffURL
```
