# Fix My Code Challenge

Minimal fixes to the original Holberton School challenge files.

## Tasks

- 0: Check divisibility by both 3 and 5 before checking 3 alone.
- 1: Parse the square size in base 10 instead of base 16.
- 2: Insert at the current position rather than the preceding position.
- 3: Store the hash in the private password attribute and compare using consistent lowercase hashes.
- 4: Reconnect both neighboring nodes before freeing a deleted node; reject invalid indices and null heads safely.

## Run

```sh
cd challenge
python3 0-fizzbuzz.py 50
node 1-print_square.js 10
ruby 2-sort.rb 3 2 1
python3 3-user.py
cd 4-delete_dnodeint
gcc -Wall -Wextra -Werror -pedantic *.c -o list_test
./list_test
```

Original source: https://github.com/holbertonschool/0x00-Fix_My_Code_Challenge

The original structure and implementation are preserved. All source files end with a newline.
