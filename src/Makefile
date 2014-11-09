NAME=EMDR_009i_deutsch

FPC ?= fpc

all:	$(NAME)

$(NAME):	$(NAME).pas
	$(FPC) $@ -o$@

clean:
	@rm -f $(NAME) *.o
