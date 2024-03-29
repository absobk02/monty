#### Description
We built and monty files (.m) interpreter with C programming language. Monty 0.98 is a scripting language that is first compiled into Monty byte codes. It relies on a unique stack, with specific instructions to manipulate it. We implement some op_codes like add, pop and print elements from the stack/queue.

**Monty byte code files**

Files containing Monty byte codes usually have the .m extension. Most of the industry uses this standard but it is not required by the specification of the language. There is not more than one instruction per line. There can be any number of spaces before or after the opcode and its argument:

#### Valid op_codes
- [X] **push**: pushes an element to the stack
- [X] **pall**: prints all the values on the stack
- [X] **pint**: prints the value at the top of the stack
- [X] **pop**:  removes the top element of the stack
- [X] **swap**: swaps the top two elements of the stack
- [X] **add**: adds the top two elements of the stack
- [X] **nop**: doesn’t do anything
- [X] **sub**: subtracts the top element of the stack from the second top element of the stack
- [X] **div**: divides the second top element of the stack by the top element of the stack
- [X] **mul**: multiplies the second top element of the stack with the top element of the stack
- [X] **mod**: computes the rest of the division of the second top element of the stack by the top element of the stack
- [X] **\#:** Every good language comes with the capability of commenting.
- [X] **pchar**: prints the char at the top of the stack
- [X] **pstr**: prints the string starting at the top of the stack
- [X] **rotl**: rotates the stack to the top
- [X] **rotr**: rotates the stack to the bottom
- [X] **stack**: sets the format of the data to a stack (LIFO). This is the default behavior of the program
- [X] **queue**: sets the format of the data to a queue (FIFO)
