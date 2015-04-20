CC=gcc
CFLAGS=-I.
DEPS = hellomake.h
OBJ = hellomake.o hellofunc.o

%.o: %.c $(DEPS)
	$(CC) -c -o $@ $< $(CFLAGS)

all: hellomake

hellomake: $(OBJ)
	gcc -o $@ $^ $(CFLAGS)
clean:
	rm *.o hellomake
