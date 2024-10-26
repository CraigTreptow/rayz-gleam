# Rayz-ts

An implementation of a ray tracer based on the
["The Ray Tracer Challenge"](https://pragprog.com/book/jbtracer/the-ray-tracer-challenge)
book in Python.

## Set Up

1. See `.devcontainer/devcontainer.json`

## Running

`deno main.ts`

## Testing

`deno test`

_Note_: If you need print output while these are running, the `behave.ini` is
configured to allow it, but you will also need to run with the `--no-color`
option. _Note_: Even easier than the above is the add a couple of lines to all
output, then behave will get rid of them and you can see the output _and_ the
color.

## Linting

`deno lint`

## Formatting

`deno fmt`

## Grid

The canvas is a grid of pixels. The grid is defined by the number of rows and
columns. The rows are the Y axis and the columns are the X axis. The origin is
the bottom left corner of the grid. The X axis increases to the right and the Y
axis increases up.

R(y) . . . 3 2 1 0 1 2 3 ... C (x)

## Chapter 1

TBD

## Chapter 2

TBD

Run example:

`python -m rayz && cp projectile.ppm /mnt/c/Users/craig`
