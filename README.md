# Unnamed Keyboard

A (work-in-progress) keyboard.

## Parts

The PCB is built around the following components

- [RP2040 Microcontroller](https://www.raspberrypi.com/documentation/microcontrollers/rp2040.html)
- [Kailh CPG151101S11 Hotswap Sockets](http://www.kailh.com/en/Products/Ks/HPC/883.html)
- [EC11E Rotary Encoder](https://tech.alpsalpine.com/e/products/category/encorder/sub/01/series/ec11e/)
  - Any EC11E rotary encoder will do as long as it has a push-on switch (i.e. it can be pressed down)
  - I used the [Alps EC11E15244G1](https://tech.alpsalpine.com/e/products/detail/EC11E15244G1/)
- ... remaining parts to be determined

## Useful Resources

This is my first attempt at designing anything keyboard related, and I've been referring to various guides online to come up with these designs. I've listed some of the resources I've used below:

- [Keyboard Layout Editor (KLE)](http://www.keyboard-layout-editor.com/) for designing and exporting the layout
- **PCB Design**
  - [Noah Kiser](https://www.youtube.com/@noahkiser)'s PCB design videos on YouTube
  - [ebastler/marbastlib](https://github.com/ebastler/marbastlib) KiCAD library with various keyboard-related parts and footprints
  - [zykrah/kicad-kle-placer](https://github.com/zykrah/kicad-kle-placer) KiCAD plugin for placing switch footprints based on a KLE
