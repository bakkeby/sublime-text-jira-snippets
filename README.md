This repository provides a series of Sublime Text snippets that are specifically related to
Atlassian Jira formatting syntax.

[Sublime Text](https://www.sublimetext.com/) is a text editor and a
[snippet](https://sublime-text-unofficial-documentation.readthedocs.io/en/sublime-text-2/extensibility/snippets.html)
can be thought of as predefined text and is often used to write out template text or code. Atlassian
[Jira](https://www.atlassian.com/software/jira) is many things but first and foremost it is an issue
tracker type of software.

Preparing text in the Jira comment box in your browser is generally perfectly fine but depending on
what you are writing up and for what purpose it may occasionally be worth doing the bulk of the work
in an editor instead. If you have ever lost significant time because something went wrong the very
moment you clicked that button to add an update then you probably understand this use case.

The snippets here can be used for example to add \{\*\} around the selected text to make it bold.
In this scenario the snippet will ignore leading and trailing spaces in the selected text as Jira's
formatting handler does not handle a \{\*\} followed by a space very well.

Snippets are usually placed in the following directory:
   - ~/.config/sublime-text-4/Packages/User/ (Linux)

Optionally one can set up a dedicated jira source definition and limit the scope of these snippets
to only apply to files that fall under the specific source.
