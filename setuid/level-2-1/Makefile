TARGET = setuid-backdoor-level2.1
CC     = gcc
CFLAGS = -Wall -Wextra -Werror
INCLUDE = -I ../../include ../../include/util.c

.PHONY: all clean

all: $(TARGET)

%: %.c
	$(CC) $(CFLAGS) $(SECFLAGS) $(INCLUDE) -o $@ $<

clean: 
	rm -rf $(TARGET)
