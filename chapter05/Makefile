CXX=g++
CXXFLAGS=-O0 -Wall -g -std=gnu++11 -msse4.2
LDLIBS=
all: chapter05_ex01 
objects = chapter05_ex01.o
BIN = chapter05_ex01

chapter05_ex01: $(objects)
	$(CXX) $(CXXFLAGS) $^ -o $@

clean:
	$(RM) $(objects)  $(BIN)
