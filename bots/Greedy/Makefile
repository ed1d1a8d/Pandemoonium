CC=gcc
CFLAGS=-g

all: Greedy

mm-client.o: mm-client.c mm-client.h

Greedy.o: Greedy.c mm-client.h
Greedy: mm-client.o Greedy.o
	${CC} ${CFLAGS} -o $@ $^

clean:
	rm -f *.o

fresh: clean all

