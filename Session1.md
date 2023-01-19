# Summary of Session 1: Jargon!
 * __bit__ = "binary digit" = a 0 or 1
   * the smallest unit of data that a computer can process/store
 * __byte__ = 8 bits = 1 character (on a US keyboard)
   * megabyte (MB) = 1 Million bytes (technically it's 2^20 = 1,048,576 bytes
   * gigabyte (GB) = 1 Billion bytes (2^30 = 1,073,741,824 bytes)
   * terabyte (TB) = 1 Trillion bytes (2^40 = 1,099,511,627,776 bytes)
 * __CPU__ = Central Processing Unit = "brain" of a computer
   * it's a _super_ fast, _super_ dumb brain
   * it can do billions of operations per second
   * ...but each operation is pretty simple
     * moving data from memory into the CPU
     * storing data in the CPU into memory
     * integer arithmetic (e.g., 2 + 3)
     * floating point arithmetic (e.g., 2.3 * -5.1)
     * branching ("jump" to a different place in the code)
  * __RAM__ = Random Access Memory (or just "memory")
    * space the computer can work with while it's turned on (e.g., applications live in RAM when they are running)
    * 16 GB RAM = 16 Billion bytes or characters worth of "work space"
  
## What is an executable/program/application (e.g., Google Chrome)?
* a series of _instructions_ in a language that the CPU understands
   * that language is called "assembly language" or "machine language"

* applications (runnable code) are stored on your hard drive, just like any other file
* when you double click (or otherwise launch an application)
  * the OS (Windows, Mac, Linux) loads the application into memory (RAM)
  * the CPU begins running it
    * that is, the CPU decodes each instruction and does what it is told
    * instructions are of two types
      * _load/store_ = move memory to/from the CPU
      * _operational_ = arithmetic or other operations on the data in the CPU

## What is Computer Programming (Coding)?
* a process that begins with the formulation of a (computing) problem and ends with the creation of an runnable computer program
* a _program_ is a set of statements or instructions that tells the computer what to do
* in order to write a program, programmers often begin with an algorithm
  * an _algorithm_ is a set of rules to be followed to solve a problem (usually, but not always by a computer)
    * e.g., an algorithm for converting Fahrenheit temperatures into Celsius:
       * subtract 32 from the Fahrenheit temperature
       * multiply the result by 5/9
* _pseudocode_ is a notation resembling a simplified programming language
  * it's often a mixture of English and real programming language constructs
  * we will always write pseudocode _BEFORE_ writing any code
  * you will want to jump right in and code w/o writing pseudocode...just don't
    * otherwise you will end up with a non-working program with no understanding of how you got there!
  * _every_ line of code you write as a _purpose_ and you should be able to relate that purpose back to the pseudocode or steps that you previously wrote down
