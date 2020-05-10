CC=cl
CFLAGS=-c -Wall

all: magic

magic: DBL.obj Queue.obj Pyataya_LR.obj
    $(CC) DBL.obj Queue.obj Pyataya_LR.obj -o magic

DBL.o: DBL.cpp
    $(CC) $(CFLAGS) DBL.cpp

Queue.o: Queue.cpp
    $(CC) $(CFLAGS) Queue.cpp

Pyataya_LR.o: Pyataya_LR.cpp
    $(CC) $(CFLAGS) Pyataya_LR.cpp