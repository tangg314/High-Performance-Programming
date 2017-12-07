CFLAGS = 

default: app

run:
	./app 0.18

app: main_v7.cpp
	g++ $(CFLAGS) main_v7.cpp -o app

clean:
	/bin/rm -f */*.o *.o app GHZ_output.txt
