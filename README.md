#Daze Material UI Concept

Because Photoshop is not fun. 

This is using Materialize.

====

##Tag CSS spritesheet

You can get a div element with a nice icon for a tag like this:

```html
<div class="daze-tag event text-only" style=""><div></div></div>
```

`daze-tag` signifies that this is a tag, `event` is the tag type (8 in total), and `text-only` will give you a text-only version of the tag with no background.

Tag options:

* `wtf`
* `hangout`
* `cop`
* `cool`
* `club`
* `music`
* `study`
* `event`

Note the nested `div` tags, this is important so it actually stays square and doesn't get way too big. Better than using JQuery for this purpose, yo.
