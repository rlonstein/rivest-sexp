sexp: sexp-basic.o sexp-input.o  sexp-output.o sexp-main.o
	$(CC) $(LDFLAGS) $^ $(LOADLIBES) $(LDLIBS) -o $@

.PHONY: clean
clean:
	rm *.o sexp

