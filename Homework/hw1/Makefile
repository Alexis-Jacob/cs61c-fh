CC	=	gcc
CFLAGS	=	-Wall -pedantic -ansi -std=c99 -O3
EXEC	=	Life1D
SRC	=	Life1D.c
OBJ	=	$(SRC:.c=.o)

$(EXEC):$(OBJ)
	$(CC) $(CFLAGS) $(OBJ) -o $(EXEC)

all	:$(EXEC)

clean	:
	rm -rf *.o *~ "#"*"#" $(EXEC)
