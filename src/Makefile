CFLAGS=-std=c11 -g -static

scrach-compiler: scrach-compiler.c

test: scrach-compiler 
		../test/test.sh

clean: 
		rm -f scrach-compiler *.o *~ tmp*

.PHONY: test clean
