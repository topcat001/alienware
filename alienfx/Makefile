CC=gcc
CFLAGS=-Wall
LIBS=-lusb-1.0

%o: %c
	$(CC) -c -o $@ $< $(CFLAGS)

alienfx: alienfx.o
	$(CC) -o $@ $^ $(CFLAGS) $(LIBS)

clean:
	rm -f alienfx alienfx.o
