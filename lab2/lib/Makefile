INCLUDES := -I../include
%.o: %.c
	$(CC) $(CFLAGS) $(INCLUDES) -c $<
%.o: %.S
	$(CC) $(CFLAGS) $(INCLUDES) -c $<

.PHONY: clean
all: print.o printf.o pmap.o asm.o
clean:
	rm -rf *~ *.o

include ../include.mk
