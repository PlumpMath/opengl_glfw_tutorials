CC = g++ -std=c++0x

INCLUDE = -I/usr/include/libdrm -I/usr/local/include

LIBS = -Wall -lglfw3 -lm -lGLEW -lGL -lGLU -ldl -lXinerama -lXrandr -lXi -lXcursor -lX11 -lXxf86vm -lpthread

# enter filename without extension
FILENAME = main

all: $(FILENAME).cpp
	@$(CC) -g $(INCLUDE) $(FILENAME).cpp -o $(FILENAME) $(LIBS)

run:
	@./$(FILENAME)

clean:
	rm ./$(FILENAME)
