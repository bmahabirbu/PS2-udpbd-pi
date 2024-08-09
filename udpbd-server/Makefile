BIN=udpbd-server
OBJS=main.o

udpbd-server: $(OBJS)
	$(CXX) $(LDFLAGS) -o $@ $(OBJS)

all: $(BIN)

clean:
	rm -f $(BIN) $(OBJS)

install: $(BIN)
	cp $(BIN) $(PS2DEV)/bin
