CC = clang++
all: test
test: test.o
	${CC} test.o -o  test
test.o: test.cc
	${CC} -c test.cc
clean:
	rm test.o test
	

