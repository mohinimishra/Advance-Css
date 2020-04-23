# CSS Rounded Corners :
* With the CSS border-radius property, you can give any element "rounded corners".
``` css
body{
    border-radius: 20px;
}
```
# CSS border-radius - Specify Each Corner:
## The border-radius property can have from one to four values.
* Four values - 
``` css
border-radius: 15px 50px 30px 5px;
```
 (first value applies to top-left corner, second value applies to top-right corner, third value applies to bottom-right corner, and fourth value applies to bottom-left corner).
 * Three values - 
 ``` css
 border-radius: 15px 50px 30px;
 ```
  (first value applies to top-left corner, second value applies to top-right and bottom-left corners, and third value applies to bottom-right corner).
  * Two values - 
  ``` css
  border-radius: 15px 50px;
  ```
   (first value applies to top-left and bottom-right corners, and the second value applies to top-right and bottom-left corners).
* One value - 
``` css
border-radius: 15px;
```
 (the value applies to all four corners, which are rounded equally.
 # CSS border-image Property
 * The CSS border-image property allows you to specify an image to be used instead of the normal border around an element
* The property has three parts:

* The image to use as the border
* Where to slice the image
* Define whether the middle sections should be repeated or stretched.
# CSS gradient properties.
# CSS 2D Transform:
```css
div {
  -ms-transform: rotate(20deg); /* IE 9 */
  transform: rotate(20deg); /* Standard syntax */
}
```
# CSS 2D Transforms Methods:
## translate():
```css
div {
  transform: translate(50px, 100px);
}
```
## rotate():

* scaleX()
* scaleY()
* scale()
* skewX()
* skewY()
* skew()
* matrix()