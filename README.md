# get_next_line


Creation of one or multiple file(s) reader in C. The bonus allows you to read from multiple fds.


## Installation


```bash
git clone https://github.com/trimize/42-get_next_line.git && cd 42-get_next_line
```

## Usage

Include get_next_line's files in your C project and use it as shown below:

```c
char  *str;

str = get_next_line(your_fd);
```


Compiling your file:


For one file:

```bash
cc -Wall -Wextra -Werror your_file.c get_next_line.c get_next_line.h get_next_line_utils.c
```
For multiple files:

```bash
cc -Wall -Wextra -Werror your_file.c get_next_line_bonus.c get_next_line_bonus.h get_next_line_utils_bonus.c
```
