# Plugin-Socket
Plugin socket readme: 14 September 2018

This is a program called “Plugin Socket” its purpose is to run content that would otherwise be run in browsers via a plug-in.

Q: Why might one want to use this?
A: To adapt plug-in dependant content to newer browsers!

Currently there is only a demonstrative program that shows how it would function and an executable file that can load the swf into the browser plug-in outside the browser.

Plugins take many forms OLE Control Extension/ ActiveX ,NPAPI/Netscape Plugin API or Pepper Plugin API PPAPI

These are being phased out by browser developers out in favour of technologies such as WebAssembly

Q: So How can we load content requiring a plugin using a browser with no plugin support?


A: By extracting the applicable information from this code with an addon we can load the content externally in our own program most notably the URL, Width and Height we can load the content in a separate window.

Perhaps in the future have our program run inside the browser,
Dosbox and early versions of windows are already functional there it is not a big leap to consider flash a possible candidate for the same, we just need the code to do it.

But this is just one option my only intention with this is to put forward an idea and some code,

Currently I have compiled a test program in C++ builder,
I will most likely program this in something else I only chose this for ease as this had built in support for Active X,

In future releases a different interface will be needed and there are several to chose from.

I am just putting this out there to encourage discussion and after this has happened explore new ideas put fourth 
