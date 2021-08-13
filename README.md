# Bootstrap Maps

Responsive maps with Bootstrap 5. Google maps, vector maps, contact us section template & more.

With Bootstrap you can use Google Maps as well as dedicated vector maps. You can select certain regions, subcontinents, continents countries & cities. Maps are also a great way to present data or set up a country filter.

## Basic examples

#### Google Map in Bootstrap grid

You have to add class `.w-100` to the `iframe` element in order to make sure that your Google Map embeds are fully responsive. You should also delete the fix height & width that Google adds to Map embeds by default. Learn more about the `w-100` class in the [Sizing Utilities](https://mdbootstrap.com/docs/standard/utilities/sizing/) documentation.

```html
<div class="row w-100">
  <div class="col-lg-6 my-4">
    <iframe
      src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d115681.29592731265!2d-77.47713270775661!3d25.0326996781907!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x892f7c99b981dbc9%3A0x2aef01d3485e50d2!2sNassau%2C%20Bahamy!5e0!3m2!1spl!2spl!4v1624445118063!5m2!1spl!2spl"
      class="w-100" height="400" allowfullscreen="" loading="lazy"></iframe>
  </div>
  <div class="col-lg-6 my-4 d-flex align-items-center">
    <div>
      <h6>This map is embedded in a 6 column layout</h6>
      <p>Try to resize your browser window - you will see that it starts to take up 12 columns on
        screens smaller than 992px.</p>
      <p>This useful feature helps to make your embedded map responsive (<strong>mobile
          friendly</strong>). You can customize responsive behavior with the use of <a
          href="https://mdbootstrap.com/docs/standard/layout/breakpoints/">breakpoints</a>.</p>
      <p>This text looks so nice because it's <strong>vertically centered</strong> you can achieve
        this effect using the <a
          href="https://mdbootstrap.com/docs/standard/layout/vertical-alignment/">vertical
          alignment</a> layout option.</p>
    </div>
  </div>
</div>
```

#### Much more examples and a detailed description can be found at [📄 Maps documentation page](https://mdbootstrap.com/docs/standard/extended/maps/)
