EXES=first

all: $(EXES)

%: %.o
	gcc -o $@ $^

% : %.s

%.o : %.s
	as -o $@ $<

.PHONY: clean
clean: 
	rm $(EXES)

