java c
Advanced Algorithms and Data Structures (COMP4133 UNNC): CourseworkFor this coursework, you are tasked with implementing the AVL tree algorithm. Your starting point will bean array of integers, which you will use to construct the AVL tree. Following the construction of the tree, you should output its elements in post-order traversal approach.
The necessary files for this assignment are available for download from Moodle. These include:
•    `Input.txt`: An example file that you will read as input.
•    `Output.txt`: A sample output file that corresponds to the `Input.txt` input.
Your Java code should fulfill the following requirements:
1.    Read the content of `Input.txt`.
2.    Implement the AVL tree algorithm.
3.    Print the constructed tree using post-order traversal, with each node printed on a new line.
For instance, given the content of 'Input.txt'provided:
9,6,2,1,4,25,16,13,37,27,17,34,10
The expected 'Output'should look like this:
1
4
2
9
13
10
6
17
25
34
37
27
16
Grading Criteria
Criteria
Full mark
Comment
Is the output correct?
40%
The correct answer will receive full marks. Marks are subject to reduction for the following reasons: partially correct answers with minor mistakes, or correct output accompanied by other issues.
How is the time complexity of the program?
20%
For those who provide the correct answer, their runtime will be recorded. Those whose runtime falls into the first quantile will receive full marks. Those in the second quantile will receive 15% of the total marks, the third quantile 10%, and the last quantile 5%.
Is the program well formatted (following Java naming conventions, high readablity, appropriate error handling, etc.)
10%

Does the program contain appropriate comments?
10%

Is the program adhere to Object-Oriented Programming paradigm (Encapsulation, Abstraction, Inheritance, Plymorphism, Modularity, Association and Composition, Message Passing, Overload and Overriding)?
20%

Definitions
Standard input
System.in, means that the stream from which input to the program is taken. Typically this is the keyboard, but it can be specified that input is to come from a serial port or a disk file.
Standard output
System.out, means that the stream to which output from the program is sent. Typically this is a display, but it can be redirected to a serial port or a file.
SubmissionYou must submit a single Java source code file containing all your code for this coursework. This file must be called AVL.java and must not require any other files outside of the standard Java packages  which are always available. The file must compile and execute without warnings or errors using the command.
Compile: javac -encoding UTF-8 -sourcepath . AVL.java
Execute: java -Dfile.encoding=UTF-8 -XX:+UseSerialGC -Xss64m -Xms1920m -Xmx1920m AVL < Input.txt > Output.txt
Your program SHOULD send its output to standard output (by executing above command, it will produce Output.txt in the same directory as AVL.java and Input.txt, so no FileWriter is required).
Technical Notes
This part contains important technical information and it is important that you read and understan代 写Advanced Algorithms and Data Structures (COMP4133 UNNC): CourseworkJava
代做程序编程语言d all the information below.
You program MAY have multiple classes if you wish, but only in one java file. And only the class with your main method SHOULD be marked as public.
Your program MUST read its input from standard input.
If your program exits with a non-zero exit code, it will be judged as a run-error.
Program submitted will be run inside a sandbox. The sandbox will allocate 2GB of memory for your   program. Your entire program, including its runtime environment, must execute within this memory limit. For Java, the runtime environment includes the interpreter (JVM).
We suggest that you do not use package statements (that is, we suggest that your solution reside in the “default package”).
Please use JDK versions latter than 7.
Possible results
A submission can have the following results:
CORRECT The submission passed all tests: you solved this problem! 0% will be given to errors listed below:
COMPILER-ERROR There was an error when compiling your program. Note that when compilation takes more than 30 seconds, it is aborted and this counts as a compilation error.
TIMELIMIT Your program took longer than the maximum allowed time for this problem, 5 seconds. Therefore it has been aborted. This might indicate that your program hangs in a loop or that your solution is not efficient enough.
RUN-ERROR There was an error during the execution of your program. This can have a lot of different causes like division by zero, incorrectly addressing memory (e.g., by indexing arrays out of bounds),
trying to use more memory than the limit, reading or writing to files, etc. Also check that your program exits with exit code 0!
NO-OUTPUT Your program did not generate any output. Check that you write to standard out.
OUTPUT-LIMIT Your program generated more output than the allowed limit. The solution is considered incorrect.
WRONG-ANSWER The output of your program was incorrect. This can happen simply because your
solution is not correct, but remember that your output must comply exactly with the specifications of
the judges. See testing below for more details. The judges may have prepared multiple test files for each problem.
Pre-Submission Checklist
Before submitting your code, you **MAY** do the following checks to help you pass the automated judging system:
o The file name and the main class shares the same case-sensitive names (``PLogic`` and ``IdSum``).
o No usage of ``package`` statement.
o No usage of third-party packages that are not included in the JDK (import packages only begin with ``java.``).
o Only the main class is marked as ``public``.
o Using a single scanner/reader for inputs (``System.in`` appears no more than once).
o No code that produces unnecessary empty lines (i.e., ``System.out.println("");``).
o Compiling and running your latest code on CSLinux.
During your manually testing on your code, ensure the following that helps you handle all ````, ``\n``, ``\r\n``, ````, ```` issues:
o No empty lines in visual:
Pressing ``ENTER`` exactly once at the last line of input then the output is shown.
The output is exactly the next line to the last line of input.




         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
