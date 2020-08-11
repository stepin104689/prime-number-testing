SRC = unity/unity.c\
src/prime.c\
test/test_prime.c\
main.c


PROJECT_NAME = PRIME.out

$(PROJECT_NAME): $(SRC)
	gcc $(SRC) -o $(PROJECT_NAME)

run:$(PROJECT_NAME)
	./${PROJECT_NAME}
doc:
	make -C documentation

clean:
	rm -rf $(PROJECT_NAME) documentation/html
