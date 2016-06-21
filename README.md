# Outline

## A fully adaptable responsive grid. That's it.

Sometimes you're just starting a simple project, and you don't need the heavy artillery of complicated frameworks.  
Outline is exactly what it says: a simple grid-based boilerplate, and that's it.

No additional modules. No preset styles. Just the stuff you asked for.

Please visit: [http://www.getoutline.com](http://getoutline.com/)

### The Grid

Outline works out of the box with a 12 columns fluid grid that extends up to 1140px wide. Columns are wrapped in `row`s, themselves wrapped in `container`s.

You can also go full-width by using a `container-full` instead of a `container`.

### Works right out of the box

You can use Outline right out of the box, or you can tune it a little before you go. It comes with source Sass files, expanded and minified CSS.

<pre>
&lt;div class="container"&gt;
&nbsp;&nbsp;&nbsp; &lt;div class="row"&gt;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &lt;div class="col col-12"&gt;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &lt;!-- This is where it all starts --&gt;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &lt;/div&gt;
&nbsp;&nbsp;&nbsp; &lt;/div&gt;
&lt;/div&gt;</pre>

### Lighter than air

Outline was built to be **as light as can be**. It only weights 1 KB, and it's free from any unnecessary bloat. There's literally only the things you need from a grid-based framework, and nothing more.

Outline is a transparent foundation, not an everything but the kitchen sink toolbox.

### Fully adaptable

**Outline adjusts to your needs, not the other way around**. You can customize the max-width of the grid, the number of columns and the gutter width in seconds. Just edit the `_variables.scss` file and recompile the sources, and you'll be good to go.

### Nestable

You can nest columns within columns as deep as you want. Don't forget to wrap each new line in a `row` and it'll just work.

<pre>
&lt;div class="container"&gt;
&nbsp;&nbsp;&nbsp; &lt;div class="row"&gt;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &lt;div class="col col-4"&gt;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &lt;div class="row"&gt;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &lt;div class="col col-6"&gt;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &lt;!-- I'm a .col-6 nested within a .col-4 --&gt;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &lt;/div&gt;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &lt;div class="col col-6"&gt;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &lt;!-- Me too --&gt;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &lt;/div&gt;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &lt;/div&gt;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &lt;/div&gt;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &lt;div class="col col-8"&gt;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &lt;!-- I'm a regular .col-8 --&gt;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &lt;/div&gt;
&nbsp;&nbsp;&nbsp; &lt;/div&gt;
&lt;/div&gt;</pre>

### Cross-browser. Cross-platform. Mobile friendly.

Outline is compatible with all major browsers. It even supports Internet Explorer, down to IE9.

It's fully responsive and works as a charm on mobile platforms. Since it's so lightweight, it will load as fast as lightning, even on a smartphone with bad 3G.

### Credits

My name is [Sarah Dayan](http://resume.sarahdayan.com/) and I'm the developer behind Outline.  
This page uses [Eric Meyer's reset.css](http://meyerweb.com/eric/tools/css/reset/) and [Arimo](https://fonts.google.com/specimen/Arimo) and [Inconsolata](https://fonts.google.com/specimen/Inconsolata) by Google Fonts.


### Social

Enjoying Outline? Show me some love by starring on [Github](https://github.com/sarahdayan/outline), sharing and following on [Twitter](https://twitter.com/outlinecss)!
