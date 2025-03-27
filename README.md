1) Van elke afbeeldingen heb je een thumbnail nodig van breedte 360. Je kan bv. de volgende website gebruiken: https://imageresizer.com/bulk-resize. Zet de Width als 360 met 'Lock aspect ratio' en download de afbeelding als .jpg. De thumbnail gaat in ```images/thumbs``` en de afbeelding van hoge kwaliteit gaat in ```images/full```
2) Je voegt een afbeelding toe met het volgende blokje:

```html
<article class="thumb">
    <a href="images/fulls/image.jpg" class="image"><img src="images/thumbs/image.jpg" alt="" /></a>
    <h2 style="color: black;">Dit is een titel</h2>
    <p> Dit is een beschrijving</p>
</article>
```

waar je eventueel een titel kan toevoegen en de kleur van de titel kan aanpassen. De eerste href link is naar de hoge kwaliteit, de tweede naar de thumbnail. 
