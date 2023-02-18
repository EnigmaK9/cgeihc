CXX=g++
CXXFLAGS=-Iinclude -Wall -Wextra -pedantic -std=c++11
LDFLAGS=-lglfw -lGLEW -lGL

SRC=$(wildcard *.cpp)
OBJ=$(SRC:.cpp=.o)

main: $(OBJ)
	$(CXX) $(CXXFLAGS) $(OBJ) -o main $(LDFLAGS)

.PHONY: clean

clean:
	rm -f $(OBJ) main

