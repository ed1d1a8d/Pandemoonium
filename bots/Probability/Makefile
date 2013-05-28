CC=gcc
CFLAGS=-g

all: Probability

mm-client.o: mm-client.c mm-client.h

Probability.o: Probability.c mm-client.h
Probability: mm-client.o Probability.o
	${CC} ${CFLAGS} -o $@ $^

clean:
	rm -f *.o

fresh: clean all

