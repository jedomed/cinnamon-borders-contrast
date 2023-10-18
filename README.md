## New solution

You can achieve basically the same thing as the theme by adding CSS like this to the end of **~/.config/gtk-3.0/gtk.css**:
```css
decoration {
    box-shadow: black 0 0 0 3px, #eeeeee 0 0 0 1px;
}
```

This seems way cleaner than the original solution, and probably works with all themes. I only checked a few. 

![screenshot](https://github.com/jedomed/cinnamon-borders-contrast/blob/main/gtkcss.png)

---

## Original solution

This is a Flat Remix theme adjusted to have white borders around windows for better contrast. **NOTE:** Looks like Window Borders were removed from Theme settings, so this is useless on new versions of Cinnamon.

* [Flat Remix](https://github.com/daniruiz/flat-remix-gtk)

![screenshot](https://github.com/jedomed/cinnamon-borders-contrast/blob/main/theme.png)
