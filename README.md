Curtains
========

A javascript plugin for creating pages that are revealed when the previous page lifts up like curtains rising.  


README Contents
---------------

- [About](#a1)
- [Demo](#a2)
- [How to Use](#a3)
- [Planned Updates](#a4)
- [License](#a5)
- [Author](#a6)


<a name="a1"/>
About
-----

Curtains is a javascript plugin to add a neat [curtains effect](#a2) to your webpage.  

A site using Curtains has a series of curtains, each acting like a curtain that rises revealing the curtains behind. Scrolling down moves the current curtain up the screen. The next curtain is fixed behind, revealed as the bottom of the current curtain becomes visible and moves up the screen. When the current curtain is no longer visible, the next curtain will start to move up the screen.  


<a name="a2"/>
Demo
----

View a demo of this plugin: [Curtains!](http://curtains.herokuapp.com/)  

*    This demo is a [Roots](http://roots.cx) project. View the Roots project code in the [demo folder](https://github.com/ericavonb/curtains/tree/master/demo).*

<a name="a3"/>
How to Use
----------

To have the Curtains effect on your webpage:

- Enclose each part that you want to be an individual curtain in a div with class "curtain".  

- Enclose all of these curtains that will have the effect in a div with class "curtains".  If you do not have this class, a container element with the class "curtains" will be inserted with the pages as children.

- Include the javascript file [curtains_0_1.js](https://github.com/ericavonb/curtains/blob/master/curtain/curtains_0_1.js) in the body or in the head when the document loads. 

If you have a footer (an element with the tag, id, or class "footer"), the footer will be affixed to the bottom of the document, below the last curtain. So, the last curtain will pull up until the footer is fully revealed at which point you can't scroll down any more.  

You can access the plugin with the var "curtains". The current curtain number is "curtains.currentCurtain", the initialization function is "curtains.init", the event listener is "curtains.fn".

<a name="a4"/>
Planned Updates
---------------
Some planned updates to the plugin:

- Add a function such that adding the class "full" to a curtain makes it take up the height of the screen.

- Allow elements within the curtains to have a parallax effect, i.e. scroll at a different speed from the rest of the curtain.  

Contact me if you have any additional suggestions.

<a name="a5"/>
Licence
-------

Copyright (c) 2013, Erica von Buelow

All rights reserved.  

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:  

Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.
Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.
THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

<a name="a6"/>
Author
------

Erica von Buelow

Contact at: [evonbuelow@gmail.com](mailto:evonbuelow@gmail.com)  

*If you have any questions, comments, or suggestions, send me an email.*
