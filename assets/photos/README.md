# Drop your photos here

Square JPGs work best — around 800×800px is ideal.

To wire them into the gallery, open `../../index.html` and find the gallery
section (search for "Our story"). Each `.memory-card` has a `data-img`
attribute. Set it to point to your photo:

```html
<div class="memory-card" data-img="assets/photos/first_date.jpg">
```

If you don't add photos, the cards will show beautiful pink-gold gradients
with emoji icons — still lovely, just not personal.
