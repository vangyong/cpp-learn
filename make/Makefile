main: main.o mytool1.o mytool2.o
	gcc -o main main.o mytool1.o mytool2.o
#	gcc -o $@ $^

main.o: main.c mytool1.h mytool2.h
	gcc -c main.c
#	gcc -c $<

mytool1.o: mytool1.c mytool1.h
	gcc -c mytool1.c
#	gcc -c $<

mytool2.o: mytool2.c mytool2.h
	gcc -c mytool2.c
#	gcc -c $<


# 简化后的 Makefile
# main：main.o mytool1.o mytool2.o
#	gcc -o $@ $^
#	.c.o：
#	gcc -c $<
