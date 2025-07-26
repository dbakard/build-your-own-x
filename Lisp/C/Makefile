CC = cc
CFLAGS = -std=c99 -Wall
LDFLAGS = -ledit -lreadline -lm
SRC = parsing.c mpc.c
OUT = parsing

all: $(OUT)

$(OUT): $(SRC)
	$(CC) $(CFLAGS) $(SRC) -o $(OUT) $(LDFLAGS)

clean:
	rm -f $(OUT)
