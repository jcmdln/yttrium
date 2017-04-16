# yttrium
Web development micro-framework using raw CSS & JavaScript

- Contains only the most essential CSS for a mobile-first design
  - Unopinionated design, doesn't force any stylization
- Implements many common frontend tasks while being JQuery-free
  - MVC tasks may use MithrilJS, though I'm focusing on using raw JavaScript
  - Long-term target of implementing the vital pieces of Bootstrap, Foundation, etc

I highly recommend using ```Normalize``` along with ```yttrium``` to ensure cross-browser consistency:

```HTML
<link rel="stylesheet"
      href="//cdnjs.cloudflare.com/ajax/libs/normalize/6.0.0/normalize.min.css">
<link rel="stylesheet"
      href="//raw.githubusercontent.com/jcmdln/yttrium/master/yttrium.css">
<script src="//raw.githubusercontent.com/jcmdln/yttrium/master/yttrium.js"></script>
```
