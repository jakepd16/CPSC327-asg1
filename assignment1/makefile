#Makefile for Assignment 1 gnu toolchain usage
#make, clean and executables

#target exe
myexe : main.o myfunc.o
	g++ $(CFLAGS) -o myexe main.o myfunc.o
	
main.o: main.cpp myfunc.h
	g++ $(CFLAGS) -c main.cpp
	
myfunc.o: myfunc.cpp myfunc.h
	g++ $(CFLAGS) -c myfunc.cpp
	
clean:
	rm -f *.o myexe
	rm -f *.o myfunc.h.gch
