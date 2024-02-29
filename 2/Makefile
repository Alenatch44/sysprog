GCC_FLAGS = -Wextra -Werror -Wall -rdynamic -I ../utils/heap_help/
LD_FLAGS = -ldl -pthread

a.out: parser.c solution.c
	gcc $(GCC_FLAGS) parser.c solution.c ../utils/heap_help/heap_help.c -o a.out $(LD_FLAGS)

.PHONY: clean
clean:
	rm a.out
	rm out.txt
