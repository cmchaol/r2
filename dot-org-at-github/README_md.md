<div id="table-of-contents">
<h2>Table of Contents</h2>
<div id="text-table-of-contents">
<ul>
<li><a href="#sec-1">1. goals</a></li>
<li><a href="#sec-2">2. export process</a></li>
<li><a href="#sec-3">3. github markdown</a></li>
<li><a href="#sec-4">4. org-export-headline-levels</a></li>
</ul>
</div>
</div>



# goals

<table border="2" cellspacing="0" cellpadding="6" rules="groups" frame="hsides">


<colgroup>
<col  class="left" />

<col  class="left" />
</colgroup>
<tbody>
<tr>
<td class="left">official</td>
<td class="left">&#xa0;</td>
</tr>


<tr>
<td class="left">&#xa0;</td>
<td class="left">&#xa0;</td>
</tr>


<tr>
<td class="left">readme</td>
<td class="left">&#xa0;</td>
</tr>


<tr>
<td class="left">&#xa0;</td>
<td class="left">&#xa0;</td>
</tr>


<tr>
<td class="left">link</td>
<td class="left">&#xa0;</td>
</tr>


<tr>
<td class="left">&#xa0;</td>
<td class="left">&#xa0;</td>
</tr>


<tr>
<td class="left">image</td>
<td class="left">&#xa0;</td>
</tr>


<tr>
<td class="left">&#xa0;</td>
<td class="left">&#xa0;</td>
</tr>


<tr>
<td class="left">footnote</td>
<td class="left">&#xa0;</td>
</tr>


<tr>
<td class="left">&#xa0;</td>
<td class="left">&#xa0;</td>
</tr>


<tr>
<td class="left">org-export-headline-levels</td>
<td class="left">&#xa0;</td>
</tr>


<tr>
<td class="left">&#xa0;</td>
<td class="left">&#xa0;</td>
</tr>


<tr>
<td class="left">export process</td>
<td class="left">&#xa0;</td>
</tr>
</tbody>
</table>

# export process

<table border="2" cellspacing="0" cellpadding="6" rules="groups" frame="hsides">


<colgroup>
<col  class="left" />

<col  class="left" />

<col  class="right" />
</colgroup>
<thead>
<tr>
<th scope="col" class="left">&#xa0;</th>
<th scope="col" class="left">&#xa0;</th>
<th scope="col" class="right">&#xa0;</th>
</tr>


<tr>
<th scope="col" class="left">&#xa0;</th>
<th scope="col" class="left">&#xa0;</th>
<th scope="col" class="right">&#xa0;</th>
</tr>


<tr>
<th scope="col" class="left">org subtree export to</th>
<th scope="col" class="left">save as</th>
<th scope="col" class="right">pathway</th>
</tr>
</thead>

<tbody>
<tr>
<td class="left">org file</td>
<td class="left">\_org.org</td>
<td class="right">1</td>
</tr>


<tr>
<td class="left">&#xa0;</td>
<td class="left">&#xa0;</td>
<td class="right">&#xa0;</td>
</tr>


<tr>
<td class="left">org buffer</td>
<td class="left">&#xa0;</td>
<td class="right">&#xa0;</td>
</tr>


<tr>
<td class="left">&#xa0;</td>
<td class="left">\_org.md</td>
<td class="right">2</td>
</tr>


<tr>
<td class="left">&#xa0;</td>
<td class="left">\_org.txt</td>
<td class="right">3</td>
</tr>


<tr>
<td class="left">&#xa0;</td>
<td class="left">&#xa0;</td>
<td class="right">&#xa0;</td>
</tr>
</tbody>

<tbody>
<tr>
<td class="left">markdown file</td>
<td class="left">.md</td>
<td class="right">4</td>
</tr>


<tr>
<td class="left">&#xa0;</td>
<td class="left">&#xa0;</td>
<td class="right">&#xa0;</td>
</tr>


<tr>
<td class="left">markdown buffer</td>
<td class="left">&#xa0;</td>
<td class="right">&#xa0;</td>
</tr>


<tr>
<td class="left">&#xa0;</td>
<td class="left">&#xa0;</td>
<td class="right">&#xa0;</td>
</tr>
</tbody>

<tbody>
<tr>
<td class="left">txt file</td>
<td class="left">.txt</td>
<td class="right">5</td>
</tr>


<tr>
<td class="left">&#xa0;</td>
<td class="left">&#xa0;</td>
<td class="right">&#xa0;</td>
</tr>


<tr>
<td class="left">txt buffer</td>
<td class="left">\_txt.org</td>
<td class="right">6</td>
</tr>


<tr>
<td class="left">&#xa0;</td>
<td class="left">\_txt.md</td>
<td class="right">7</td>
</tr>


<tr>
<td class="left">&#xa0;</td>
<td class="left">&#xa0;</td>
<td class="right">&#xa0;</td>
</tr>
</tbody>
</table>

# github markdown

1.  Writing on GitHub

    <https://help.github.com/categories/writing-on-github/>

2.  Markdown Basics

    <https://help.github.com/articles/markdown-basics/>

3.  Mastering Markdown

    <https://guides.github.com/features/mastering-markdown/>

4.  Markdown Cheatsheet

    <https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet>

5.  GitHub Flavored Markdown

    <https://help.github.com/articles/github-flavored-markdown/>

# org-export-headline-levels

<http://orgmode.org/manual/Export-settings.html>

The #+OPTIONS keyword is a compact2 form that recognizes the following arguments: 

H:
    Set the number of headline levels for export (org-export-headline-levels). Below that level, headlines are treated differently. In most back-ends, they become list items. 

1.  org export settings

    <http://orgmode.org/manual/Export-settings.html>
    
    1.  subtree properties
    
    2.  org export space (effective area)
    
        <table border="2" cellspacing="0" cellpadding="6" rules="groups" frame="hsides">
        
        
        <colgroup>
        <col  class="left" />
        
        <col  class="left" />
        
        <col  class="right" />
        
        <col  class="left" />
        </colgroup>
        <thead>
        <tr>
        <th scope="col" class="left">org export space</th>
        <th scope="col" class="left">&#xa0;</th>
        <th scope="col" class="right">&#xa0;</th>
        <th scope="col" class="left">&#xa0;</th>
        </tr>
        
        
        <tr>
        <th scope="col" class="left">(effective area)</th>
        <th scope="col" class="left">&#xa0;</th>
        <th scope="col" class="right">&#xa0;</th>
        <th scope="col" class="left">&#xa0;</th>
        </tr>
        
        
        <tr>
        <th scope="col" class="left">&#xa0;</th>
        <th scope="col" class="left">&#xa0;</th>
        <th scope="col" class="right">&#xa0;</th>
        <th scope="col" class="left">examples</th>
        </tr>
        
        
        <tr>
        <th scope="col" class="left">3 levels</th>
        <th scope="col" class="left">what, where to set</th>
        <th scope="col" class="right">priority</th>
        <th scope="col" class="left">org-export-headline-levels</th>
        </tr>
        </thead>
        
        <tbody>
        <tr>
        <td class="left">a subtree</td>
        <td class="left">subtree properties</td>
        <td class="right">1</td>
        <td class="left">&#xa0;</td>
        </tr>
        
        
        <tr>
        <td class="left">&#xa0;</td>
        <td class="left">&#xa0;</td>
        <td class="right">&#xa0;</td>
        <td class="left">&#xa0;</td>
        </tr>
        
        
        <tr>
        <td class="left">an individual file</td>
        <td class="left">in-buffer setting</td>
        <td class="right">2</td>
        <td class="left">#+OPTIONS:  H:1</td>
        </tr>
        
        
        <tr>
        <td class="left">&#xa0;</td>
        <td class="left">&#xa0;</td>
        <td class="right">&#xa0;</td>
        <td class="left">&#xa0;</td>
        </tr>
        
        
        <tr>
        <td class="left">globally</td>
        <td class="left">variable</td>
        <td class="right">3</td>
        <td class="left">&#xa0;</td>
        </tr>
        
        
        <tr>
        <td class="left">&#xa0;</td>
        <td class="left">&#xa0;</td>
        <td class="right">&#xa0;</td>
        <td class="left">&#xa0;</td>
        </tr>
        </tbody>
        </table>
    
    3.  in-buffer setting
    
        <table border="2" cellspacing="0" cellpadding="6" rules="groups" frame="hsides">
        
        
        <colgroup>
        <col  class="left" />
        
        <col  class="left" />
        </colgroup>
        <thead>
        <tr>
        <th scope="col" class="left">in-buffer setting</th>
        <th scope="col" class="left">&#xa0;</th>
        </tr>
        
        
        <tr>
        <th scope="col" class="left">2 ways</th>
        <th scope="col" class="left">&#xa0;</th>
        </tr>
        </thead>
        
        <tbody>
        <tr>
        <td class="left">directly</td>
        <td class="left">anywhere in the file</td>
        </tr>
        
        
        <tr>
        <td class="left">&#xa0;</td>
        <td class="left">&#xa0;</td>
        </tr>
        
        
        <tr>
        <td class="left">indirectly</td>
        <td class="left">anywhere in the file</td>
        </tr>
        
        
        <tr>
        <td class="left">&#xa0;</td>
        <td class="left">#+SETUPFILE: filename</td>
        </tr>
        </tbody>
        </table>
        
        <table border="2" cellspacing="0" cellpadding="6" rules="groups" frame="hsides">
        
        
        <colgroup>
        <col  class="left" />
        </colgroup>
        <thead>
        <tr>
        <th scope="col" class="left">examples</th>
        </tr>
        </thead>
        
        <tbody>
        <tr>
        <td class="left">#+TITLE:</td>
        </tr>
        
        
        <tr>
        <td class="left">#+OPTIONS:</td>
        </tr>
        
        
        <tr>
        <td class="left">#+SETUPFILE: file</td>
        </tr>
        
        
        <tr>
        <td class="left">#+STARTUP:</td>
        </tr>
        
        
        <tr>
        <td class="left">&#xa0;</td>
        </tr>
        </tbody>
        </table>
        
        <http://orgmode.org/manual/Export-settings.html>
        
        <http://orgmode.org/manual/In_002dbuffer-settings.html#In_002dbuffer-settings>
    
    4.  org footnote
    
        This is a book.I like this book. 
        
        I also like that book. 
        
        I like a lot of books. 
        
        I like many books. 

<div id="footnotes">
<h2 class="footnotes">Footnotes: </h2>
<div id="text-footnotes">

<div class="footdef"><sup><a id="fn.1" name="fn.1" class="footnum" href="#fnr.1">1</a></sup> hello</div>

<div class="footdef"><sup><a id="fn.2" name="fn.2" class="footnum" href="#fnr.2">2</a></sup> hi</div>

<div class="footdef"><sup><a id="fn.3" name="fn.3" class="footnum" href="#fnr.3">3</a></sup> hello again</div>

<div class="footdef"><sup><a id="fn.4" name="fn.4" class="footnum" href="#fnr.4">4</a></sup> <p>hello again</p></div>

<div class="footdef"><sup><a id="fn.5" name="fn.5" class="footnum" href="#fnr.5">5</a></sup> another footnote mode</div>


</div>
</div>
