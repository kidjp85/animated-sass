animated-sass
=======================

> This Sass Mixin is based on the work being done here: http://daneden.github.io/animate.css/

ANIMATION TYPES
===============

**Attention seekers (flash, bounce, shake, tada)**

**Fading entrances (fadeIn, fadeInUp, fadeInDown, fadeInLeft, fadeInRight, fadeInUpBig, fadeInDownBig, fadeInLeftBig, fadeInRightBig)**

**Fading exits (fadeOut, fadeOutUp, fadeOutDown, fadeOutLeft, fadeOutRight, fadeOutUpBig, fadeOutDownBig, fadeOutLeftBig, fadeOutRightBig)**

**Bouncing entrances (bounceIn, bounceInDown, bounceInUp, bounceInLeft, bounceInRight)**

**Bouncing exits (bounceOut, bounceOutDown, bounceOutUp, bounceOutLeft, bounceOutRight)**

**Rotating entrances (rotateIn, rotateInDownLeft, rotateInDownRight, rotateInUpLeft, rotateInUpRight)**

**Rotating exits (rotateOut, rotateOutDownLeft, rotateOutDownRight, rotateOutUpLeft, rotateOutUpRight)**

## Usage
> For .sass file
```
.animated-elem
  +animated(fadeIn, 1s, 0.5s)
```

> For .scss file

```css
.animated-elem {
    @include animated(fadeIn, 1s, 0.5s)
}
```

## License
MIT