What is Markdown?

Markdown is a way to style text on the web. You control the display of the document; formatting words as bold or italic, adding images, and creating lists are just a few of the things we can do with Markdown. Mostly, Markdown is just regular text with a few non-alphabetic characters thrown in, like # or *.

You can use Markdown most places around GitHub:

Gists
Comments in Issues and Pull Requests
Files with the .md or .markdown extension
For more information, see “Writing on GitHub” in the GitHub Help.

Examples
Text Lists Images Headers & Quotes Code Extras
It's very easy to make some words **bold** and other words *italic* with Markdown. You can even [link to Google!](http://google.com)
It's very easy to make some words bold and other words italic with Markdown. You can even link to Google!

Syntax guide
Here’s an overview of Markdown syntax that you can use anywhere on GitHub.com or in your own text files.

Headers
# This is an <h1> tag
## This is an <h2> tag
###### This is an <h6> tag

Emphasis
*This text will be italic*
_This will also be italic_

**This text will be bold**
__This will also be bold__

_You **can** combine them_

Lists(Unordered)
* Item 1
* Item 2
  * Item 2a
  * Item 2b

Lists(Ordered)
1. Item 1
1. Item 2
1. Item 3
   1. Item 3a
   1. Item 3b

Images
![GitHub Logo](/images/logo.png)
Format: ![Alt Text](url)

Links
http://github.com - automatic!
[GitHub](http://github.com)

Tables
You can create tables by assembling a list of words and dividing them with hyphens - (for the first row), and then separating each column with a pipe |:

First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column
Would become:

First Header	Second Header
Content from cell 1	Content from cell 2
Content in the first column	Content in the second column
SHA references
Any reference to a commit’s SHA-1 hash will be automatically converted into a link to that commit on GitHub.

->Username @mentions
Typing an @ symbol, followed by a username, will notify that person to come and view the comment. This is called an “@mention”, because you’re mentioning the individual. You can also @mention teams within an organization.

Refrence: https://guides.github.com/features/mastering-markdown/