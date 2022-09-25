# First Challenge for UT Full Stack Development Bootcamp

## Refactoring Code for Accessibility 

This webpage for the fictional social media marketing company "Horiseon" was the first challenge for the UT-Austin Full Stack Web Development Bootcamp. The main goal was to refactor the front end of the web page to be more accessible by using semantic tags instead of the existing structure. 

![Screenshot of Horiseon Webpage](./assets/images/Horiseon%20Project%20for%20UTA%20Bootcamp.png)



## Changes Made and Lessons Learned

While the Web is designed to work for all people, poor design can lead to problems for end users with different levels of abilities. In this project I replaced `<div>` tags with tags that provide additional context, such as `<header>`, `<section>`, and `<article>`. I also added `<alt>` tags to every image related to the content. (Note: Background images don't normally require `<alt>` tags unless the content of the background is essential. Icons can also simply have empty `<alt>` tags when they're accompanied by explanatory text, like the icons in the lower right sidebar.)

I also refactored the CSS styles to eliminate redundancy while still keeping the visual requirements and best-practices for ordering of styles.

___


## Credits

The original code was created by staff of the UT Austin Full Stack Development Bootcamp. Thanks to Leah, Ian, Negin, Diem, and all the students who work with me daily to keep improving. 

___


## License

MIT License

Copyright (c) 2022 Mark Gardner

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
