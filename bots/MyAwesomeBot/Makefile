CC=g++
CFLAGS=-g

all: MyAwesomeBot

mm-client.o: mm-client.cpp mm-client.h

MyAwesomeBot.o: MyAwesomeBot.c mm-client.h
MyAwesomeBot: mm-client.o MyAwesomeBot.o
	${CC} ${CFLAGS} -o $@ $^

clean:
	rm -f *.o

fresh: clean all

