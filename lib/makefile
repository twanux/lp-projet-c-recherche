%.o: %.c recherche.H
	gcc -c $<

librecherche.a: load.o
	ar -rs $@ $^