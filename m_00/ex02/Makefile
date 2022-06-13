FILES = \
	Account.cpp \
	tests.cpp

OBJ = $(FILES:.cpp=.o)

CFLAGS = -Wall -Wextra -Werror -std=c++98 -I.

NAME = bank

all: $(NAME)
	c++ $(CFLAGS) $(OBJ) -o $(NAME)

$(NAME): $(OBJ)
	c++ $(OBJ) -o $(NAME)

clean:
	rm -f $(OBJ)

fclean: clean
	rm -f $(NAME)

re: fclean all
