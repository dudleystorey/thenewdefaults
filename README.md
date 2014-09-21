The New Defaults: A Sass Color Thesaurus
========================================

A Sass replacement for the standard CSS named color system. Provides more visually appealing hues for many CSS keywords; adds new colors with more relevant and easily remembered names. Inspired by [Ingrid Sundberg’s color thesaurus](http://ingridsnotes.wordpress.com/2014/02/04/the-color-thesaurus/) and the work of [Adam Morse](http://clrs.cc/).

To use
------

Include `_color-map.scss` and `_color-generator.scss` in your project:

```CSS
@import 'maps/_color-map.scss';
@import 'functions/_color-generator.scss';
```

Use any of the named colors in your Sass:

```CSS
body { background: color(sky); }
```

A [complete visual guide to The New Defaults](http://dudleystorey.github.io/thenewdefaults/) is available on Github Pages.
