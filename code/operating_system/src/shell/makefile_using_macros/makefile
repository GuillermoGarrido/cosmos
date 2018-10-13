OBJS = a.o b.o c.o
CC = g++
DEBUG = -g
CFLAGS = -Wall -c $(DEBUG)
LFLAGS = -Wall $(DEBUG)

p1 : $(OBJS)
	$(CC) $(LFLAGS) $(OBJS) -o p1

a.o : a.h a.cpp c.h
	$(CC) $(CFLAGS) a.cpp

b.o : b.h b.cpp c.h
	$(CC) $(CFLAGS) b.cpp

c.o : c.h c.cpp
	$(CC) $(CFLAGS) c.pp

clean:
	\rm  *.o *~  p1
tar:
	tar cfv p1.tar b.h b.cpp c.h c.cpp 
