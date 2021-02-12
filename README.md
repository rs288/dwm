# Rs build of dwm

## Patches and features
- Clickable statusbar with my build of [dwmblocks](https://github.com/rs288/dwmblocks)
- Fake full screen: Only allow clients to "fullscreen" into space currently given to them.
- Horizgrid: It arranges windows in a grid pattern in which every window is roughly the same size, adjusted such that there are no gaps.
- Pertag: This patch keeps layout, mwfact, barpos and nmaster per tag.
- Restartsig: dwm can now be restarted via MOD+CTRL+SHIFT+Q
## Installation for newbs

```
git clone https://github.com/rs288/dwm.git
cd dwm
sudo make install
```
## to add color emoji to dwmblocks install `libxft-bgra`!

This build of dwm does not block color emoji in the status/info bar, so you must install [libxft-bgra](https://aur.archlinux.org/packages/libxft-bgra/) from the AUR, which fixes a libxft color emoji rendering problem, otherwise dwm will crash upon trying to render one. Hopefully this fix will be in all libxft soon enough.
