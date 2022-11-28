![](../../workflows/gds/badge.svg) ![](../../workflows/docs/badge.svg)

# 4-Bit Tristate Loadable Counter
This IP block simulates a 4-bit scalable synchronous (parallel) counter. Applications are CPU's, PWM signal generators, etc. 

## Features: 
- tri-direction (pause, count up, count down) 
- loadable (use pin[4:7], eg. for jump instruction, initialization at boot up) 
- synchronous output(at rising edge) with async (ripple) setup of next count) 
- easy to control, fast and scalable (each 1 bit counter only depends on previous counter)

## Interactive simulation 
https://wokwi.com/projects/341423712597181012

## Video
https://youtu.be/a_5DLUsAf9g

## Images
[![Chip interface made with Mixed Radix Circuit Synthesis tool](https://i.imgur.com/tyMDeKP.png)]() 

[![Gate level implementation overview](https://i.imgur.com/DbY4sNm.png)]()

[![GDS (die) shot](https://i.imgur.com/uEzMofO.png)]()

# What is Tiny Tapeout?

TinyTapeout is an educational project that aims to make it easier and cheaper than ever to get your digital designs manufactured on a real chip!

Go to https://tinytapeout.com for instructions!
