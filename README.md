# AppleScript Libraries
Here is a collection of AppleScript libraries which I use regularly which others may find useful.  This code also forus the basis for a series of blog posts on [markalldritt.com](http://markalldritt.com).

## MarkdownLib

MarkdownLib is a library which converts `rich text` within a `Text Suite` compatible application (e.g. `TextEdit`, [OmniOutliner](https://www.omnigroup.com/omnioutliner) and others) into Markdown.  This is a fairly rudimentry conversion, but it serves me needs.

### Installation


### Usage

MarkdownLib provides a single public function: `richTextToMarkdown(rich text object reference)`.

~~~~
use AppleScript version "2.4" -- Yosemite (10.10) or lateruse MarkdownLib : script "MarkdownLib" version "1.0"use scripting additionstell application "TextEdit"	MarkdownLib's richTextToMarkdown(a reference to document 1)end tell~~~~

