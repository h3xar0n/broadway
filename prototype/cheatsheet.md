# HTML/CSS Project: Broadway
## Cheat Sheet: Creating HTML elements, styling with CSS

---
### HTML

Creates a list item (can be added within an unordered list):

```html
<li>Apples</li>
```

Creates an unordered list (can store list items):

```html
<ul>
</ul>
```

Creates a link:

```html
<a href="http://www.google.com">Search Here!</a>
```

Creates a link with a class name of `knowledge`:

```html
<a href="http://www.google.com" class="knowledge">Search Here!</a>
```

More knowledge available at: https://www.codecademy.com/articles/glossary-html

---
### CSS

To reference an HTML element with a class of `banner`:

```css
.banner {
  
}
```

Change the background color of an HTML element with a class of `banner`:

```css
.banner {
  background-color: #FFFFFF;
}
```

Change the background image and size of an HTML element with a class of `banner`:

```css
.banner {
  background-image: url(the-link-to-the-image-goes-here);
  background-size: size-options-go-here;
}
```

To display `<li>` HTML elements (within a `<ul>` HTML element) on one line:

```css
.ul-class-name li {
  display: inline;
}
```

More knowledge available at: https://www.codecademy.com/articles/glossary-html