main: main.o display.o
	g++  -o main main.o display.o -lGL -lglut -lGLU -lSDL2 -lGLEW
display.o: ../project/display.cpp ../project/display.h
	g++ -c ../project/display.cpp ../project/display.h
main.o: ../project/main.cpp ../project/display.h
	g++ -c ../project/main.cpp ../project/display.h
clean:
	$(RM) count *.o *~
