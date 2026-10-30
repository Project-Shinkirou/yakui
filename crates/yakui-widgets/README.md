`yakui_widgets` contains the built-in widgets and related helpers for [yakui](https://github.com/SecondHalfGames/yakui), a declarative UI library for games.

Most of this crate is also re-exported from the [`yakui`](https://docs.rs/yakui) crate.

You might also be interested in:
* [`yakui`](https://docs.rs/yakui)
* [`yakui_core`]
* [`yakui_app`](https://docs.rs/yakui-app)

## Features

The `text` feature enables built-in font storage and rendering, text widgets,
text buttons and windows, and their shorthand helpers. It is enabled by the
default `default-fonts` feature. Applications that provide their own text layout
can disable default features to use layout, image and interaction widgets without
linking the built-in text backend. `system-fonts` also enables `text`.