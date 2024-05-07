# Keychron Q60 Configuration

This repository hosts the source code for the [QMK firmware](https://qmk.fm/)
that powers my
[Keychron Q60 Max](https://www.keychron.com/products/keychron-q60-max-qmk-via-wireless-custom-mechanical-keyboard).
See instructions below to compile from source. It also contains my custom
layout, for use in [VIA](https://www.caniusevia.com/).

![Keychron Q60 Max](https://cdn.shopify.com/s/files/1/0059/0630/1017/files/Keychron-Q60-Max-QMK-VIA-Custom-Mechanical-Keyboard-2_ff1caf01-49d3-4b6a-a002-b2f613da13e1.jpg?v=1702534477)

Make example for this keyboard (after setting up your build environment):

```bash
make keychron/q60_max/ansi/rgb:default
```

Flashing example for this keyboard:

```bash
make keychron/q60_max/ansi/rgb:default:flash
```
