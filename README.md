# 42finder
Little script to find specific patterns in all .c and .h files in a folder

////////////////////////////////////////////////////////

It is designed to work with files that carry the 42 signature header, but

alternatively it is sufficient to put this line at the beginning of every file:

/*  FILE_NAME  */

or, even better:

/*  FILE_PATH  */

e.g. 

/*  src/utils/string_utils.c  */

(at least 1 space after "/*" and 2 spaces after ".c"/".h")

//////////////////////////////////////////////////////////

To use it, just put the executable in the folder and run

./find word PATTERN

Here's an example:

![test 42finder](https://user-images.githubusercontent.com/95633668/200097442-bf27237e-ab9c-4707-bfed-a432dd85251a.png)

Occurrences of the pattern "strlen" can be found in ft_strlen.c, x_X_printf.c, c_s.c and libft.h
