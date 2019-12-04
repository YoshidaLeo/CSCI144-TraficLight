CSCI 144 Project

This project was developed and tested on Linux Ubuntu 18.04.3

Compiler: g++ C++11

To Compile use `g++ -pthread -o proj project.cpp`
To Run use `./proj`

NOTE:

For this project, I changed how the directions are read from the file. 
In the input files, if the direction is N, it means the car is traveling from South to North.
When reading the input files I separeated the direction into origin and destination.
Therefore, a car with direction N in the input file will be converted to `origin = South` and `destination = North`.
Other examples: A car with direction NE in the input file will be converted to `origin = S` and `destination = E`.

OUTPUT:

The output of this program can be seen in the console or in the file created after execution calles outFile.txt.