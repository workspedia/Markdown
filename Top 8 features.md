### 1 – Forum and discussion
BBS是电子公告板系统(Bulletin Board System)之英文缩写，  
它通过在计算机上运行服务软件，允许用户使用终端程序通过电话调制解调器拨号或者Internet来进行连接，  
执行下载数据或程序、上传数据、阅读新闻、与其它用户交换消息等功能。  
Users write Markdown inside web forms; the website does the Markdown conversion on the server and then displays the text in HTML.
Sites such as GitHub, BitBucket, Reddit, StackOverflow, SourceForge, Trello, and Disqus use Markdown with great success. 
### 2 – Writing e-mails
### 3 – Sharing a single document
Creating and sharing a document with someone can be achieved very easily with different web
services. Here we present two of them that work in exactly the same way:
- Hashify: Read about it at [http://hashify.me/](http://hashify.me/)
- Socrates: Read about it at http://socrates.io/
### 4 – Blogging
Writing a blog using Markdown is possible in different ways.
Some blog platforms, such as Tumblr, have an editor that supports writing in Markdown.

### 5 – To-do lists
We can use Markdown for personal organization. To-do lists are prioritized lists of tasks that we
need to do.
The service that we are going to use is Cheddar, which can be found at https://cheddarapp.com/.
### 6 – Presentations
Creating beautiful, interactive, and simple presentations is possible with some of the presentation
frameworks based on JavaScript and Markdown.
Two such frameworks that support a Markdown extension are reveal.js and deck.js.
> reveal.js: Check this out at http://lab.hakim.se/reveal-js/
> deck.js: Check this out at http://imakewebthings.com/deck.js/

### 7 – Converting files to other formats
If we need to convert files from Markdown format into another format, pandoc is the tool that
we need, and it can be found at http://johnmacfarlane.net/pandoc/.
Pandoc is able to convert documents from Markdown to many different formats, such as:
- HTML formats (XHTML, HTML5, HTML)
- Word processor formats (Microsoft Word docx, OpenOffice/LibreOffice odt,
OpenDocument XML)
- Ebooks (ePub Versions 2 or Version 3, FictionBook2)
- Documentation formats (DocBook)
- TeX formats (LaTeX)
- PDF
- Lightweight markup formats (reStructuredText, Textile)
Installing Pandoc is really easy. On the official website, we can find the package installers for
MS Windows and Mac OS X, and an installer is also available in the repositories of different
Linux distributions.
Pandoc is a command-line tool, so we need to open a command-line interface to use it. For
example, to convert a Markdown file to PDF, simply type the following command:  
  
<pre><code> pandoc document.md -s -o document.pdf </code></pre> 

8 – Markdown extensions

There are Markdown extensions implementing multiple syntax features currently not available
with the Markdown syntax. These extensions are similar to Markdown flavors but add to or
modify the syntax in a more advanced way.

MultiMarkdown is a popular superset of the Markdown syntax and can be found at
http://fletcherpenney.net/multimarkdown/. Some of the features it adds to Markdown are:
Ê Footnotes
Ê Tables
Ê Citations and bibliography
Ê Math support
Ê Smart typography with support for multiple languages

Footnotes
Here is an example of a footnote:

Here is some text containing a footnote[^somefootnote]. More text
  
[^somefootnote]: Here is the text of the footnote itself.

Tables
The format of a table is shown as follows:

| First Header | Second Header |
| :----------: | :-----------: |
| First row | Data |
| Second row | **Cell** |
[simple_table]

Citations
Here is an example of a citation:
Let's cite a book.[p. 42][#book]

Math
Here is a math support example:

\\[ {e}^{i\pi }+1=0 \\]

People and places you should get to know
If you need help with Markdown, here are some people and places that will prove invaluable.
Official sites:
Ê The homepage: http://daringfireball.net/projects/markdown/
Ê Syntax and documentation:
http://daringfireball.net/projects/markdown/syntax
Ê Editor and converter: http://daringfireball.net/projects/markdown/dingus
Articles:
Ê See the article by Jeff Atwood discussing the standardization of Markdown—for it to
be consistent in every service— and its future at http://www.codinghorror.com/
blog/2012/10/the-future-of-markdown.html
Ê 78 tools for writing and previewing Markdown: http://mashable.com/2013/06/24/
markdown-tools/
Ê Find out more about comparing the output of various implementations at
http://johnmacfarlane.net/babelmark2/
Community:
Ê The official mailing list can be found at http://six.pairlist.net/mailman/
listinfo/markdown-discuss
Ê The Markdown community page can be found at http://markdown.github.io/
Twitter:
Ê Follow Markdown on Twitter at https://twitter.com/markdown
Ê Follow John Gruber, the creator of Markdown, on Twitter at
https://twitter.com/gruber
Ê For more open source information, follow Pa
