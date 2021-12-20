CC     = gcc
CFLAGS = -O2 -Wall -pedantic
LIBS   = -lm -lnsl 

Kripto:Kripto.o
	$(CC) $(CFLAGS) $(LIBS) -o Kripto Kripto.o -lm

Kripto.o:Kripto.c
	$(CC) $(CFLAGS) -c Kripto.c

clean:
	rm -f Kripto *.o
