# course-css-typography
* Coursework: [Frontend Masters: Responsive Web Typography v2](https://frontendmasters.com/courses/responsive-typography-v2)
	* [Repository](https://github.com/jpamental/rwt-vf-workshop-full)

## Performance
* Select fonts with care
* Load only what you need
* Don't block the page draw

## Progressive
* Plan for failure
* Optimize loading
* Provide fallbacks

## Proportion
* Type scale for small screens

## Units
> There's no need to have pixels value in your CSS
* 1em = 16px
* Width in em = desired width in px / 16
* ems are relative to the parent
* rems are relative to the root (typically 16px)

## Line Length
``` css
@media (min-width: 58em) { /* 58em * 16px = 928px */
	p { max-width: 38em; } /* 65-70 characters */
}
```

## Proportional Scaling Formula
* [Flexible typography with CSS locks](https://blog.typekit.com/2016/08/17/flexible-typography-with-css-locks)

## Variable Fonts
* [Can I use variable fonts?](https://caniuse.com/#search=variable%20fonts)
* [Can I use font-variation-settings?](https://caniuse.com/#search=font-variation-settings)
* [How to start with variable fonts on the web](https://www.zeichenschatz.net/typografie/how-to-start-with-variable-fonts-on-the-web.html)
* [Variable Web Typography](https://zeichenschatz.net/demos/vf/variable-web-typo)
* [Implementing a variable font with fallback web fonts](https://www.zeichenschatz.net/typografie/implementing-a-variable-font-with-fallback-web-fonts.html)
* [Variable Fonts 101](https://www.monotype.com/resources/expertise/variable-fonts-101)
	* [FF Meta Variable Font Demo](https://codepen.io/jpamental/pen/MGEPEL)
* [What should brands know about variable fonts?](https://www.monotype.com/resources/expertise/variable-fonts-for-brands)




