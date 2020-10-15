SOURCE = unity/unity.c \
src/memory_allocation.c \
src/substring.c \
test/test_substring.c \
main.c 

INCLUDE = -Iunity \
-Iinclude \
-Itest

PROJECT_NAME = SUBSTRING.out

$(PROJECT_NAME): $(SRC)
	gcc $(SOURCE) $(INCLUDE) -o TEST_$(PROJECT_NAME)

run:$(PROJECT_NAME)
	./TEST_$(PROJECT_NAME)

doc: 
	make -C documentation

