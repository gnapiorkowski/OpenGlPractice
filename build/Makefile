main: main.o display.o shader.o
	g++ -lGL -lglut -lGLU -lSDL2 -lGLEW -o main main.o display.o shader.o
display.o: ../project/display.cpp ../project/display.h
	g++ -c ../project/display.cpp ../project/display.h
shader.o: ../project/shader.cpp ../project/shader.h
	g++ -c ../project/shader.cpp ../project/shader.h
main.o: ../project/main.cpp ../project/display.h
	g++ -c ../project/main.cpp ../project/display.h
clean:
	$(RM) count *.o *~
