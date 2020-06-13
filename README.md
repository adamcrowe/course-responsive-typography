# course-responsive-typography
* Coursework: [Frontend Masters: Responsive Web Typography v2](https://frontendmasters.com/courses/responsive-typography-v2/)
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

