Image Slider
============

Whilst learning JQuery as part of the Odin Project [jQuery 101 module](http://www.theodinproject.com/courses/web-development-101/lessons/jquery-basics), I wanted to improve upon/update the basic image slider posted in these videos;

* [Video 1](http://www.youtube.com/watch?v=QtYP_eSVKfs)
* [Video 2](http://www.youtube.com/watch?v=z277ZUHNnnE)
* [Video 3](http://www.youtube.com/watch?v=XlYsjMPCgfI)

Check it out [here](https://clormor.github.io/image-slider/).

Improvements include;

1. Simpler logic for looping through images. Instead of keeping 2 loop counters and having `if/else` statements to handle overflow, simply use 1 counter and use the modulus to determine which image to display.
2. jQuery3+ compatible by using `.length` instead of `.size()` to count number of images.
3. Avoid duplication of code to display the next image
4. Use `<button>`s instead of `<a>`s for the buttons, to avoid a `href='#'` and having to return `false` to prevent page reloads.
5. Nicer images :)
