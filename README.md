# Use cases
- Want to take a screenshot of specific/whole portion of the webpage?
- Is that your stylesheet editing with direct browser went too long and you need to show the current-state of look to your boss? 
- Are you in need of a GUI based tool to select the portion of web page to get extracted as a png/jpg image file?
- Do you have a physical/virtual canvas, for which the selected portion of web page should need to get painted?

# Smile Please :) -- Here's the solution!

A js based lightweight library that can paint the current-state of look of the DOM you specify to a canvas -- eventually which in case it can be extracted as an image too.

## Usage
1. Web
   - Include the lightweight lib script `smilePlease.js` using the cdn - 
   https://cdn.rawgit.com/venkatb4u/smile_please/master/example/smilePlease.js
   
   usage 1:  `__();` (OR) `smilePlease();`   // if no DOM specified, 'document.body' is made to be default.
   
   usage 2:  `__(dom, [optional-callback]);` (OR) `smilePlease(dom, [optional-callback]);`
   
   e.g.:  `__('#test')`, `__('.test', function(canvas) { document.body.appendChild(canvas) });`
   
   usage 3: Simply double-click on the page to toggle the 'EDIT' mode and single click to select the DOM
 
## Contribution
Below are some possible `top priority` features/challenges yet to be addressed, and any sort of help from you is really appreciable.
- Support for exporting various other image formats (png,gif etc.)
- Appropriate/efficient way of painting `img` tags over `canvas`. 

If anything else you feel can be included, pls feel free to raise it as an `issue` and provide a solution to it with a `pull request'.
