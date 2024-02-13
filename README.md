# microc
A compiler to implement a subset of C language features. Thus dubbed "Micro C".


### Roadmap

[ ] Integer arithmetic lexing / parsing 
[ ] Boolean algebra lexing / parsing
[ ] Basic types
[ ] Variables
[ ] Scope
[ ] Function declarations
[ ] "int main" entry point
[ ] First codegen with cranelift
[ ] Temp Buildin of printf function
[ ] If control flow
[ ] While loops
[ ] For loops
[ ] Arrays 
[ ] Pointers & buildin of malloc and free functions
[ ] Structs
[ ] Function pointers


#### Why?
I am doing this project to study program compilation. I want to write a fully fledged C compiler and this is a good precursor to that. 

The phases I hope for this compiler to have are as follows.
1. Lexical analysis (Reading literals, keywords, operators, etc)
2. Parsing (Reading the logical structure of the code)
3. Binding (Type checking and the like)
4. Codegen (Creating the IR, linking the object files, creating a binary)
