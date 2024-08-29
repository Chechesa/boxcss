# BoxCSS

BoxCSS is a lightweight and flexible CSS grid system designed to help developers create responsive web layouts with ease.

## Features
- **12-Column Grid:** Allows you to easily create responsive layouts.
- **Responsive Design:** Adapts to different screen sizes, from mobile to desktop.
- **Browser Compatibility:** Works with all modern browsers, including IE8+.
- **Simple and Search Engine Friendly:** Inspired by Foundation, but more straightforward and optimized for SEO.

## Getting Started

To get started with BoxCSS, simply download the CSS and JS files:

- [Download Box CSS](css/box.css)
- [Download JS File for IE8 Compatibility](js/css3.js)

Include the CSS file in your HTML:

~~~html
<link rel="stylesheet" type="text/css" href="css/box.css" />
~~~

If you need compatibility with IE8, include the JS file:

~~~html
<!--[if lt IE 9]>
<script type="text/javascript" src="js/css3.js"></script>
<![endif]-->
~~~

## Example Usage

~~~html
<div class="row">
    <div class="small-12 medium-6 large-4">Your content here</div>
    <div class="small-12 medium-6 large-8">More content here</div>
</div>
~~~

## More Details

For more detailed examples and explanations of how to use BoxCSS, please refer to the [index.html](index.html) file included in this repository. It provides an overview of the grid system, screen size prefixes, and additional styles that you can apply in your projects.

## License

BoxCSS is released under the MIT License.

## Contact

For comments, suggestions, or questions, feel free to contact me via [Twitter](http://twitter.com/Chechesa) or at [Chechesa Labs](http://chechesa.com).
