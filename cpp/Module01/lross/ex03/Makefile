CFLAGS	=	-Wall -Wextra -Werror
OUT		=	weapon
CC		=	c++ -std=c++98
SRC		=	main.cpp \
			Weapon.cpp \
			HumanA.cpp \
			HumanB.cpp
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
