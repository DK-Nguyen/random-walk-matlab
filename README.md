# Scientific Computing Project
## Minimum Requirements
1. - [x] A Start/Stop button for starting and stopping the animation.
2. - [x] Static text fields for printing the x- and y-coordinates of the current location.
3. - [x] A drop down menu for selecting the marker.
4. - [x] A spinner for setting the marker size.
5. - [x] A button for selecting the marker face (default red) and edge (default black) colors from a palette.
6. - [x] A way of setting the initial axes limits and the amount to change them when the marker goes outside the current limits.
7. - [x] A numeric edit field for setting the step size.
***
### To get grade 4
8. - [x] An option for leaving a trail of previous points visible. Use *animatedline* for this. In this case the user should be able to choose the line style (including ’none’), color and width. It should also be possible to set the marker to ’none’. Of course the marker and line style shouldn’t be set to ’none’ at the same time, so you should give an error message if the user tries to do this.
9. - [x] Usually the angle θ is uniformly distributed in the interval [0.2π). Add the option of θ having a uniform discrete distribution of values 2πk/n for k = 0, . . . , n − 1 with equal probability. Here we must have n ≥ 3. The case n = 4 is the widely used rectangular discrete walk where the walk moves to right, left, down, or up with equal probability.
***
### To get grade 5
10. - [x] Add an option to change the boundary behaviour so that if x goes outside the axis on the right (left) it comes back from the left (right) and similarly for y. This means that we have glued the line x = xmin to the line x = xmax and the line y = ymin to the line y = ymax. This makes the square into a torus.
11. - [x] An option for making the random walk in 3 dimensions. Then you must add the z coordinate to all relevant places, such as axis limits. You also need two angles, latitude θ ∈ [0.π] and longitude φ ∈ [0.2π). When computing the x, y, and z values using spherical coordinates.
***
### Bonus
12. - [x] RESET button
13. - [x] Program log