Main: main.cpp my_print.asm
	nasm -felf32 my_print.asm -o my_print.o
	g++ main.cpp my_print.o -o main -std=c++11
	rm -rf my_print.o
clean:
	rm -rf main
