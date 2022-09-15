<div id="top"></div>

<br />
<div align="center">
  <a href="https://github.com/serhaturtis/AC-Pitch-Black-Forest">
    <img src="outputs/images/front.png" alt="Pitch Black Forest" width="600">
    <img src="outputs/pcb/pcb.PNG" alt="Pitch Black Forest" width="600">
  </a>

<h3 align="center">PITCH BLACK FOREST</h3>

  <p align="center">
    A Preamp Inspired By Ueberschall
  </p>
</div>


<!-- WHAT -->
## What?

This is a two stage guitar preamp board with gain, treble, mid, bass, voicing, filter bands and volume controls. And a boost switch.

## Why?

Because I wanted to experiment with JFETs and also have a small preamp board that I was going to use on another project.

## How?

Usage:
	advctrli2c -a <i2c number> -i <input_type> -c <input_channel>
	input types: 0: PAL, 1: NTSC
	input channels: CVBS: 0-7, SVIDEO: 8-11

