CC = $(CROSS_COMPILE)gcc

susan: susan.c Makefile
	$(CC) -static -O4 -o susan susan.c -lm 

clean:
	rm -rf susan output*
