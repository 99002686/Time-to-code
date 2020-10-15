SRC = unity/unity.c\
src/prime.c\
test/test_prime.c\
main.c

INC = -Iunity\
-Iinc\
-Itest

PROJECT_NAME = PRIME.out

$(PROJECT_NAME): $(SRC)
	gcc $(SRC) $(INC) -o TEST_$(PROJECT_NAME)

run:$(PROJECT_NAME)
	./TEST_${PROJECT_NAME}
doc:
	make -C documentation

clean:
	rm -rf $(PROJECT_NAME) documentation/html
