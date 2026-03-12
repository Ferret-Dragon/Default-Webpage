# Website Name
To modify the website name, edit:
```html
const SITE_NAME = "My Website";
```

# Color Palette
Color palletes can be modified in style.css
Each modular part can also be found there

# Content
There are two different classes of content: 

### content
Use this for normal left-aligned sections.

```html
<section id="content-section" class="content">
    <h2>Content Section</h2>
    <p>Your content here</p>
</section>}
```

### content centered
Use this for centered content sections
```html
<section id="centered-section" class="content centered">
    <h2>Centered Section</h2>
    <p>Your content here</p>
</section>
```

### Left content header, content centered
```html
<section id="content-section" class="content">
    <h2>Content Section</h2>
</section>}
<section id="centered-section" class="content centered">
    <p>Your content here</p>
</section>
```

### Centered content header, content on the left
```html
<section id="content-section" class="content centered">
    <h2>Content Section</h2>
</section>}
<section id="centered-section" class="content">
    <p>Your content here</p>
</section>
```
