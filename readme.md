# Enhanced Animate-on-Scroll

Animate your website's elements with style! This library builds upon the foundation of the popular Animate-on-Scroll (AOS) library but adds an extra layer of flair, customization, and detailed guidance.

[Check it out here!](https://evanmarie.github.io/animate-on-scroll/)

![animatescroll3](http://www.evanmarie.com/content/images/2023/10/animatescroll3.png)

![animatescroll4](http://www.evanmarie.com/content/images/2023/10/animatescroll4.png)

![animatescroll5](http://www.evanmarie.com/content/images/2023/10/animatescroll5.png)

![animatescroll6](http://www.evanmarie.com/content/images/2023/10/animatescroll6.png)

![animatescroll7](http://www.evanmarie.com/content/images/2023/10/animatescroll7.png)

## Features

- 🌈 Rich animations with extended easing functions.
- 🕰 Adjustable durations, delays, and offsets for precise control.
- 💡 Enhanced documentation with in-depth explanations.
- 🚀 Support for modern browsers with smooth scrolling and customized scrollbars.
- 🔧 Vanilla JavaScript, no additional dependencies.

![animatedscroll](http://www.evanmarie.com/content/images/2023/10/animatedscroll.gif)

## Getting Started

1. **Include the Library**

   Link the enhanced AOS library in your HTML:

   ```html
   <link rel="stylesheet" href="path-to-your-enhanced-aos.css" />
   <script src="path-to-your-enhanced-aos.js"></script>
   ```

2. **Initialize**

   After including the library, initialize it:

   ```javascript
   document.addEventListener("DOMContentLoaded", function () {
     AOS.init();
   });
   ```

3. **Add Data Attributes to Elements**

   Use `data-aos` attributes on elements to specify the animation type:

   ```html
   <div data-aos="fade-up">I will fade up when scrolled into view!</div>
   ```

4. **Customize!**

   Make use of the additional attributes like `data-aos-easing`, `data-aos-duration`, `data-aos-offset`, and `data-aos-delay` for fine-tuned control.

## Detailed Attributes

- `data-aos`: The animation type (e.g., `fade-up`, `fade-right`, etc.)
- `data-aos-easing`: Speed curve of the animation.
- `data-aos-duration`: How long the animation effect lasts (in milliseconds).
- `data-aos-offset`: Adjusts the animation trigger point.
- `data-aos-delay`: Adds a delay before the animation starts.

## Custom Scrollbars

Give your website a consistent and stylish look with customized scrollbars. Follow our guide on integrating our enhanced scrollbars, tailored for both Webkit and Firefox browsers.

## Conclusion

Enhanced Animate-on-Scroll provides web developers with a powerful toolkit to breathe life into their websites. With a rich set of animations, combined with the flair and extensive documentation, making your website elements pop has never been easier!

## License

This project is licensed under the MIT License.
