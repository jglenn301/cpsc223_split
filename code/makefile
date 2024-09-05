CC = gcc
CFLAGS = -std=c17 -pedantic -Wall -g

SplitAudio: split.o output.c
	${CC} ${CFLAGS} -o $@ $^

split.o: split.c output.h
output.o: output.c output.h
