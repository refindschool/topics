---
group: web-dev-2
playlist: PLWjCJDeWfDddIWwftJxBqtHpw8CbFMXsa
download: https://github.com/acgd-learn-the-web/modules-code/archive/master.zip
github: https://github.com/acgd-learn-the-web/modules-code
---

Thinking modularly in CSS allows us to create more reusable CSS. And allows us to really reduce our duplication making our code more maintainable.

---

## Why is modularity important?

When writing CSS, and any code, we want to make everything as lean and maintainable as possible. In code there’s a common idiom: “Keep it DRY”; meaning don’t repeat yourself.

When writing code, don’t just think about what makes sense now, but also think about what makes sense in the future.

- If you come back to a project in a year, will you know what’s going on?
- If you give your code to another person is it obvious where everything is?
- If you find yourself copying and pasting code from one place to another, you have a problem.
- If you find that two elements have nearly identical code, combine them together.
- If you find something that feels *wrong* or *hacky*, see if there’s a better way.

---

## Ways to simplify CSS

When looking at simplifying your CSS there a few things you can consider:

- Look for common properties, like text alignment, margins, paddings, etc.
- Look for common patterns, common design items with small variations, like buttons, or horizontal lists, and extract those into reusable classes.
- Use min-width media queries so you don’t have to copy and paste all your CSS into each new MQ.

If you’re using a [grid system](http://gridifier.web-dev.tools) or the [modular type system](http://typografier.web-dev.tools), they often come with a bunch of abstracted CSS classes to help you out.

Some utility classes you could consider:

- `.left`, `.right` to float elements.
- `.text-left`, `.text-center`, `.text-right` to change the text alignment.
- `.bold`, `.italic` to change the font weight and style.
- `.gutter`, `.island` for consistent padding.
- `.push` for consistent margins.
- `.flex` to make images responsive.

*But be really careful not to go overboard—these classes should be considered “brute-force” and used within reason.*

### Example: list group

A very common pattern in websites is using lists because they semantically make sense but not wanting them to have bullets. This is called a “list group”.

Here’s a simple navigation, almost always a list, but rarely with bullets.

```html
<nav>
  <ul class="nav list-group">
    <li><a href="#">Terrestrial planets</a></li>
    <li><a href="#">Gas giants</a></li>
    <li><a href="#">Dwarf planets</a></li>
    <li><a href="#">Asteroids</a></li>
  </ul>
</nav>
```

We can use the `.list-group` class as a way to simplify, always removing the padding and bullets from a list.

```css
.list-group {
  padding-left: 0;
  list-style-type: none;
}
```

Another common thing we want with lists is to make the `<li>` elements horizontal, instead of stacked, called “inline list group”.

```html
<nav>
  <ul class="nav list-group list-group-inline">
    ⋮
```

Then with a little bit extra CSS we can have a list with no bullets and inline.

```css
.list-group-inline > li {
  display: inline-block;
}
```

Notice how I kept the two classes separate, so we could remove the bullets with one class, and make the items horizontal with another class.

### Example: buttons

Another great place to look for simplification is with buttons.

Here’s an example of a simple button:

```html
<a class="btn" href="#">Go!</a>
```

Here’s some standard CSS for a button:

```css
.btn {
  display: inline-block;
  padding: 0.5em 0.75em;
  background-color: red;
  border: 3px solid darkred;
  color: #fff;
  text-decoration: none;
}
```

Now, if I wanted a differently coloured button, it’s unnecessary to create a whole second class with duplicated CSS, I can just make a slight modifier class:

```css
.btn-bright {
  /* I only change those properties that are different */
  background-color: yellow;
  border-color: darkyellow;
  color: #000;
}
```

And apply it to my HTML like this:

```html
<a class="btn btn-bright" href="#">Go!</a>
```

So now the button inherits all the CSS from the standard `.btn` class plus the slightly modified `.btn-bright` class—creating much less duplicated CSS.

If you have a [modular type system](http://typografier.web-dev.tools) you can use the font-size classes to adjust the size of the button with another class:

```html
<!-- Inheriting the .mega class from the type system -->
<a class="btn btn-bright mega" href="#">Go!</a>
```

---

## Common website modules

- **[List group](http://learn-the-web.algonquindesign.ca/modules-code/list-group.html)**: vertical & horizontal lists.
- **[Buttons](http://learn-the-web.algonquindesign.ca/modules-code/buttons.html)**: small, medium, large, alternative, [buttons + modular typography](http://learn-the-web.algonquindesign.ca/modules-code/buttons-modular-type.html).
- **[Icons](http://learn-the-web.algonquindesign.ca/modules-code/icons.html)**: different sizes, stacked, inline, image replacement.
- **[Media object](http://learn-the-web.algonquindesign.ca/modules-code/media-object.html)**: flexible image size, embeddable, with list group, stacked, reversed.
- **[Embed containers](http://learn-the-web.algonquindesign.ca/modules-code/embed.html)**: for flexible images and videos, with specific aspect ratios—to prevent layout reflow after the image loads.

*The `common.css` file used in the examples and videos could be replaced by your modular typography `typography.css` file for better results.*

---

## Naming conventions

There are a couple major naming conventions for modular CSS that help clarify the intent of our classes and help us visualize the HTML by ust looking at the CSS classes.

- [BEM](http://bem.info/)
- [SMACSS](http://smacss.com/)

Part of what we learned today comes directly from SMACSS: the icon naming conventions.

BEM takes naming a little further by using double underscores or double hyphens to represent certain ideas.

- [Getting Your Head Around BEM Syntax](http://csswizardry.com/2013/01/mindbemding-getting-your-head-round-bem-syntax/)

```html
<div class="media media--highlighted">
  <div class="media__img"></div>
  <div class="media__body"></div>
</div>
```

1. Name your component with a descriptive phrase, e.g. `media`
2. Any classes that modify an original, base class, are separated with hyphens, e.g. `media--highlighted`
3. Any classes that represent pieces that are inside of the original class, or sub-components, are separated with underscores, e.g. `media__body`

I find it helpful to remember that when using **under**scores the element is **under** the original component.

Some people find this naming convention a little over-the-top—and I admit that sometimes I do myself. If you’re one of those people, that’s no problem, but keep the naming consistent for you and your team.

---

## Video list

1. [Modules: list group](https://www.youtube.com/watch?v=Kcd1742iCVA&list=PLWjCJDeWfDddIWwftJxBqtHpw8CbFMXsa&index=1)
2. [Modules: buttons](https://www.youtube.com/watch?v=u4yYGmI2-Qk&list=PLWjCJDeWfDddIWwftJxBqtHpw8CbFMXsa&index=2)
3. [Modules: making modular icons](https://www.youtube.com/watch?v=s8198ThMOgA&list=PLWjCJDeWfDddIWwftJxBqtHpw8CbFMXsa&index=6)
4. [Modules: combining the icons and the list group](https://www.youtube.com/watch?v=zfUErXraYCc&list=PLWjCJDeWfDddIWwftJxBqtHpw8CbFMXsa&index=7)
5. [Modules: icon image replacement](https://www.youtube.com/watch?v=bv6OQ6X5xWY&list=PLWjCJDeWfDddIWwftJxBqtHpw8CbFMXsa&index=8)
6. [Modules: media object](https://www.youtube.com/watch?v=bE0VpK1SjUc&list=PLWjCJDeWfDddIWwftJxBqtHpw8CbFMXsa&index=3)
7. [Modules: combining the media object and the list group](https://www.youtube.com/watch?v=V4QQFVa2Dok&list=PLWjCJDeWfDddIWwftJxBqtHpw8CbFMXsa&index=4)
8. [Modules: media object alternatives](https://www.youtube.com/watch?v=TTTrGPlIBJ8&list=PLWjCJDeWfDddIWwftJxBqtHpw8CbFMXsa&index=5)
9. [Modules: embed containers](https://www.youtube.com/watch?v=UQLq8w_gOv0&list=PLWjCJDeWfDddIWwftJxBqtHpw8CbFMXsa&index=10)
10. [Modules: embedding videos responsively](https://www.youtube.com/watch?v=noEcV1AFY-g&list=PLWjCJDeWfDddIWwftJxBqtHpw8CbFMXsa&index=11)
11. [Modules: embed containers with figures](https://www.youtube.com/watch?v=9tbM8i9K6lw&list=PLWjCJDeWfDddIWwftJxBqtHpw8CbFMXsa&index=12)
12. [Modules: combining buttons with modular typography](https://www.youtube.com/watch?v=z01-pDAd0HA&list=PLWjCJDeWfDddIWwftJxBqtHpw8CbFMXsa&index=13)

## Supplemental links

- [OOCSS](https://github.com/stubbornella/oocss/wiki)
- [An Introduction to OOCSS](http://coding.smashingmagazine.com/2011/12/12/an-introduction-to-object-oriented-css-oocss/)
- [The Flag Object](http://csswizardry.com/2013/05/the-flag-object/)
- [CSS Wizardry: CSS Guidelines](https://github.com/csswizardry/CSS-Guidelines)
- [Responsive Images: How to Prevent Reflow](http://andmag.se/2012/10/responsive-images-how-to-prevent-reflow/)
