# IgnCoilAnalize
Spark ignition coil analyzer application for Windows

Many years ago we developed a simple application for quick assessment and comparison of automotive ignition coils using a few simple measurements. This application was used internally by us, now we are sharing this program for personal use. 

This simple applications takes the result of a few measurements of an ignition coil primary and secondary, and calculates theoretical parameters like primary charge time, secondary peak voltage, spark burn time, etc. There is a PDF document that outlines the use of the program along with several sample tests.

The application was written in Visual C++ for 32-bit Windows but should also work on newer Windows operating systems. This is a very simple application, totally standalone without any installer - just copy the executable and run locally within a windows folder. There is nothing saved or persistent, applications starts with a default set of values and nothing is saved. Again, this was designed for internal use and there was little error checking performed. However the calculations are very useful for comparing an unknown ignition coil. As such, there are no guarantees of its use, and the code is to be used as-is without any warranty for its use. It is also unsupported and will not be updated with corrections/additions/etc.
