# REVERT BLUE GRAYS IN GNOME 47+

This repo contains gtk3 and gtk4 css files and a gnome shell theme to revert blue gray tints because they look awful (subjective opinion)

## Installation

`gtk-[34].0/gtk.css` should go into `~/.config/gtk-[34].0/gtk.css`. I am using them with [`adw-gtk3` theme](https://github.com/lassekongo83/adw-gtk3). If you don't use it. you can skip the gtk-3.0 file, probably.

The shell theme (`gnome-blue-revert`) goes into `~/.local/share/themes/`. Use gnome tweaks to apply the shell theme.

## Shell theme accent color

The shell theme has to change the accent colors of the control popout (upper left corner) too. You can take screenshots of the buttons when it's activated, hovered (when activated) and pressed down (when activated) with the theme turned off and use eyedropper on teh screenshots to get the necessary colors.

## Credits

General credit to 242424color from gnome discourse forum: https://discourse.gnome.org/t/adwaita-tint-in-gnome-48/27577/19

I had to do quite a bit to get the shell theme to work properly though.

### Closing notes

You know, it would be nice if they gave us a choice, not just force the change. The blue tint looks horrible and "just change your display temperature / color balance" is the shittiest solution I've ever heard, since it affects every other app on the system.

I do plan on making patches for gtk, libadwaita, gnome shell and others to revert the colors at the source (so I can just do that on my gentoo system), no ETA lmfao.
