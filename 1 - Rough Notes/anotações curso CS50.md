- Unorgonised Information -

Unary - base-1 [
    counting with human hand]
Binary - base-2 [
    basicamente usa bases de 2 {1,2,4,8,16,32...} para contar, então 111 é igual a 7, porque 1x1 + 1x2 + 1x4 = 7
    quanto mais 'transistores', maior a contagem, então 1000 é igual a 8, porque 1x8 = 8]
Binary digit - bit [
    0 or 1] → Transistors like light bulbs {Off for 0 | On for 1}
Decimal - base-10 [
    10 possibilities → 0 through 9]
Byte - 8 bits
ASCII (American Standard Code for Information Interchange) [
    A in ASCII is 01000001 (1 byte, or 8 bits), or 65 in decimal, because 1x64 + 1x1 = 65]
Unicode [
    Unicode can be U+2665 for a heart, for example]
RGB (Red, Green, Blue) [
    to represent Red, Green and Blue, it takes 1 byte
    a pixel has generally 3 bytes (RGB), the system telling what color to use]
Algorithm [
    the source that converts inputs to outputs
    a precise description of how to do something, step-by-step instructions for solving a problem]
Code [
    functions [
        (arguments, return values, variables) - action or verb]
    conditionals [
        - decide which way to go based on a question]
    boolean expresions [
        - a question with a yes or no answer (true or false)]
    indentation [
        - tells wether to do something yes or not]
    loops [
        - tells to repeatedly execute a block of code a certain number of times or when a condition is satisfied]

    low-level coding [
        - the nitty-gritty part, closer to the machine code (which consists of 0's and 1's)]
    high-level coding [
        - the abstract part, simplifying concepts and hiding hardware details with easy commands]

    side-effect [
        - when a function does something that affects the program's state outside itself (like when you write on a notebook, changing the notes, or in this case  the variables)]
    return value [
        - it's the output that gets handed back when a function ends executing it (like adding 5 to a value), it can be stored in a variable for later use]]
Artificial Intelligence (AI) [
    uses LLM's (large language models) with neural networks, which are provided a lot of data (inputs)
    have a final neuron to give what the answer should be]

+

Machine Code [
    the 0's and 1's instructions the machine reads and interpret]
Source Code [
    the human-readable instructions that are written by humans in a certain programming language]
Compiler [
    translates source code to machine code]
Graphical User Interface (GUI) [
    the buttons, icons, menus etc. in an application]
Command-line Interface (CLI) [
    the line where you type the commands in a terminal emulator, there are no graphical details, just text instead]
Header File [
    are files that declare what functions, arguments etc. exist in a programming language (libraries use them to connect with the code)]
Libraries [
    collections of code that someone else wrote, including the definitions of the functions, you can access them by including header files]
More Code [
    escape sequences (\) [
        \r - goes to the beginning of the line
        \" - makes double quote
        \' - makes single quotes
        \\ - makes backslashes]

    bool [
        - true or false question]
    char [
        - single characters]
    double and float [
        - real numbers (with decimal numbers or not)]
    long [
        - long integers]
    
    format codes [
        - basically placeholders

        %s - puts the following string
        %i - for integers]
    logical operators [
        || - or
        && - and]
    
    strings [
        - basically text, sequences of characters]
    conditionals [
        - decide which way to go based on a question

        if
        else
        else if - else and then if conditional]
    operators [
        = - assign a return value from the right side to the left side
        < - less than
        <= - less than or equal
        > - greater than
        >= - greater than or equal
        == - equal
        != - different]
    variables [
        - used to store data, can be created and assigned a value
        - when declaring variables, define their type → int numero = 4]
    constants [
        turns a variable into a constant, so the compiler doesn't let the value to be changed anymore]
    comments [
        // - used to make notes inside the code]

    return (value) [
        - used to when you want a function to hand back a value to wherever is calling it
        - ends the function at that point]]
" and ' Difference [
    - use " for strings
    - use ' for chars]
Loop types [
    while () - while the bool inside the while remains true, it'll execute again until the condition is met
    for () - it functions the same way as while, but tidier

    it works like this: for (variable to create and initialise; boolean expresion to check again; something to happen)
    an example: for (int i = 0; i < 10; i++)]
How to create functions? [
    - you can use void function_name(void), and it's better to declare it in the first lines of the code
    - void means 'no return value', if a function is void null(void), it takes no input, and returns nothing
    - void function_name(void) in the first lines is a prototype, it's a clue that the function will eventually exist

    - when using the function, you can just use function_name(), not putting void inside it]
Scopes [
    - variables declared inside a scope (basically inside the brackets) won't work the same way outside it
    - that's why a variables with the same name might work differently while coding]
Integer Overflow [
    - since C only handles 32-bits integers, if an int tries to carry a 33th bit, it'll mess up the other 32 bits turning them from 1's to 0's
    - causes the int to turn into 0]
Truncation [
    - an integer divided by an integer, always returns another integer
    - 3 / 2 = 1]

    How to avoid truncation? (Casting) [
        - before a variable, you can put (type) and tell the compiler to treat it as the requested
        - (float) x / y]

- Scratch -

What is Computer Science?
-The study of information, how you represent and process it
-Problem solving

Game Ideas for Scratch:

Making a simple quiz game (like Show do Milhão) ✅

- C - 

Some project ideas:

-Calculator ✅
-Text-based RPG game
-Blackjack game (i don't know if it's possible)

Some tasks to do:
-review the basics
-write a simple code that returns N times a word, and write another that works like a settings program
-do problem set 1