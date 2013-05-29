CC=g++
CFLAGS=-g

all: MyAwesomeBot

mm-client.o: mm-client.c mm-client.h

MyAwesomeBot.o: MyAwesomeBot.cpp mm-client.h
MyAwesomeBot: mm-client.o MyAwesomeBot.o
	${CC} ${CFLAGS} -o $@ $^

clean:
	rm -f *.o

fresh: clean all

