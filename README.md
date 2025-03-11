# Prose Style

A lightweight and responsive CSS stylesheet for better prose styling. Developed with SCSS. Used to style basic HTML elements.

## Usage

### Include the CSS file:

```html
<link rel="stylesheet" href="prose.min.css">
```

## Wrap your content with the "prose" class:

```html
<div class="prose">
    Your content...
</div>
```

### Customize Prose Style variables in your own stylesheet:

```css
:root{
    --prose-font: "Montserrat";
    --prose-text-color: #231f20;
    --prose-primary-color: #0d6efd;
    --prose-secondary-color: #6c757d;
    --prose-background-color: #f5f5f5;
    --prose-title-text-color: #fff;
    --prose-title-background-color: #6c757d;
    --prose-border-color: #ddd;
}
```

### Notes:

* The CSS file should be included in your project before using "**prose**" class.
* Wrap your content inside a **&lt;div class="prose"&gt;** to apply the styles.
* The variables allow you to easily customize colors and typography without modifying the main stylesheet.