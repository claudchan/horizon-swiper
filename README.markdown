# Horizon Swiper
#### Version 1.1.1

You will love this light (~ 7kb) free swiper.
It comes with many options and it works with your simple native browser scrolling.
Try it on touch devices!

## Documentation
[http://horizon-swiper.sebsauer.de](http://horizon-swiper.sebsauer.de)

### HTML
```
<div class="horizon-swiper">
  <div class="horizon-item"></div>
  <div class="horizon-item"></div>
  <div class="horizon-item"></div>
</div>
```

### Javascript
```
$('.horizon-swiper').horizonSwiper();
```

### Options

Variable | Type | Default | Description
------ | ---- | ------- | -----------
item | string | '.horizon-item' | Selector for the swiper items.
showItems | string or integer | 'auto' | Set 'auto' for the original item width or an integer for a numer of items. For example, set 2 for a 50% item width.
dots | boolean | false | Enable or disable the slide dots (pagination).
numberedDots | boolean | false | Enable or disable numbers for the slide dots.
dotsContainer | string | $(element) | Change where the navigation dots are attached (Selector, htmlString, Array, Element, jQuery object)
arrows | boolean | true | Enable or disable the slide to next or previous item arrows.
arrowPrevText | string | '' | Text for the slide to previous button.
arrowNextText | string | '' | Text for the slide to next button.
animationSpeed | integer | 500 | Time to slide to the next item.
mouseDrag | boolean | true | Enable or disable the mousedrag (includes no touch).

### Browser support
* Google Chrome
* Mozilla FireFox
* Safari
* Internet Explorer (11, 10, 9, 8)
* Microsoft Edge

## Author
Sebastian Sauer - [http://www.sebsauer.de](http://www.sebsauer.de)
