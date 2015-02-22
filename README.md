# lengthily
Extra length units for Sass.
For all of those times when you want to add two hundredths of a mile of padding to a div.

The `_length` function can be used as such:

    h1 {
      padding-left: _length(.0000000000000001 lightyears);
      margin-top: _length(20000000 nanometers);
    }
    
Demo: http://codepen.io/mknadler/full/dPmBqZ/
    
Currently supported units:

* Inches
* Nanometers
* Centimeters
* Meters
* Kilometers
* Pixels
* Miles
* Astronomical Units
* Light-years
* [Hands](http://en.wikipedia.org/wiki/Hand_%28unit%29)
* [Horse-lengths](http://en.wikipedia.org/wiki/Horse_length)

Feel free to add more!
