FILES = \
	Contact.cpp \
	PhoneBook.cpp \
	main.cpp

OBJ = $(FILES:.cpp=.o)

CFLAGS = -Wall -Wextra -Werror -std=c++98 -I.

NAME = dead_book

all: $(NAME)
	c++ $(CFLAGS) $(OBJ) -o $(NAME)

$(NAME): $(OBJ)
	c++ $(OBJ) -o $(NAME)

clean:
	rm -f $(OBJ)

fclean: clean
	rm -f $(NAME)

re: fclean all
