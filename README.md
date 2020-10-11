# Background
This is the first BASH script I ever wrote, done for my OS couse. It's purpose is to perform simple matrix operations on a tab delimited file.
For example, a possible input file containing the string `1\t2\n3\t4`, where `\t` represents a tab and `\n` represents a newline,
would correspond to the matrix:  
1   2  
3   4

# Usage #
1. get matrix dimensions: `./matrix dims <input file>`
2. transpose a matrix: `./matrix transpose <input file>`
3. Get the mean of each column of a matrix: `./matrix mean <input file>`
4. Add two matrices: `./matrix add <input file left> <input file right>`
5. Multiply two matrices: `./matrix multiply <input file left> <input file right>`

All output can be piped to other files.
