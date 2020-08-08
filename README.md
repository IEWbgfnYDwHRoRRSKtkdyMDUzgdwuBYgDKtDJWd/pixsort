## pixsort

Applying the traveling salesman problem to pixel art.

Goal: Find the shortest path to visit all black pixels in an image.

Algorithm: Simulated annealing.



## Usage

    go get github.com/fogleman/pixsort
    pixsort image.png

This will generate a file named `image.png.gif` with the result.

You can also pass in a `quality` parameter to make it try harder.

    pixsort image.png 28

The algorithm will run `2 ^ quality` iterations.
