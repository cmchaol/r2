:PROPERTIES:
:EXPORT_OPTIONS: H:1
:END:



* goals

| official                   |   |
|                            |   |
| readme                     |   |
|                            |   |
| link                       |   |
|                            |   |
| image                      |   |
|                            |   |
| footnote                   |   |
|                            |   |
| org-export-headline-levels |   |
|                            |   |
| export process             |   |


* export process

|                       |          |         |
|                       |          |         |
| org subtree export to | save as  | pathway |
|-----------------------+----------+---------|
| org file              | _org.org |       1 |
|                       |          |         |
| org buffer            |          |         |
|                       | _org.md  |       2 |
|                       | _org.txt |       3 |
|                       |          |         |
|-----------------------+----------+---------|
| markdown file         | .md      |       4 |
|                       |          |         |
| markdown buffer       |          |         |
|                       |          |         |
|-----------------------+----------+---------|
| txt file              | .txt     |       5 |
|                       |          |         |
| txt buffer            | _txt.org |       6 |
|                       | _txt.md  |       7 |
|                       |          |         |

* github markdown

** Writing on GitHub

[[https://help.github.com/categories/writing-on-github/]]


** Markdown Basics

[[https://help.github.com/articles/markdown-basics/]]


** Mastering Markdown

[[https://guides.github.com/features/mastering-markdown/]]


** Markdown Cheatsheet

[[https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet]]


** GitHub Flavored Markdown

[[https://help.github.com/articles/github-flavored-markdown/]]



* org-export-headline-levels

[[http://orgmode.org/manual/Export-settings.html]]

The #+OPTIONS keyword is a compact2 form that recognizes the following arguments: 

H:
    Set the number of headline levels for export (org-export-headline-levels). Below that level, headlines are treated differently. In most back-ends, they become list items. 

** org export settings

[[http://orgmode.org/manual/Export-settings.html]]

*** subtree properties



*** org export space (effective area)


| org export space   |                    |          |                            |
| (effective area)   |                    |          |                            |
|                    |                    |          | examples                   |
| 3 levels           | what, where to set | priority | org-export-headline-levels |
|--------------------+--------------------+----------+----------------------------|
| a subtree          | subtree properties |        1 |                            |
|                    |                    |          |                            |
| an individual file | in-buffer setting  |        2 | #+OPTIONS:  H:1            |
|                    |                    |          |                            |
| globally           | variable           |        3 |                            |
|                    |                    |          |                            |


*** in-buffer setting

| in-buffer setting |                       |
| 2 ways            |                       |
|-------------------+-----------------------|
| directly          | anywhere in the file  |
|                   |                       |
| indirectly        | anywhere in the file  |
|                   | #+SETUPFILE: filename |


| examples          |
|-------------------|
| #+TITLE:          |
| #+OPTIONS:        |
| #+SETUPFILE: file |
| #+STARTUP:        |
|                   |

[[http://orgmode.org/manual/Export-settings.html]]

[[http://orgmode.org/manual/In_002dbuffer-settings.html#In_002dbuffer-settings]]



*** org footnote

This is a book.[fn:1] I like this book. [fn:2]

I also like that book. [fn:3]

I like a lot of books. [fn:4: hello again]

I like many books. [1]
