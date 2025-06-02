## Gnome shell numlock&capslock state indicator extension.

It shows notifications about numlock, capslock or fn lock state change.

![Screenshot](https://github.com/kazysmaster/gnome-shell-extension-lockkeys/raw/master/screenshot.png)

The original extension is available at (no fn-lock indicator): https://extensions.gnome.org/extension/36/lock-keys/

If you make any changes you can recompile the schemas file with the command `glib-compile-schemas <schemas-folder>`.

If you update the translations, run the `./po2mo.sh` script in the root directory.

In order to manually install this extension, copy lockkeys@vaina.lt to the:
~/.local/share/gnome-shell/extensions
