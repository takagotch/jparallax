### jparallax
---
https://github.com/stephband/jparallax

```
git clone git://github.com/stephband/jparallax.git
jQuery( '.parallax-layer' ).parallax( options );

```

```
<ul>
<li class="parallax-layer"></li>
<li class="parallax-layer"></li>
</ul>
```

```css
.parallax-viewport
  { position:relative; overflow:hidden; width:npx;
height:npx; }

.parallax-layer
  { position:absolute; }
```

```js
jQuery('.parallax-layer').parallax(options, layer_0_options, layer_1_options, ...);

jQuery('.parallax-layer').parallax({}, {}, {xparallax: '200px'});

jQuery('.parallax-layer').trigger('freeze');
```

