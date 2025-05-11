# html2pdf - HTML to PDF converted in C

## Example PDF using Postscript

Following is an example postscipt code to show hello world -

```ps
 %!PS
 /Courier             % name the desired font
 20 selectfont        % choose the size in points and establish 
                      % the font as the current one
 72 500 moveto        % position the current point at 
                      % coordinates 72, 500 (the origin is at the 
                      % lower-left corner of the page)
 (Hello world!) show  % paint the text in parentheses
 showpage             % print all on the page
```

In Linux, use the following cmd to convert the ps to pdf format -

```sh
ps2pdf hello_world.ps hello_world.pdf
```

## References

- [PDF Wikipedia](https://en.wikipedia.org/wiki/PDF)
- [Web Pages Wikipedia](https://en.wikipedia.org/wiki/Web_page)
- [Postscript Wikipedia](https://en.wikipedia.org/wiki/PostScript)
- [Printers Wikipedia](https://en.wikipedia.org/wiki/Printer_(computing))

