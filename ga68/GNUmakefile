PROGRAMS=hello printargv

all: build $(foreach p,$(PROGRAMS),build/$(p))

build:
	mkdir build

build/% : %.a68
	ga68 -o $@ $<
