
Pipes are used because of the UNIX philosophy that programs only do one thing, and they do it very well.


### Input / Output Redirection (Piping)

![[Pasted image 20251007141413.png]]

Bash by default has 3 file descriptors for each process
- STDIN - keyboard input
- STOUT - the default output to the screen
- STERR - another output to the screen, specifically for errors

Programs can output to other programs
`program_1 | program_2`
- `program_1`'s output becomes `program_2`'s input
`program_1 > file.txt`
- `program_1`'s output is written to the file `file.txt`
`program_1 < input.txt`
- `program_1` gets it's input from a file called `input.txt`

### Filters
A filter is a type of program that takes an input and provides and output, manipulating the input to create that output.
Filters can be connected together using pipes
Filters are like building blocks that can be put together to perform a task.

#### For Example:
```bash
cat student_attendance.txt | grep August | sort
```
output the contents of the file -> only show August | sort in reverse order of attendance

### Example filters
`head`
- view the first 10 lines of a file
`tail`
- view the last 10 lines of a file
`sort`
- organise the data into order
`wc`
- print number of lines, words, and characters
`uniq`
- remove duplicate lines
`tr`
- simple text transformations

