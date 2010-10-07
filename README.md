ProgressBar
============

Javascript progressbar

![Screenshot](http://github.com/tbela99/progressbar/raw/master/screenshot.png)
[Demo](http://jsfiddle.net/tbela99/5UR8v/1/)

How to use
---------------------

The progressbar can use either colors or background image.

object providing methods to control field upload.

### Syntax

	var progressbar = new ProgressBar({container: 'element'});

(*boolean*) indicates if the browser handle file upload via XMLHTTPRequest.

#### Arguments:

1. options - (*object*)

##### Options:

- container - (*mixed*) progressbar container.
- value - (*number*, optional) initial value of the progressbar. value is always between 0 and 1 (100%). default to 0. 
- text - (*string*, optional) progressbar text.
- color - (*string*, optional) progressbar color.
- fillColor - (*string*, optional) progressbar fill color.
- backgroundImage - (*string*, optional) background image used to fill the progressbar. this parameter will shadow the fillColor parameter.


##### Events:

##### onChange

Fired after the value is changed.

##### Arguments:

- value - (*number*) the current value

##### onComplete

Fired after the value has been set to 1.

##### setText

set the text in the progressbar

##### Arguments:

- text - (*string*) 

##### setValue

set the progressbar value. the value is a number between 0 and 1.

##### Arguments:

- value - (*number*)

##### getValue

return the progressbar value.