FILES = \
	megaphone.cpp

OBJ = $(FILES:.cpp=.o)

CFLAGS = -Wall -Wextra -Werror -std=c++98

NAME = megaphone

all: $(NAME)
	c++ $(CFLAGS) $(FILES) -o $(NAME)

$(NAME): $(OBJ)
	c++ $(OBJ) -o $(NAME)

clean:
	rm -f $(OBJ)

fclean: clean
	rm -f $(NAME)

re: fclean all
