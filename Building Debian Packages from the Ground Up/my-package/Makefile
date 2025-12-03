PREFIX=/usr

build: welcome

welcome: welcome.c
	gcc -o welcome welcome.c

install:
	mkdir -p $(DESTDIR)$(PREFIX)/bin
	install welcome $(DESTDIR)$(PREFIX)/bin/

