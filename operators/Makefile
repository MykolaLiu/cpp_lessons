CC=g++
CFLAGS=-c -Wall
LDFLAGS=
SOURCES=main.cpp complex.cpp
OBJECTS=$(SOURCES:.cpp=.o)
EXECUTABLE=executable.exe

all: $(SOURCES) $(EXECUTABLE)

$(EXECUTABLE): $(OBJECTS)
	$(CC) $(LDFLAGS) $(OBJECTS) -o $@
.cpp.o:
	$(CC) $(CFLAGS) $< -o $@
