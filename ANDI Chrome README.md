To use ANDI in Chrome -- the work-around:
Click [F12] to open developer tools
Select Console tab
Paste following code into the console and hit [Enter]:
-----
javascript:void((function(){andiScript=document.createElement('script');andiScript.setAttribute('src','https://www.ssa.gov/accessibility/andi/andi.js');document.body.appendChild(andiScript)})());
-----
Press Enter after typing above code.
Click [F12] to close developer tools
