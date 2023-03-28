all : cpu mem threads io

cpu : cpu.c common.h
	gcc -o cpu cpu.c -Wall -Wfatal-errors

mem : mem.c
	gcc -o mem mem.c -Wall -Wfatal-errors

threads : threads.c common.h common_threads.h
	gcc -o threads threads.c -Wall -Wfatal-errors -lpthread

clean :
	rm -f cpu mem threads io
