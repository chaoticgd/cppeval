cppeval
=======

An extremely hacky program that will take a C++ expression as an argument and
output the result.

Example:

	$ ./cppeval "1 + 2"
	3

	$ ./cppeval "srand(time(NULL)), rand()"
	1125357861

	$ ./cppeval "\"hello world\""
	hello world
