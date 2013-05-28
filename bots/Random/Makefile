CC=gcc
CFLAGS=-g

all: Random

mm-client.o: mm-client.c mm-client.h

Random.o: Random.c mm-client.h
Random: mm-client.o Random.o
	${CC} ${CFLAGS} -o $@ $^

clean:
	rm -f *.o

fresh: clean all

