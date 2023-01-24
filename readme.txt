Pipex is a program that is expected to take a file as input for a 1st command and direct the output of that first command as input to a 2nd command
and then finally redirect its output to another file.


Program name = pipex

Turn in files = Makefile, *.h, *.c

Makefile = NAME, all, clean, fclean, re

Arguments = file1 cmd1 cmd2 file2

External functs.
open
close
read
write,
malloc
free

perror 
void perror(const char *s);
The perror() function produces a message on standard error
describing the last error encountered during a call to a system
or library function.

strerror
char *strerror(int errnum);
The strerror() function returns a pointer to a string that describes
the error code passed in the argument errnum, possibly using the LC_MESSAGES 
part of the current locale to select the appropriate language. 
(For example, if errnum is EINVAL, the returned description will "Invalid argument".) 
This string must not be modified by the application, but may be modified by a subsequent call to strerror(). 
No library function, including perror(3), will modify this string.

access
int access(const char *pathname, int mode);
access() checks whether the calling process can access the file
pathname.  If pathname is a symbolic link, it is dereferenced.

dup

dup2

execve

exit

fork

pipe,

unlink

wait

waitpid

• ft_printf and any equivalent
YOU coded

Libft authorized Yes