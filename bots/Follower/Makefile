CC=gcc
CFLAGS=-g

all: Follower

mm-client.o: mm-client.c mm-client.h

Follower.o: Follower.c mm-client.h
Follower: mm-client.o Follower.o
	${CC} ${CFLAGS} -o $@ $^

clean:
	rm -f *.o

fresh: clean all

