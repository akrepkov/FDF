The program reads the coordinates of the landscape from a .fdf file provided as a parameter. Each number in the file represents a point in space, where the horizontal position corresponds to its x-axis, the vertical position corresponds to its y-axis, and the value corresponds to its altitude on the z-axis. The program then renders the landscape in isometric projection using the MiniLibX library.

To build the project, run:
<pre>
make
</pre>

To render a landscape, execute the program with a .fdf file as a parameter:
<pre>
./fdf maps/42.fdf
</pre>

<img src="first.png"  style=" height: auto;"><img src="mars.png" style="height: auto;">
