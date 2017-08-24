# thwombly
## Outrageous typography for the web

### Why is web typography sooooo boooring?

The web has everything: animations, all the fonts in the world, images, video, 3D - we've got it all, really.
Still, the web looks really, really boring.

Let's fix that

## Usage
`npm install thwombly`
or 
`<script src="I hope we get a CDN dot min dot js">`

### Then:
```
<p data-thwombly={type="edgy"}>Stack them letters hon</p>
<p data-thwombly={type="preachy", image="image.jpg"}>Background images and cutout text</p>
<div data-thwombly={type="rawhide"}>Put it in any tag</div>
```
Thwombly will replace the content of that element with a more fun typography and cool effects. Sorta full with Kinda deal works best, and inline elements are probably not a great idea, but do what you want, it's your site.

### Api
```
<p data-thwombly={
  type= edgy | preachy | rawhide - *required*
  image= url to suitable image
  font= name of a font on Google Fonts
}
```

### Why is it called "Thwombly"?
Thwombly is named after one of our great contemporary typographers, Carol Thwombly, who not only created several classic fonts you've probably heard of, such as Myriad, Trajan, Lithos and Charlemagne. However, and perhaps more importantly, she also created the original iteration of whimsical and delightfully reader-unfriendly Viva, which has spruced up countless party invitations, book covers, advertising sprees and magazine spreads since its initial release in 1993. Viva is bold, brazen, colourful and highly impractical - just the kind of typography the modern web desperately needs more of.
