It is static language( variable type is stetted) an enhancement of the C language to add Object-oriented paradigm. it is platform dependent in that the compiler generates a code(.exe) that work for the specific machine or OS but it is not dependent at the source level but at the binary level(.exe) file so the code can work but we need to compile it by a specific platform for the OS and arc specific 

It is middle level language as it combines feature of both high-level( OOP, exception handling) and low-level(direct memory manipulation, system level) making it middle-level 
*Advantage:
- Simple- can be broken into logical parts
- Low level access- provides resources for the system 
- Fast Execution Speed
- Object Oriented-helps make C++ maintainable and extensible programs*
Identifiers are the unique names assigned to variables 
[[Rules of Identifiers]] (naming)
Example:   `int val = 10 `
	     `void func(){ } `
And whenever you discover a keyword  ----> [[Keywords]]
Dynamic memory allocation - inside a function the variables are allocated in the stack space. this means the size of memory is determined at runtime [[Memory Layout Of C++]] 
whenever a variable is assigned in C++ the compiler allocates a memory based on it's data type [[Classification of data types]] 
C++ is both procedural and object oriented programming, while C supports only procedural programming
[[Operators]]

In C++ input and output are sequence or bytes or commonly known as **streams**
**Input stream** : if the direction of flow of the bytes is from the device(for example: keyboard) to the memory then it's called a input 
**Output stream** : if the direction of flow of bites is opposite from main memory to device
all this streams are knowns as `iosstream`
there are two ways of accepting input ```getline()``` and `cin`
`cin` reads automatically and convert the input to the type of n and it stops at first encounter of space 
`getline()` this is more like python input() it reads entire line including spaces
`cerr` is in the stdrr it is output like `cout` but it is unbuffered(no waiting room doesn't store in file) while in `cout` it is buffered(stored and doesn't execute if problem) clog is buffered used to output errors 
the preproccessor operator in C++ is # which is used to declare a variable or handle before actual compilation 
*Note* : all local variables contain garbage unless you explicitly initialize them 
[[Decision making]] 
We can use [[loops]] to iterate over something
we use [[Functions ]] to perform a specific task it helps to break a specific task into smaller maintainable code 