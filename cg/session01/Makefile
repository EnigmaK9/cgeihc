IDIR = include
CC = gcc
CFLAGS = -Iinclude -Iinclude/GL -I$(IDIR) -Wall

LDIR = lib
LIBS = -lglut32 -lglu32 -lopengl32

tetera: main.o
	$(CC) -o tetera main.o -L$(LDIR) $(LIBS)

main.o: main.cpp $(IDIR)/Main.h
	$(CC) -c -o main.o main.cpp $(CFLAGS)

.PHONY: clean

clean:
	rm -f *.o tetera
