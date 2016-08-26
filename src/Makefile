all: app0
	@echo build complete

clean:
	-rm airkiss

app0:airkiss.c
	$(CC) airkiss.c -o airkiss -O0 -g3 -I"./include" -L"./lib" -lairkiss_log -lpthread -ldl -lstdc++ -lm -lrt
