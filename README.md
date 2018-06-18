Arty Z7-20 Monte Carlo Pi Simulator VGA
============
Created for Vivado 2016.4

This demo provides a visualization of a Monte Carlo experiment for estimating
the value of pi. The demo will display one quadrant of a circle and randomly
generated coordinate points. Points that lie within the circle are colored red;
points that lie outside the circle are colored green. The ratio of the number of
points within the circle to the total number of points generated gives an
estimate of pi/4. Multiplying this value by 4 would give an estimate of pi.

The frequency at which coordinate points are generated can be selected by the
switches. The frequencies are:
- SW1 down, SW0 down 152.59 Hz
- SW1 down, SW0 up   610.35 Hz
- SW1 up,   SW0 down 2.441  kHz
- SW1 up,   SW0 up   9.765  kHz

The materials needed for this demo project are
- Arty Z7-20 board
- Micro-USB cable
- PmodVGA
- VGA monitor and cable

Download and Launch the Demo
------------
Follow the [Using Digilent Github Demo Projects](https://reference.digilentinc.com/learn/programmable-logic/tutorials/github-demos/start)
tutorial. This is an HDL design project and does not require the Xilinx SDK.
Select the tutorial options appropriate for a Vivado-only design. Return to this
guide when prompted to check for additional hardware requirements and setup.

Once you have generated the bitstream, make sure that you have your PmodVGA
plugged into the Arty Z7's Pmod ports. Use a VGA cable to connect the PmodVGA
to your monitor's VGA port. Return to the Github Projects tutorial to finish
programming your board.
