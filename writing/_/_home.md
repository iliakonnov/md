# Hello!

This service is based on the amazing [Writing](https://github.com/josephernest/writing). You can write your markdown notes here.

- Private pages — can be accessed only by owner: `/.user/…`
- Public pages — can be read by anyone: `/~user/…`
- Shared pages — can be edited by anyone: `/…`, but be careful: there is no real collaborative editing
- Browse available pages: <a href="/_">Click</a>

Authorization form:
<form action="/_auth/" method="post" style="border: 1px dashed gray;">
    <input type="text" placeholder="Login" name="name" required>
    <input type="password" placeholder="Password" name="pass" required>
    <button type="submit">Click me!</button>
</form>

# Help

Write text on the left, and the result is displayed on the right.
                                   
Commands
--------                              
CTRL + D: toggle display mode (editor only, preview only or both-at-the-same-time)
CTRL + P: print or export as PDF   
CTRL + S: save source code as .MD file                                  
CTRL + SHIFT + O: open .MD file
            
CTRL + SHIFT + L: enable / disable LaTeX (i.e. math formulas)
CTRL + SHIFT + D: toggle dark mode                             
CTRL + SHIFT + R: toggle roman (LaTex-like) or sans-serif font
CTRL + SHIFT + H: show this help dialog  
         
F11: full-screen (in most browsers)

LaTeX syntax          
------------           
This formula $x^2+1$ will be displayed inline.                            
This formula $$x^2+1$$ will be displayed in a new paragraph.
            
Specific syntax                                      
---------------                                                  
\pagebreak will trigger a pagebreak when printing / exporting to PDF.
                                   
About
-----
Made (mostly) by [@JosephErnest](https://twitter.com/JosephErnest) (https://github.com/josephernest/writing)
Uses [Pagedown](https://code.google.com/archive/p/pagedown/), [Pagedown Extra](https://github.com/jmcmanus/pagedown-extra), [MathJax](https://www.mathjax.org/), StackOverflow's [editor](https://gist.github.com/gdalgas/a652bce3a173ddc59f66) code and the [Linux Libertine](http://libertine-fonts.org/libertine-fonts/) font.
