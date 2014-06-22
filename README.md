safcat (beta)
=============
A simple Safari extension that uploads a gif open in the current tab to gfycat and plays it back on said site.

While visiting a third-world country with very slow Internet, I was tired of uploading gifs manually to gfycat to view them smoothly and I saw that there was no such extension for Safari. **I made this extension to learn JavaScript, browser extensions, JSON parsing and the Safari extensions API.**

I have never done anything in JavaScript before and I am certainly new to writing browser add-ons. I am sure I have not followed many best-practices and my code is quite messy. But it is simple and it works with negligible extra load on the browser (pretty sure).

I would appreciate any pointers, tips and improvements to this extension.

P.S. Does anyone know of a way to update this extension without having a web server? Are there online services I can use? **Currently, this extension does NOT have a way for me to update it. When I implement that feature, I will announce it on appropriate subreddits.**

Download
--------
Download the extension file here: http://ge.tt/96Wxqnl1/v/0

This is the same file as the one in this repository.

Ways to contribute
------------------
I am uncertain on how exactly I should use the 'validate' event to only enable the button when the current URL has a .gif at the end. I think I have a viable stub of code to handle this, but it doesn't work properly. If you think you can make it work, uncomment the validate event listener and implement this. Then send me a pull request and I will accept it.