# base16-waybar

This repo provides templates for using
[Base16](https://github.com/chriskempson/base16) color schemes with
[Waybar](https://github.com/Alexays/Waybar), a status bar for Wayland
compositors like [Sway](https://github.com/swaywm/sway).

It's still a work in progress, and right now only provides the Base16 colors as
CSS variables. You can download the generated color files and then include them
to use the CSS variables `@base{00-0F}` in a Waybar style config like this:

```css
@import "/path/to/color/scheme.css";

window#waybar {
  color: @base04;
}
```
