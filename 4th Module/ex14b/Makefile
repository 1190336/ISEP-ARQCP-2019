ex14: join_bits.o main.o
	gcc -g -Wall join_bits.o main.o -o ex14
	
join_bits.o: join_bits.s
	gcc -g -Wall -c join_bits.s -o join_bits.o

main.o: main.c
	gcc -g -Wall -c main.c -o main.o

clean:
	rm -f *.o ex14

run: ex14
	./ex14
