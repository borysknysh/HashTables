# HashTables
This program is being designed for studying basics of hash tables and algorithms of its filling. It has been shown that for the hash table of 500000 size (by default) and randomly generated keys with hash-function key%elements_to_fill, time wouldn't grow up drastically untill number of elements in the table less than 2^10, which is 1000 elements!
Unless simple hashing, hashing with linked list gives time of filling much smaller.

In order to start one has to create build directory in the program's folder, move to this directory and run CMake:
mkdir build
cd build
cmake ../
make -j4
./main
