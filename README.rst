MotoROS Application
------------------

Code from

https://github.com/ros-industrial/motoman

motoman_driver/MotoPlus

The difference from the original is that there is a lot more functionality added after stress testing with Motoman robots. Eventually the changes here should be merged into the original code base, but until then, this is all we have.



Should be compiled with MotoPlus tools and generate a .out file to be run on the motoman controller.

The robot bridge uses the header files to sync with the structures that are used to communicate with it.

