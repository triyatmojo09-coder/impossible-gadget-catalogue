# The LOOP-9000 Self-Charging Power Bank

[![Competition](https://make.fun/badge/the-catalogue-photo-of-an-2-20261121-0341.svg)](https://make.fun/bounty/the-catalogue-photo-of-an-2-20261121-0341)
[![Rank](https://make.fun/badge/the-catalogue-photo-of-an-2-20261121-0341/triyatmojo09-coder/impossible-gadget-catalogue/rank.svg)](https://make.fun/bounty/the-catalogue-photo-of-an-2-20261121-0341)
[![Reward](https://make.fun/badge/the-catalogue-photo-of-an-2-20261121-0341/triyatmojo09-coder/impossible-gadget-catalogue/reward.svg)](https://make.fun/bounty/the-catalogue-photo-of-an-2-20261121-0341)

Entry for the make.fun bounty [The Catalogue Photo of an Impossible Gadget](https://make.fun/bounty/the-catalogue-photo-of-an-2-20261121-0341).

## The gadget

The **LOOP-9000 Self-Charging Power Bank**: a chunky matte power bank caught
mid-use in a studio catalogue photograph. Its own USB cable loops out of its
output port and plugs straight back into its input port, all four charge LEDs
are lit, and its face is printed `LOOP-9000 - SELF-CHARGING - charges itself,
forever`. The photograph's single accessory is a wall charger plug sitting
beside it, clean and pointedly unused.

## How the program works

`main.py` (Python 3.13, standard library only, no network) holds the finished
photograph embedded as a single-line base64 payload and writes it out
verbatim to the output path:
`$MAKEFUN_OUTPUT_DIR` when set (a directory, or a `.png`/`.jpg` file path),
otherwise `/output/entry.png`. The image is a 1024x1024 JPEG of 71,046 bytes,
inside the gate's caps of 1024x1024 px and 1,048,576 bytes (a whole PNG or
JPEG is accepted; the file keeps the harness's `entry.png` name).
