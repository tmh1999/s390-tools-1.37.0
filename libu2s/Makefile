include ../common.mak

ALL_CPPFLAGS += -I../include

lib = libu2s.a

all: $(lib)

objects = u2s.o misc.o

$(lib): $(objects)

install: all

clean:
	rm -f *.o $(lib)
