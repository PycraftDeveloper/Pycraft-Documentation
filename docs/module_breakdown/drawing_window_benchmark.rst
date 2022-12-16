drawing_window_benchmark
==========

run_drawing_window_benchmark
----------
__init__
__________
This subroutine is used to render the drawing window benchmark, accessible when run through the benchmark section of Pycraft. This test is the second of three designed to stress your system. This one is usually used to measure the performance of CPU rendering with Pygame on your device.

* Args:

  * self (dict): This is used by Pycraft as a way of storing it's current configuration and behaviour and is required by most GUIs. Its use should be reduced where possible for readability reasons.

  * iteration (int): In the benchmarking process, iteration is used to keep track of how long the benchmark has been running

  * Setfpslength (int): This is the length of the 'Setfps' array, we use this instead of specifying an integer in order to allow us to make changes later on in Pycraft's development about how many targets to use for the benchmark section.

  * Setfps (array): This is an array of integers that stores FPS targets for the benchmark section of Pycraft, with each element being a different FPS to try to reach, getting progressively harder. The FPS from this array is updated every 500 iterations of the benchmark.

  * fpscounter (int): This is used to store the index used to calculate the next element in the 'Setfps' array, this is used so Pycraft know's what to set the FPS to next, and what to set the caption to so that it displays the current FPS being tested.

  * Maxiteration (int): This is used to calculate after how many iterations we move onto the next targeted FPS, currently this is set to increase the FPS every 500 'iteration's.

  * display (Pygame Surface): The display object is used throughout Pycraft. This is the identifier we use when we want to interact with/draw to/update Pycraft's gui. Pygame is the main windowing engine used in Pycraft.

* Keyword Args:

  * None

* Output:

  * fpslistX (array): Used to store the iteration of the benchmark. This correlates to a point, with this making up the X coordinate and 'fpslistY' making up the Y coordinate. These points are later plotted (after a bit of processing) in the benchmark results screen on a line graph.

  * fpslistY (array): Used to store the FPS at a given iteration of the benchmark. This correlates to a point, with this making up the Y coordinate and 'fpslistX' making up the X coordinate. These points are later plotted (after a bit of processing) in the benchmark results screen on a line graph.

start
__________
This subroutine is used to render the drawing window benchmark, accessible when run through the benchmark section of Pycraft. This test is the second of three designed to stress your system. This one is usually used to measure the performance of CPU rendering with Pygame on your device.

* Args:

  * self (dict): This is used by Pycraft as a way of storing it's current configuration and behaviour and is required by most GUIs. Its use should be reduced where possible for readability reasons.

  * iteration (int): In the benchmarking process, iteration is used to keep track of how long the benchmark has been running

  * Setfpslength (int): This is the length of the 'Setfps' array, we use this instead of specifying an integer in order to allow us to make changes later on in Pycraft's development about how many targets to use for the benchmark section.

  * Setfps (array): This is an array of integers that stores FPS targets for the benchmark section of Pycraft, with each element being a different FPS to try to reach, getting progressively harder. The FPS from this array is updated every 500 iterations of the benchmark.

  * fpscounter (int): This is used to store the index used to calculate the next element in the 'Setfps' array, this is used so Pycraft know's what to set the FPS to next, and what to set the caption to so that it displays the current FPS being tested.

  * Maxiteration (int): This is used to calculate after how many iterations we move onto the next targeted FPS, currently this is set to increase the FPS every 500 'iteration's.

  * display (Pygame Surface): The display object is used throughout Pycraft. This is the identifier we use when we want to interact with/draw to/update Pycraft's gui. Pygame is the main windowing engine used in Pycraft.

* Keyword Args:

  * None

* Output:

  * fpslistX (array): Used to store the iteration of the benchmark. This correlates to a point, with this making up the X coordinate and 'fpslistY' making up the Y coordinate. These points are later plotted (after a bit of processing) in the benchmark results screen on a line graph.

  * fpslistY (array): Used to store the FPS at a given iteration of the benchmark. This correlates to a point, with this making up the Y coordinate and 'fpslistX' making up the X coordinate. These points are later plotted (after a bit of processing) in the benchmark results screen on a line graph.


