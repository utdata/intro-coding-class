# Sass and SCSS

Sass is system that makes writing CSS more efficient. SCSS (Sassy CSS) is the syntax we use, and it has to be processed (or "compiled" in tech speak) into regular CSS before the browser can understand it. Think of it as a translation service. In our case we are using Gulp and some other npm tasks to do that translation, hence all the need for the development environment.

Some of the benefits/features of Sass/SCSS are:

- Nesting and shorthand styles allow you to write more understandable and efficient code that is easier to maintain.
- Variables allow you to reuse styles and make a single change that affects values all through your code base.
- Partials and importing allow you to organize your style files into smaller, more manageable chunks.
- Sass allows you to do standard math operations within your SCSS.
- "Mixins" let you make groups of CSS declarations that you can reuse throughout your site. You can even pass in values to make your mixin work more like functions.

The Bootstrap framework that we will use later in this class takes advantage of all of these features. Sass is a required part of Bootstrap.

^ There are two different ways to write Sass, but we will use the SCSS version.

## Sass features

The [Sass guide](https://sass-lang.com/guide) walks through the above features with code examples. You should look through it.

----

Next: [Refactor existing CSS](sass-03.md)