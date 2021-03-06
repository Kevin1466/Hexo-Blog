---
title: markdown test
date: 2020-02-12 21:08:43
tags:
---
## Overview[](https://www.markdownguide.org/basic-syntax/#overview)

Nearly all Markdown applications support the basic syntax outlined in John Gruber’s original design document. There are minor variations and discrepancies between Markdown processors — those are noted inline wherever possible.
<!--more-->
## Headings[](https://www.markdownguide.org/basic-syntax/#headings)

To create a heading, add number signs (`#`) in front of a word or phrase. The number of number signs you use should correspond to the heading level. For example, to create a heading level three (`<h3>`), use three number signs (e.g., `### My Header`).

| Markdown | HTML | Rendered Output |
| --- | --- | --- |
| `# Heading level 1` | `<h1>Heading level 1</h1>` | 

# Heading level 1

 |
| `## Heading level 2` | `<h2>Heading level 2</h2>` | 

## Heading level 2

 |
| `### Heading level 3` | `<h3>Heading level 3</h3>` | 

### Heading level 3

 |
| `#### Heading level 4` | `<h4>Heading level 4</h4>` | 

#### Heading level 4

 |
| `##### Heading level 5` | `<h5>Heading level 5</h5>` | 

##### Heading level 5

 |
| `###### Heading level 6` | `<h6>Heading level 6</h6>` | 

###### Heading level 6

 |

### Alternate Syntax[](https://www.markdownguide.org/basic-syntax/#alternate-syntax)

Alternatively, on the line below the text, add any number of `==` characters for heading level 1 or `--` characters for heading level 2.

| Markdown | HTML | Rendered Output |
| --- | --- | --- |
| `Heading level 1
===============` | `<h1>Heading level 1</h1>` | 

# Heading level 1

 |
| `Heading level 2
---------------` | `<h2>Heading level 2</h2>` | 

## Heading level 2

 |

## Paragraphs[](https://www.markdownguide.org/basic-syntax/#paragraphs-1)

To create paragraphs, use a blank line to separate one or more lines of text. You should not indent paragraphs with spaces or tabs.

| Markdown | HTML | Rendered Output |
| --- | --- | --- |
| `I really like using Markdown.

I think I'll use it to format all of my documents from now on.` | `<p>I really like using Markdown.</p>

<p>I think I'll use it to format all of my documents from now on.</p>` | 

I really like using Markdown.

I think I'll use it to format all of my documents from now on.

 |

## Line Breaks[](https://www.markdownguide.org/basic-syntax/#line-breaks)

To create a line break (`<br>`), end a line with two or more spaces, and then type return.

| Markdown | HTML | Rendered Output |
| --- | --- | --- |
| `This is the first line.  
And this is the second line.` | `<p>This is the first line.<br>
And this is the second line.</p>` | 

This is the first line.
And this is the second line.

 |

## Emphasis[](https://www.markdownguide.org/basic-syntax/#emphasis)

You can add emphasis by making text bold or italic.

### Bold[](https://www.markdownguide.org/basic-syntax/#bold)

To bold text, add two asterisks or underscores before and after a word or phrase. To bold the middle of a word for emphasis, add two asterisks without spaces around the letters.

| Markdown | HTML | Rendered Output |
| --- | --- | --- |
| `I just love **bold text**.` | `I just love <strong>bold text</strong>.` | I just love **bold text**. |
| `I just love __bold text__.` | `I just love <strong>bold text</strong>.` | I just love **bold text**. |
| `Love**is**bold` | `Love<strong>is</strong>bold` | Love**is**bold |

### Italic[](https://www.markdownguide.org/basic-syntax/#italic)

To italicize text, add one asterisk or underscore before and after a word or phrase. To italicize the middle of a word for emphasis, add one asterisk without spaces around the letters.

| Markdown | HTML | Rendered Output |
| --- | --- | --- |
| `Italicized text is the *cat's meow*.` | `Italicized text is the <em>cat's meow</em>.` | Italicized text is the *cat’s meow*. |
| `Italicized text is the _cat's meow_.` | `Italicized text is the <em>cat's meow</em>.` | Italicized text is the *cat’s meow*. |
| `A*cat*meow` | `A<em>cat</em>meow` | A*cat*meow |

### Bold and Italic[](https://www.markdownguide.org/basic-syntax/#bold-and-italic)

To emphasize text with bold and italics at the same time, add three asterisks or underscores before and after a word or phrase.

| Markdown | HTML | Rendered Output |
| --- | --- | --- |
| `This text is ***really important***.` | `This text is <strong><em>really important</em></strong>.` | This text is ***really important***. |
| `This text is ___really important___.` | `This text is <strong><em>really important</em></strong>.` | This text is ***really important***. |
| `This text is __*really important*__.` | `This text is <strong><em>really important</em></strong>.` | This text is ***really important***. |
| `This text is **_really important_**.` | `This text is <strong><em>really important</em></strong>.` | This text is ***really important***. |

## Blockquotes[](https://www.markdownguide.org/basic-syntax/#blockquotes-1)

To create a blockquote, add a `>` in front of a paragraph.

```
> Dorothy followed her through many of the beautiful rooms in her castle.

```

The rendered output looks like this:

> Dorothy followed her through many of the beautiful rooms in her castle.

### Blockquotes with Multiple Paragraphs[](https://www.markdownguide.org/basic-syntax/#blockquotes-with-multiple-paragraphs)

Blockquotes can contain multiple paragraphs. Add a `>` on the blank lines between the paragraphs.

```
> Dorothy followed her through many of the beautiful rooms in her castle.
>
> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

```

The rendered output looks like this:

> Dorothy followed her through many of the beautiful rooms in her castle.
> 
> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

### Nested Blockquotes[](https://www.markdownguide.org/basic-syntax/#nested-blockquotes)

Blockquotes can be nested. Add a `>>` in front of the paragraph you want to nest.

```
> Dorothy followed her through many of the beautiful rooms in her castle.
>
>> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

```

The rendered output looks like this:

> Dorothy followed her through many of the beautiful rooms in her castle.
> 
> > The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

### Blockquotes with Other Elements[](https://www.markdownguide.org/basic-syntax/#blockquotes-with-other-elements)

Blockquotes can contain other Markdown formatted elements. Not all elements can be used — you’ll need to experiment to see which ones work.

```
> #### The quarterly results look great!
>
> - Revenue was off the chart.
> - Profits were higher than ever.
>
>  *Everything* is going according to **plan**.

```

The rendered output looks like this:

> #### The quarterly results look great!
> 
> *   Revenue was off the chart.
> *   Profits were higher than ever.
> 
> *Everything* is going according to **plan**.

## Lists[](https://www.markdownguide.org/basic-syntax/#lists)

You can organize items into ordered and unordered lists.

### Ordered Lists[](https://www.markdownguide.org/basic-syntax/#ordered-lists)

To create an ordered list, add line items with numbers followed by periods. The numbers don’t have to be in numerical order, but the list should start with the number one.

| Markdown | HTML | Rendered Output |
| --- | --- | --- |
| `1\. First item
2\. Second item
3\. Third item
4\. Fourth item` | `<ol>
<li>First item</li>
<li>Second item</li>
<li>Third item</li>
<li>Fourth item</li>
</ol>` | 

1.  First item
2.  Second item
3.  Third item
4.  Fourth item

 |
| `1\. First item
1\. Second item
1\. Third item
1\. Fourth item` | `<ol>
<li>First item</li>
<li>Second item</li>
<li>Third item</li>
<li>Fourth item</li>
</ol>` | 

1.  First item
2.  Second item
3.  Third item
4.  Fourth item

 |
| `1\. First item
8\. Second item
3\. Third item
5\. Fourth item` | `<ol>
<li>First item</li>
<li>Second item</li>
<li>Third item</li>
<li>Fourth item</li>
</ol>` | 

1.  First item
2.  Second item
3.  Third item
4.  Fourth item

 |
| `1\. First item
2\. Second item
3\. Third item
    1\. Indented item
    2\. Indented item
4\. Fourth item` | `<ol>
<li>First item</li>
<li>Second item</li>
<li>Third item
<ol>
<li>Indented item</li>
<li>Indented item</li>
</ol>
</li>
<li>Fourth item</li>
</ol>` | 

1.  First item
2.  Second item
3.  Third item
    1.  Indented item
    2.  Indented item
4.  Fourth item

 |

### Unordered Lists[](https://www.markdownguide.org/basic-syntax/#unordered-lists)

To create an unordered list, add dashes (`-`), asterisks (`*`), or plus signs (`+`) in front of line items. Indent one or more items to create a nested list.

| Markdown | HTML | Rendered Output |
| --- | --- | --- |
| `- First item
- Second item
- Third item
- Fourth item` | `<ul>
<li>First item</li>
<li>Second item</li>
<li>Third item</li>
<li>Fourth item</li>
</ul>` | 

*   First item
*   Second item
*   Third item
*   Fourth item

 |
| `* First item
* Second item
* Third item
* Fourth item` | `<ul>
<li>First item</li>
<li>Second item</li>
<li>Third item</li>
<li>Fourth item</li>
</ul>` | 

*   First item
*   Second item
*   Third item
*   Fourth item

 |
| `+ First item
* Second item
- Third item
+ Fourth item` | `<ul>
<li>First item</li>
<li>Second item</li>
<li>Third item</li>
<li>Fourth item</li>
</ul>` | 

*   First item
*   Second item
*   Third item
*   Fourth item

 |
| `- First item
- Second item
- Third item
    - Indented item
    - Indented item
- Fourth item` | `<ul>
<li>First item</li>
<li>Second item</li>
<li>Third item
<ul>
<li>Indented item</li>
<li>Indented item</li>
</ul>
</li>
<li>Fourth item</li>
</ul>` | 

*   First item
*   Second item
*   Third item
    *   Indented item
    *   Indented item
*   Fourth item

 |

### Adding Elements in Lists[](https://www.markdownguide.org/basic-syntax/#adding-elements-in-lists)

To add another element in a list while preserving the continuity of the list, indent the element four spaces or one tab, as shown in the following examples.

#### Paragraphs[](https://www.markdownguide.org/basic-syntax/#paragraphs)

```
*   This is the first list item.
*   Here's the second list item.

    I need to add another paragraph below the second list item.

*   And here's the third list item.

```

The rendered output looks like this:

*   This is the first list item.
*   Here’s the second list item.

    I need to add another paragraph below the second list item.

*   And here’s the third list item.

#### Blockquotes[](https://www.markdownguide.org/basic-syntax/#blockquotes)

```
*   This is the first list item.
*   Here's the second list item.

    > A blockquote would look great below the second list item.

*   And here's the third list item.

```

The rendered output looks like this:

*   This is the first list item.
*   Here’s the second list item.

    > A blockquote would look great below the second list item.

*   And here’s the third list item.

#### Code Blocks[](https://www.markdownguide.org/basic-syntax/#code-blocks-1)

[Code blocks](https://www.markdownguide.org/basic-syntax/#code-blocks) are normally indented four spaces or one tab. When they’re in a list, indent them eight spaces or two tabs.

```
1\.  Open the file.
2\.  Find the following code block on line 21:

        <html>
          <head>
            <title>Test</title>
          </head>

3\.  Update the title to match the name of your website.

```

The rendered output looks like this:

1.  Open the file.
2.  Find the following code block on line 21:

    ```
    <html>
      <head>
        <title>Test</title>
      </head>

    ```

3.  Update the title to match the name of your website.

#### Images[](https://www.markdownguide.org/basic-syntax/#images)

```
1\.  Open the file containing the Linux mascot.
2\.  Marvel at its beauty.

    ![Tux, the Linux mascot](/assets/images/tux.png)

3\.  Close the file.

```

The rendered output looks like this:

1.  Open the file containing the Linux mascot.
2.  Marvel at its beauty.

    ![Tux, the Linux mascot](https://upload-images.jianshu.io/upload_images/1971289-50ba52a81646041e.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

3.  Close the file.

## Code[](https://www.markdownguide.org/basic-syntax/#code)

To denote a word or phrase as code, enclose it in backticks (```).

| Markdown | HTML | Rendered Output |
| --- | --- | --- |
| `At the command prompt, type `nano`.` | `At the command prompt, type <code>nano</code>.` | At the command prompt, type `nano`. |

### Escaping Backticks[](https://www.markdownguide.org/basic-syntax/#escaping-backticks)

If the word or phrase you want to denote as code includes one or more backticks, you can escape it by enclosing the word or phrase in double backticks (````).

| Markdown | HTML | Rendered Output |
| --- | --- | --- |
| ```Use `code` in your Markdown file.``` | `<code>Use `code` in your Markdown file.</code>` | `Use `code` in your Markdown file.` |

### Code Blocks[](https://www.markdownguide.org/basic-syntax/#code-blocks)

To create code blocks, indent every line of the block by at least four spaces or one tab.

```
    <html>
      <head>
      </head>
    </html>

```

The rendered output looks like this:

```
<html>
  <head>
  </head>
</html>

```

 **Note:** To create code blocks without indenting lines, use [fenced code blocks](https://www.markdownguide.org/extended-syntax/#fenced-code-blocks).

## Horizontal Rules[](https://www.markdownguide.org/basic-syntax/#horizontal-rules)

To create a horizontal rule, use three or more asterisks (`***`), dashes (`---`), or underscores (`___`) on a line by themselves.

```
***

---

_________________

```

The rendered output of all three looks identical:

* * *

## Links[](https://www.markdownguide.org/basic-syntax/#links)

To create a link, enclose the link text in brackets (e.g., `[Duck Duck Go]`) and then follow it immediately with the URL in parentheses (e.g., `(https://duckduckgo.com)`).

```
My favorite search engine is [Duck Duck Go](https://duckduckgo.com).

```

The rendered output looks like this:

My favorite search engine is [Duck Duck Go](https://duckduckgo.com/).

### Adding Titles[](https://www.markdownguide.org/basic-syntax/#adding-titles)

You can optionally add a title for a link. This will appear as a tooltip when the user hovers over the link. To add a title, enclose it in parentheses after the URL.

```
My favorite search engine is [Duck Duck Go](https://duckduckgo.com "The best search engine for privacy").

```

The rendered output looks like this:

My favorite search engine is [Duck Duck Go](https://duckduckgo.com/ "The best search engine for privacy").

### URLs and Email Addresses[](https://www.markdownguide.org/basic-syntax/#urls-and-email-addresses)

To quickly turn a URL or email address into a link, enclose it in angle brackets.

```
<https://www.markdownguide.org>
<fake@example.com>

```

The rendered output looks like this:

[https://www.markdownguide.org](https://www.markdownguide.org/)
[fake@example.com](mailto:fake@example.com)

### Formatting Links[](https://www.markdownguide.org/basic-syntax/#formatting-links)

To [emphasize](https://www.markdownguide.org/basic-syntax/#emphasis) links, add asterisks before and after the brackets and parentheses. To denote links as [code](https://www.markdownguide.org/basic-syntax/#code), add backticks in the brackets.

```
I love supporting the **[EFF](https://eff.org)**.
This is the *[Markdown Guide](https://www.markdownguide.org)*.
See the section on [`code`](#code).

```

The rendered output looks like this:

I love supporting the **[EFF](https://eff.org/)**.
This is the *[Markdown Guide](https://www.markdownguide.org/)*.
See the section on [`code`](https://www.markdownguide.org/basic-syntax/#code).

### Reference-style Links[](https://www.markdownguide.org/basic-syntax/#reference-style-links)

Reference-style links are a special kind of link that make URLs easier to display and read in Markdown. Reference-style links are constructed in two parts: the part you keep inline with your text and the part you store somewhere else in the file to keep the text easy to read.

#### Formatting the First Part of the Link[](https://www.markdownguide.org/basic-syntax/#formatting-the-first-part-of-the-link)

The first part of a reference-style link is formatted with two sets of brackets. The first set of brackets surrounds the text that should appear linked. The second set of brackets displays a label used to point to the link you’re storing elsewhere in your document.

Although not required, you can include a space between the first and second set of brackets. The label in the second set of brackets is not case sensitive and can include letters, numbers, spaces, or punctuation.

This means the following example formats are roughly equivalent for the first part of the link:

*   `[hobbit-hole][1]`
*   `[hobbit-hole] [1]`

#### Formatting the Second Part of the Link[](https://www.markdownguide.org/basic-syntax/#formatting-the-second-part-of-the-link)

The second part of a reference-style link is formatted with the following attributes:

1.  The label, in brackets, followed immediately by a colon and at least one space (e.g., `[label]: `).
2.  The URL for the link, which you can optionally enclose in angle brackets.
3.  The optional title for the link, which you can enclose in double quotes, single quotes, or parentheses.

This means the following example formats are all roughly equivalent for the second part of the link:

*   `[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle`
*   `[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle "Hobbit lifestyles"`
*   `[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle 'Hobbit lifestyles'`
*   `[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle (Hobbit lifestyles)`
*   `[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> "Hobbit lifestyles"`
*   `[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> 'Hobbit lifestyles'`
*   `[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> (Hobbit lifestyles)`

You can place this second part of the link anywhere in your Markdown document. Some people place them immediately after the paragraph in which they appear while other people place them at the end of the document (like endnotes or footnotes).

#### An Example Putting the Parts Together[](https://www.markdownguide.org/basic-syntax/#an-example-putting-the-parts-together)

Say you add a URL as a [standard URL link](https://www.markdownguide.org/basic-syntax/#links) to a paragraph and it looks like this in Markdown:

```
In a hole in the ground there lived a hobbit. Not a nasty, dirty, wet hole, filled with the ends
of worms and an oozy smell, nor yet a dry, bare, sandy hole with nothing in it to sit down on or to
eat: it was a [hobbit-hole](https://en.wikipedia.org/wiki/Hobbit#Lifestyle "Hobbit lifestyles"), and that means comfort.

```

Though it may point to interesting additional information, the URL as displayed really doesn’t add much to the existing raw text other than making it harder to read. To fix that, you could format the URL like this instead:

```
In a hole in the ground there lived a hobbit. Not a nasty, dirty, wet hole, filled with the ends
of worms and an oozy smell, nor yet a dry, bare, sandy hole with nothing in it to sit down on or to
eat: it was a [hobbit-hole][1], and that means comfort.

[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> "Hobbit lifestyles"

```

In both instances above, the rendered output would be identical:

> In a hole in the ground there lived a hobbit. Not a nasty, dirty, wet hole, filled with the ends of worms and an oozy smell, nor yet a dry, bare, sandy hole with nothing in it to sit down on or to eat: it was a [hobbit-hole](https://en.wikipedia.org/wiki/Hobbit#Lifestyle "Hobbit lifestyles"), and that means comfort.

and the HTML for the link would be:

```
<a href="https://en.wikipedia.org/wiki/Hobbit#Lifestyle" title="Hobbit lifestyles">hobbit-hole</a>

```

## Images[](https://www.markdownguide.org/basic-syntax/#images-1)

To add an image, add an exclamation mark (`!`), followed by alt text in brackets, and the path or URL to the image asset in parentheses. You can optionally add a title after the URL in the parentheses.

```
![Philadelphia's Magic Gardens. This place was so cool!](/assets/images/philly-magic-gardens.jpg "Philadelphia's Magic Gardens")

```

The rendered output looks like this:

![Philadelphia's Magic Gardens. This place was so cool!](https://upload-images.jianshu.io/upload_images/1971289-30e35c480b161ece.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240 "Philadelphia's Magic Gardens")

### Linking Images[](https://www.markdownguide.org/basic-syntax/#linking-images)

To add a link to an image, enclose the Markdown for the image in brackets, and then add the link in parentheses.

```
[![An old rock in the desert](/assets/images/shiprock.jpg "Shiprock, New Mexico by Beau Rogers")](https://www.flickr.com/photos/beaurogers/31833779864/in/photolist-Qv3rFw-34mt9F-a9Cmfy-5Ha3Zi-9msKdv-o3hgjr-hWpUte-4WMsJ1-KUQ8N-deshUb-vssBD-6CQci6-8AFCiD-zsJWT-nNfsgB-dPDwZJ-bn9JGn-5HtSXY-6CUhAL-a4UTXB-ugPum-KUPSo-fBLNm-6CUmpy-4WMsc9-8a7D3T-83KJev-6CQ2bK-nNusHJ-a78rQH-nw3NvT-7aq2qf-8wwBso-3nNceh-ugSKP-4mh4kh-bbeeqH-a7biME-q3PtTf-brFpgb-cg38zw-bXMZc-nJPELD-f58Lmo-bXMYG-bz8AAi-bxNtNT-bXMYi-bXMY6-bXMYv)

```

The rendered output looks like this:

[![An old rock in the desert](https://upload-images.jianshu.io/upload_images/1971289-7aa74e5b5d6aa7b2.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240 "Shiprock, New Mexico by Beau Rogers")](https://www.flickr.com/photos/beaurogers/31833779864/in/photolist-Qv3rFw-34mt9F-a9Cmfy-5Ha3Zi-9msKdv-o3hgjr-hWpUte-4WMsJ1-KUQ8N-deshUb-vssBD-6CQci6-8AFCiD-zsJWT-nNfsgB-dPDwZJ-bn9JGn-5HtSXY-6CUhAL-a4UTXB-ugPum-KUPSo-fBLNm-6CUmpy-4WMsc9-8a7D3T-83KJev-6CQ2bK-nNusHJ-a78rQH-nw3NvT-7aq2qf-8wwBso-3nNceh-ugSKP-4mh4kh-bbeeqH-a7biME-q3PtTf-brFpgb-cg38zw-bXMZc-nJPELD-f58Lmo-bXMYG-bz8AAi-bxNtNT-bXMYi-bXMY6-bXMYv) 

## Escaping Characters[](https://www.markdownguide.org/basic-syntax/#escaping-characters)

To display a literal character that would otherwise be used to format text in a Markdown document, add a backslash (`\`) in front of the character.

```
\* Without the backslash, this would be a bullet in an unordered list.

```

The rendered output looks like this:

* Without the backslash, this would be a bullet in an unordered list.

### Characters You Can Escape[](https://www.markdownguide.org/basic-syntax/#characters-you-can-escape)

You can use a backslash to escape the following characters.

| Character | Name |
| --- | --- |
| \ | backslash |
| ` | backtick (see also [escaping backticks in code](https://www.markdownguide.org/basic-syntax/#escaping-backticks)) |
| * | asterisk |
| _ | underscore |
| { } | curly braces |
| [ ] | brackets |
| ( ) | parentheses |
| # | pound sign |
| + | plus sign |
| - | minus sign (hyphen) |
| . | dot |
| ! | exclamation mark |
| | | pipe (see also [escaping pipe in tables](https://www.markdownguide.org/extended-syntax/#escaping-pipe-characters-in-tables)) |

## HTML[](https://www.markdownguide.org/basic-syntax/#html)

Many Markdown applications allow you to use HTML tags in Markdown-formatted text. This is helpful if you prefer certain HTML tags to Markdown syntax. For example, some people find it easier to use HTML tags for images. Using HTML is also helpful when you need to change the attributes of an element, like specifying the color of text or changing the width of an image.

To use HTML, place the tags in the text of your Markdown-formatted file.

```
This **word** is bold. This <em>word</em> is italic.

```

The rendered output looks like this:

This **word** is bold. This *word* is italic.

### Limitations[](https://www.markdownguide.org/basic-syntax/#limitations)

For security reasons, not all Markdown applications support HTML in Markdown documents. When in doubt, check your Markdown application’s documentation. Some applications support only a subset of HTML tags.

Use blank lines to separate block-level HTML elements like `<div>`, `<table>`, `<pre>`, and `<p>` from the surrounding content. Try not to indent the tags with tabs or spaces — that can interfere with the formatting.

You can’t use Markdown syntax inside block-level HTML tags. For example, `<p>italic and **bold**</p>` won’t work.
