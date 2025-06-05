# Shop2

## Custom Show Slider Snippet

This repository includes a sample Liquid snippet `showslider.liquid` and a small CSS file `custom-slider.css`.
These files demonstrate how to configure a slider so that different images display depending on screen width.

1. **Snippet**: `snippets/showslider.liquid` expects two section settings: `desktop_image` and `mobile_image`.
2. **Stylesheet**: `assets/custom-slider.css` defines `.desktop-only` and `.mobile-only` classes.

Add the CSS to your theme and include the snippet where you want the slider to appear:

```liquid
{% render 'showslider' %}
```

Remember to configure the images in the theme editor once the snippet is installed.
