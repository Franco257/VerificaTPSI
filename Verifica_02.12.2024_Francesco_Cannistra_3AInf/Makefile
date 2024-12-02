all: main 


clean: main main.o math.o pow.o 
	rm -rf main main.o math.o pow.o

main: main.o math.o pow.o
	gcc -o main main.o math.o pow.o

main.o: main.c math.h pow.h
	gcc -c -o main.o main.c

math.o: math.c
	gcc -c -o math.o math.c  

pow.o: pow.c
	gcc -c -o pow.o pow.c

