`yttrium` is a CSS "micro-framework" that provides a handful of
boilerplate mechanisms for writing CSS inspired by skeleton. Pair with
your preferred CSS normalization library.

```HTML
<link rel="stylesheet" href="//jcmdln.org/yttrium/yttrium.css">
```


## Goals

I've used various frameworks like Bootstrap, Foundation, Pure, Skeleton,
and some others. While they are helpful in making a pleasant UI, they
make too many design decisions that I then have to overwrite. This
project exists to only provide mechanisms for the most generic of tasks
like handling containers, grids, and clearly named selectors so you
won't have to look up the mnemonic form.


## Features

* 3.8K raw, 2.4K minified, 1K gzipped and minified
* No UI/UX design decisions baked-in
  * Well, that is a lie
    * Mobile-first development by default
    * Lists have simplistic margins
    * Defined a style for code snippits
    * Generic image sizes
      * avatar
      * background
      * banner
      * icon
* No cryptic CSS selector names
  *
* Infinitely nested containers
* 12-column grid system
* Optional media scaling while preserving aspect ratio
* Optional GPU acceleration
* Optional selector to mimic Material Design cards


## Contributing

The goal is to abstract away pointlessly repetitive tasks without
defining the presentation. Any CSS selectors that provide a useful
utility are ideal targets.

Do you think `yttrium` is missing something? Please file an issue or
submit a pull request!
