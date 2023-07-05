## Examples

### Example 1
**Input File:**

ildc 10\
ildc 20\
iadd

**Output:**

30


### Example 2
**Input File:**

ildc 20\
ildc 5\
here: ildc 1\
isub\
dup\
jz there\
swap\
ildc 10\
iadd\
swap\
jmp here\
there:\
pop

**Output:**

60