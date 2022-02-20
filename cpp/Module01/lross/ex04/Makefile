CFLAGS	=	-Wall -Wextra -Werror
OUT		=	replace
CC		=	c++ -std=c++98
SRC		=	main.cpp \
			Replace.cpp
OBJ		=	$(SRC:.cpp=.o)

all: $(OUT)

$(OUT): $(OBJ)
	$(CC) $(CFLAGS) $(OBJ) -o $@

clean:
	rm -fr $(OBJ)

fclean:
	make clean
	rm -fr $(OUT)

re: fclean all
