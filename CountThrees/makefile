# Makefile for CountThrees 
# CCSF CS 178
# Roman Borisov
# 2015-09-19
	
objects = countThrees.o readInt32BitLE.o

countThrees : $(objects)
	cc -o countThrees countThrees.o readInt32BitLE.o

countThrees.o : countThrees.c readInt32BitLE.h
	cc -c countThrees.c
readInt32BitLE.o : readInt32BitLE.c readInt32BitLE.h
	cc -c readInt32BitLE.c
	
test :
	./countThrees
	

clean :
	rm $(objects)
