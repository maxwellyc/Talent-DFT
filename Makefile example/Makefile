all: hello

hello: hello.o main.o
    gcc -o hello hello.o main.o

hello.o: hello.c
    gcc -o hello.o -c hello.c -W -Wall -ansi -pedantic -l

make.o: make.c
    gcc -o make.o -c make.c -W -Wall -ansi -pedantic -l

clean:
    rm -rf *.o

mrproper: clean
    rm -rf hello