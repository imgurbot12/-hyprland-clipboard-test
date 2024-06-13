## hyprland wlr-data-control-unstable-v1 listener test

Design:

The following script uses an existing rust library
[wayland-clipboard-listener](https://github.com/Decodetalkers/wayland-clipboard-listener)
to bind to the
[wlr-data-control-unstable-v1](https://wayland.app/protocols/wlr-data-control-unstable-v1)
protocol and listen for Clipboard Selection Offers before calling
[recieve](https://wayland.app/protocols/wlr-data-control-unstable-v1#zwlr_data_control_offer_v1:request:receive)
to retrieve the associated clipboard data.

Getting Started:

```bash
$ git clone https://github.com/imgurbot12/hyprland-clipboard-test
$ cd hyprland-clipboard-test
$ cargo run
```
