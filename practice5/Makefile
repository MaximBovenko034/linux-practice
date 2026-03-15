CC=gcc
CFLAGS=-Wall -O2
all: app
app: main.o
	$(CC) main.o -o app
main.o: main.c
	$(CC) $(CFLAGS) -c main.c
clean:
	rm -f *.o app
