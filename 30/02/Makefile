build:
	as -o hello.o hello.s; ld -dynamic-linker /lib64/ld-linux-x86-64.so.2 -lc -o hello hello.o
clean:
	find . ! -name Makefile ! -name hello.s -type f -delete
