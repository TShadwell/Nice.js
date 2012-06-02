Nice.js
=======
Compiles javascript into ascii art! It is based on [horrible.js](https://github.com/TShadwell/Horrible.js), but as well as compiling, it folds the text into an image.

You can clone this repository if are so inclined to fiddle with the code, or you can use the online version, [here](http://tshadwell.github.com/nice.html).
#Usage
Use a data URI converter to convert the image of your choice (like [this one](http://www.websemantics.co.uk/online_tools/image_to_data_uri_convertor/)), paste it in. The rest is intuitive (I hope). Expect a proportionally lagtime for large code, consider sectioning part of your code to be compiled with this, and leave the else as normal to reduce size and compilation times. Small images <90000px^2 recommended, as the image processing is very inefficient.
#Example
That [face](http://tshadwell.github.com/nice.js)- the Javascript part of nice.js compiled.
