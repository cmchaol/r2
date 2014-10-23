			      ____________

			       README.ORG
			      ____________


Table of Contents
_________________

1 goals
2 github markdown
3 org-export-headline-levels





1 goals
=======

   official                     
                              
   readme                       
                              
   link                         
                              
   image                        
                              
   footnote                     
                              
   org-export-headline-levels   


2 github markdown
=================

* 2.1 Writing on GitHub

  [https://help.github.com/categories/writing-on-github/]


* 2.2 Markdown Basics

  [https://help.github.com/articles/markdown-basics/]


* 2.3 Mastering Markdown

  [https://guides.github.com/features/mastering-markdown/]


* 2.4 Markdown Cheatsheet

  [https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet]


* 2.5 GitHub Flavored Markdown

  [https://help.github.com/articles/github-flavored-markdown/]


3 org-export-headline-levels
============================

  [http://orgmode.org/manual/Export-settings.html]

  The #+OPTIONS keyword is a compact2 form that recognizes the following
  arguments:

  H: Set the number of headline levels for export
      (org-export-headline-levels). Below that level, headlines are
      treated differently. In most back-ends, they become list items.


* 3.1 org export settings

  [http://orgmode.org/manual/Export-settings.html]


  + 3.1.1 subtree properties


  + 3.1.2 org export space (effective area)

     org export space                                                             
     (effective area)                                                             
                                                       examples                   
     3 levels            what, where to set  priority  org-export-headline-levels 
    ------------------------------------------------------------------------------
     a subtree           subtree properties         1                             
                                                                              
     an individual file  in-buffer setting          2  #+OPTIONS:  H:1            
                                                                              
     globally            variable                   3                             


  + 3.1.3 in-buffer setting

     in-buffer setting                        
     2 ways                                   
    ------------------------------------------
     directly           anywhere in the file  
                                          
     indirectly         anywhere in the file  
                        #+SETUPFILE: filename 


     examples          
    -------------------
     #+TITLE:          
     #+OPTIONS:        
     #+SETUPFILE: file 
     #+STARTUP:        

    [http://orgmode.org/manual/Export-settings.html]

    [http://orgmode.org/manual/In_002dbuffer-settings.html#In_002dbuffer-settings]


  + 3.1.4 org footnote

    This is a book.[1] I like this book. [2]

    I also like that book. [3]

    I like a lot of books. [4]

    I like many books. [5]



Footnotes
_________

[1] hello

[2] hi

[3] hello again

[4] hello again

[5] another footnote mode
