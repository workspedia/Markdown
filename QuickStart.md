in order for editors or applications to make sure that the file they are using is Markdown-formatted,  
we could use some of the most common file extensions, such as .md, .mkdn, or .markdown.  
### Step 1 – Inserting paragraph and line breaks
### Step 2 – Inserting headers #  
There are two styles for declaring headers in Markdown: setext and atx.  
#### Setext style  
header 1  
--------
#### Atx style  
##### header 5  
### Step 3 – Inserting emphasis  
Markdown treats asterisks (*) and underscores (_) as indicators of emphasis. A single symbol is  
used for italics and a double symbol for bold:  
*single asterisks*  
_single underscores_  
**double asterisks**  
__double underscores__  
### Step 4 – Inserting lists  
#### Ordered lists  
Ordered lists use numbers as list markers:  
1. One  
2. Two  
6. Six
#### Unordered lists
Unordered lists use asterisks (*), plus signs (+), and hyphens (-) as list markers:
* A list.  
* Second element.
+ A new entry.
- Another entry in a list.
- And the list goes on.

#### Nested lists
List can be nested as follows:

- First level
  - Second level
    - Third level
  - Second level again  

### Step 5 – Inserting links
Markdown supports two styles of links: inline and reference.  
In both styles, the link text is delimited by square brackets ([ and ]) and the title attribute is optional.  
Inline
An example is shown as follows:  
An example of [inline link](http://example.com "Example").  
[This link](http://example.net/) has no title attribute.

Reference
This is [an example][a] reference-style link.
This is [an example] [b] reference-style link.

[a]: http://baidu.com/ "Optional Title Here"
[b]: http://example.com/ 'Optional Title Here'
[c]: http://example.com/ (Optional Title Here)

### Step 6 – Inserting automatic links  
Creating automatic links is possible by wrapping the text with angle brackets (< and >)
The automatic URL as follows:
<http://baidu.com/>

### Step 7 – Inserting blockquotes  
The syntax for blockquotes is similar to that of e-mail blockquotes—it uses right-angle brackets (>):
> A blockquote.
> Another line of blockquote.
Optionally, we may only put one bracket before the first line of a paragraph:
> A blockquote.
Another line of blockquote.

Blockquotes can be nested:
> First level of the quote.
>> Nested blockquote.

### Step 8 – Inserting code blocks
The embedding of pre-formatted code blocks is possible by indenting every line of the block
with four spaces or one tab:  

    echo 'Hello World'
    
### Step 9 – Inserting code spans
To insert inline code, we wrap it with backticks (`and`):
Type `echo 'Hello World'` in your terminal

### Step 10 – Inserting images
Markdown uses syntax similar to that of the links to insert images in a document, allowing two styles: inline and reference.  
#### Inline  
![Alt text](/path/to/img.jpg "Optional title")  
  
#### Reference  

![Alt text][id]  

Then, add the following line anywhere in the document:  

[id]: url/to/image "Optional title attribute"

### Step 11 – Inserting horizontal rules  
To insert a horizontal separator, put three or more hyphens (-), asterisks (*), or underscores (_)  
 
on a line:
---
***
*****
* * *
___

### Step 12 – Inserting backslash escapes
Markdown uses many symbols to specify its syntax. If we want to write any of them without
being interpreted, Markdown provides backslash escapes (\) for the following characters:  

\ backslash

` backtick

* asterisk

_ underscore

{} curly braces

[] square brackets

() parentheses

# hash mark
+ plus sign
- minus sign (hyphen)
. dot
! exclamation mark
Escape asterisks in text as shown in the following code:
\*this text is surrounded by literal asterisks\*

### Step 13 – Inserting HTML
Finally, Markdown allows you to include raw HTML. You may write HTML code anywhere in
a document. Consider the following example:
This is a paragraph.
<table>
 <tr>
 <td>Row</td>
 </tr>
</table>
