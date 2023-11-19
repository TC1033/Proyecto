all: clean compile run

compile: exercise.cpp
	g++ *.cpp -o build/exercise
run: 
	clear
	build/exercise
clean:
	rm -f build/exercise
	rm -f build/dexercise
debug: 
	g++ *.cpp -g -o dexercise
	gdb dexercise
	rm -f dexercise
debugvs:
	g++ *.cpp -g -o build/dexercise
