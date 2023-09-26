C = gcc
CPP  = clang++

SRC_C = foo.c 
OBJ_C = foo.o  

SRC_CPP  = 1.1.cpp 

TARGET = 1.1
STD = -std=c++2a


all:
	$(C) -c $(SRC_C)
	$(CPP) $(SRC_CPP) $(OBJ_C) $(STD) -o $(TARGET)

clean:
	rm -rf *.o $(TARGET)