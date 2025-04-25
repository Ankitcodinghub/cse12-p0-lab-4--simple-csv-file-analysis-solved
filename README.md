# cse12-p0-lab-4--simple-csv-file-analysis-solved



**<span style='color:red'>TO GET THIS SOLUTION VISIT:</span>** https://www.ankitcodinghub.com/product/cse12-p0-cse12-lab-4-simple-csv-file-analysis-solved/

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;124360&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;5&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (5 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE12 P0 Lab 4- Simple CSV File Analysis Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">
            
<div class="kksr-stars">
    
<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
    
<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>
                

<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (5 votes)    </div>
    </div>
<h4 class="product_title entry-title"><a href="https://www.ankitcodinghub.com/product/cse12-lab-4-simple-csv-file-analysis-spring-2025-solved/"><span style="color: #0000ff;"><strong>CSE12 Lab 4: Simple CSV File Analysis Spring 2025 Solution click here!!</strong></span></a></h4>
Objective

The objective of this lab is to learn about function calling, RISC-V protocols for the use of registers.

This lab takes as input a CSV (comma separated values) file (.csv extension) that is used for generating tabular data in spreadsheets. Specifically, for this assignment, you will NEED to assume this CSV file was generated under Windows (the reason will be explained shortly). Consider the data.csv file below as it appears when you open it in Excel as an example.

Assignment Project Exam HelpFigure 1 data.csv file in Excel

This file shows the stock returns from an investment portfolio over a year. The “A” column contains the stock name

and the “B” column indicates the returns in USD (We will assume that there is no negative stock return in all our

You will run the file lab4_testbench_rev##.asm file in RARS which takes data.csv as an input CSV file. Doing so will yield the following analysis, based on the calculations made by the assembly files that you will be submitting):

2. List the dollar amount of all the input records. (input_from_record.asm)

3. Provide the name of the stock that gives the maximum income. (maxIncome.asm)

4. Provide the name of the stock that gives the minimum income. (minIncome.asm)

5. Calculate the total income generated from all stocks

When you run via RARS lab4_testbench_rev#.asm with the .asm files shown above completed by you, you will get the output console as shown below:

Figure 2 After running the lab4_testbench_rev##.asm file with the Lab4 assignment fully completed

About the Windows CSV file format

To distinguish between each entry/row/record in the spreadsheet format of the CSV file, the following convention is adopted depending on the OS :

Windows – Lines end with a &lt;CR&gt; and a &lt;LF&gt; character

Linux – Lines end with only a &lt;LF&gt; character

Macintosh (Mac OSX) – Lines end with only a &lt;LF&gt; character Macintosh (old) – Lines end with only a &lt;CR&gt; character where &lt;CR&gt; is the carriage return (‘ ’) character and &lt;LF&gt; is the line feed/newline (‘ ’) character.

If you open the provided data.csv file in Notepad++ on Windows with “Show all Characters” enabled, then you should see the following text showing the placement of the carriage return and line feed characters. .

Assignment Project Exam Help

Figure 3 data.csv on Notepad++ on Windows

Another assumption that we will state at this point is that we expect that in each record, the name of the stock is followed by the “,” and then immediately by the stock price expressed as an unsigned integer in base 10. So, with record 2 as an example, we will never have a situation where it is written as “Kramerica, . . 0 ” where the 2 red dots indicate two blank spaces. This assumption makes the CSV file analysis by RARS easier to code.

Resources

Much like how a high-level program has a specific file extension (.c for C, .py for python) RARS based RISC-V programs have an .asm extension.

In the Lab4 folder in the course you will see 9 assembly files. They are meant to be read (and understood) in sequence and they will provide you with lotsof hints as to how to build your program:

1. add_function.asm – This program accepts two integers as user inputs and prints their addition result. The actual addition is done through calling a function, sum. Sum accepts two arguments in the a0, a1 registers and returns a0+a1 in a0 register

2. multiply_function.asm – This program accepts two integers as user inputs and prints their multiplication result. The actual multiplication is done through calling a function, multiply. Multiply accepts two arguments in the a0, a1 registers and returns a0*a1 in a0 register. This function in turn calls the function sum, described previously, to do a particular addition. Thus, multiply function is an example of a nested function call, a function which itself calls another function, sum in our case.

4. lab4_testbench_rev##.asm – This is the main testbench program you will run upon completion of all coding in Lab4 to ensure your Lab4 assignment works as expected. This file is initially provided such that if you run it as it is (with the other .asm files in the same directory), you will still get partially correctly generated output. This testbench will also run the the function allocate_file_record_pointers from the allocate_file_record_pointers.asm which will aide you in writing your program. DO NOT MODIFY THIS FILE.

5. allocate_file_record_pointers.asm – This .asm file contains a function that creates an internal reference table in memory to pointer pairs. These pointer pairs indicate 1) the location of the start of a string corresponding to the stock name and 2) the start of a location containing the stock price for each and every record/entry coming from the data.csv file. This function has been fully written out for you. DO NOT MODIFY THIS FILE.

6. macros_rev#.asm – This file contains useful macros, mostly to do I/O, it uses and modifies a# registers, so be careful. Become familiar with these functions. They are your friends.

6. income_from_record.asm – This. asm file contains a function that you will write to convert the string data from the income of a record/entry in the spreadsheet and convert it into an integer. Example, convert the string “1234” into the actual integer 1234 in base 10.

7. income_from_record_ideas_asm – This file provides some ideas for implementing income_from_record.asm.

7. length_of_file.asmAssignment Proje – This. asm file contains a function that you will writect Exam Help to find the total amount of data bytes in the csv file. Refer to Figure 2 for an example.

9. minIncome.asm – This. asm file contains a function that you will write to determine the name of the stock that has the minimum income in the csv file. (Figure 2 fails to show the corresponding output. It’ll be added later)

10. totalIncome.asm – This. asm file contains a function that Add WeChatyou will write powc to sum up all the stock incomes in theoder csv file. Refer to Figure 2 for an example.

These files have enough comments in the source code to jump start your understanding of RISC-V assembly programming for Lab 4 if the lectures have not yet covered certain topics in assembly programming.

For the usage of macros (which are utilized heavily in this lab to generate ecalls), please also refer to the RARS documentation on macros and ecalls as well.

Please read the provided files carefully. You can learn a lot about assembler from reading these files. Note that using macros resembles calling functions. The macros have been written to make use of the a# registers, so don’t assume that any values in your a# registers remain valid after calling a macro.

Memory arrangement as defined in Lab4

The memory of RISC V is used as per the given requirements.

File Data Buffer

The data.csv file is treated as the default input file. It’s contents are store in the file buffer location 0xffff0000 (referred to as MMIO).

Figure 4 data segment window for MMIO after running completed Lab4 assignment.

The input is achieved when the provided fileRead macro found in lab4_testbench_rev##.asm is executed. Your code does not need to do this.

For reference, from Figure 4, note where the first record in the given data.csv file, “Kruger Industrial Smoothing,365 ” is found. The location of the letter ‘K’(encoded in ASCII as byte 0x4b or 64 in base 10) is at 0xffff0000. The location of the character digit ‘3’, i.e. the start of the income,(encoded in ASCII as byte 0x33 or 51 in base 10) is at 0xffff001c. If you count the bytes in the string “Kruger Industrial Smoothing,365 ” with ‘K’ being the 0th character, then ‘3’is the 28th character (0x1c), so this makes sense.

Assignment Project Exam Help

File Record Pointers

We need a systematic way to reference the memory locations where the stock name and income from the file buffer at

Figure 5 data segment window for heap after running completed Lab4 assignment.

This is achieved when the testbench (lab4_testbench_rev##.asm) runs the provided function

allocate_file_record_pointers with the arguments in a0 and a1 registers being the file size in bytes (119 in our given example from data.csv) and the starting address of file buffer (0x0ffff0000 in our given example from data.csv), respectively. The allocate_file_record_pointers function is provided in the allocate_file_record_pointers.asm file separately through the .include statement in lab4_testbench_rev##.asm.

For reference, from Figure 5, note in our example data.csv the first record’s location of start of income name (0xffff0000) and income value(0xffff001c) are stored as words in consecutive heap memory locations 0x10040000 and 0x10040004 respectively. Likewise, the second record’s (i.e. “Kramerica,0 ”) location of start of income name (0xffff0021) and income value(0xffff002b) are stored as words in consecutive heap memory locations 0x10040008 and 0x1004000c respectively. And so on and so forth. It is left as a HIGHLY recommended exercise that the student verifies this pattern for the remaining records in the CSV file and how they are allocated in the memory locations as shown in Figure 5. As we see in Figure 5, the 10 non zero heap memory locations from 0x10040000 to 0x10040024 indicate there were originally 10/2 = 5 records in our data.csv file. This value (no. of records) is returned in a0.

Student coded functions

All student coded functions are to be written in the .asm files listed in the lab4_testbench_rev##.asm file using the .include statement (excluding allocate_file_record_pointers.asm). The functions written MUST abide by the register saving conventions of RISC-V.

1. length_of_file(a1) – This function is to be written in length_of_file.asm. It accepts as argument in a1 register the buffer address holding file data and returns in a0 the length of the file data in bytes. From our example involving data.csv, length_of_file(0xffff0000)=119

2. income_from_record(a0) – This function is to be written in income_from_record.asm. It accepts as argument in a0 register the pointer to start of numerical income in a record. It returns the income’s numerical value in a0.

From our example involving data.csv, income_from_record(0x10040004)=365. This is the income from the stock of Kruger Industrial Smoothing. income_from_record(0x1004000c)= 0. This is the income from the stock of Kramerica.

3. totalIncome(a0,a1) – This function is to be written in totalIncome.asm. a0 contains the file record pointer array

location (0x10040000 in our example) But your code MUST handle any address value. a1 contains the number of

records in the CSV file. a0 then returns the total income (add up all the record incomes). Assignment Project Exam Help

From our initial example data.csv, the call to totalIncome(0x10040000, 5) will return 1007

From our example involving data.csv, maxIncome(0x10040000, 5)= 0x10040010. Observe from Figure 5 that this address value points to the location of the stock name “Vandelay Industries”, which is valued at the maximum value of $500, and proving that even in times of market uncertainty , the latex polymer industry is booming as ever.

5. minIncome(a0,a1) – This function is to be written in minIncome.asm. a0 contains the file record pointer array location (0x10040000 in our example) But your code MUST handle any address value. a1 contains the number of records in the CSV file. a0 then returns the heap memory pointer to the actual location of the record stock name in the file buffer.

From our example involving data.csv, maxIncome(0x10040000, 5)= 0x10040008. Observe from Figure 5 that this address value points to the location of the stock name “Kramerica”, which is valued at the minimum value of $0, proving once and for all, a sales pitch about a “coffee table book about coffee tables” is an absolutely terrible idea.

Test Cases

Your Lab4 Google Drive folder called TestCases contains more test data files: data1.csv, data2.csv and data3.csv, and data0.csv. To test with these you have to copy any one of them to data.csv in your working directory. The initial data.csv you use by default is the same as TestCases/data0.csv. It corresponds to the file described in this write-up.

Automation

Note that our grading script is automated, so it is imperative that your program’s output matches the specification exactly. The output that deviates from the spec will end up with a poor score.

Files to be submitted to Gradescope

length_of_file.asm

income_from_record.asm maxIncome.asm minIncome.asm totalIncome.asm

You will NOT be editing the following files, and you will NOT BE UPLOADING THEM: lab4_testbench_rev##.asm allocate_file_record_pointers.asm macros_rev#.asm

DO NOT UPLOAD ANY DATA FILES. We use our own data files to test your program.

Assignment Project Exam Help

ORDER TO IMPLEMENT FUNCTIONS

IMPORTANT: START OUT BY SUBMITTING THE FILES AS THEY ARE WITHOUT

MODIFICATION. GRADESCOPE WILL GIVE YOU 20 POINTS AS IS GIVEN THAT THE PROGRAM ASSEMBLES PROPERLY WITHOUT MODIFICATION. DO THIS AS SOON AS

PROGRAM WONT ASSEMBLE PROPERLY.

Make sure you read the code in the lab4_testbench_rev#.asm, and the file macros_rev#.asm you will get many ideas from reading these.

Submit using Gradebook. Do it as many times as you want, there is no penalty for multiple submissions. If your grade gets worse you can go back to your best prior grade.

After you submit the files without any edits, you must get the length_of_file function working next in order to make any further progress. Using the default data.csv you should get a length of 119.

After you get length_of_file working, you must get the income_from_record function working. Double check that the output displayed matches the input. income_from_record_ideas_asm will give you some coding ideas that will help.

Once income_from_record works, get totalIncome, and maxIncome and minIncome functions working in that order. The last two are very similar.

If you get all that working go for the extra credit described next.

PROCRASTINATE.

POTENTIAL SIZABLE EXTRA CREDIT

This is a great opportunity for you to learn assembly language, and become somewhat of a near expert in RISC-V programming, while you work on getting extra credit. With continuous regrading and some significant effort, you should be able to get a perfect score in this lab. If you do, I will be giving you the opportunity to get some extra credit, and learn more while you are at it.

The ideas is that with some effort if you get 100 points on this lab, you can work on optimizing it, too. In particular you can use what you have learned about caller and callee saving conventions when using nested functions (which this lab does do). My most optimized implementation of this lab executed running a total of 2228 instructions.

SOME TIPS

We will be discussing how to debug your code in class along with numerous tricks and techniques to make your life easier. You can use some of the macros on your code to print out intermediate results if you feel you need to. You can also put breakpoints in your code and use the powerful built-in debugger.

A caveat: Be careful: use lwu not lw when loading a pointer from memory. The lw instructions does sign-extension into 64-bits. 64-bit addresses that do not work in RARS and result in unfriendly run-time errors. RARS uses 32-bit pointers, and a 32-bit address space, even though the RV64I model has 64-bit registers. To create pointers it is best to use the unsigned version of these instructions.

You can get advice and help learning how to do this, but you must do this assignment all by yourself. Write comments that shows you know what you are doing! COPYING CODE FROM SOMEONE ELSE OR THE INTERNET IS NOT ALLOWED.

Grading Rubric (100 points total + 20% extra credit)

The following rubric applies provided you have fulfilled all criteria in Minimum Submission Requirements. Failing any criteria listed in that section would result in an automatic grade of zero which cannot be eligible for applying for a regrade request.

20 pt lab4_testbench_rev##.asm assembles without errors (so even if you submit lab4_testbench_rev##.asm with all the other required .asm files COMPLETELY unmodified by you, you will get 20 pts.

30 pt length_of_file.asm works

20 pt income_from_record.asm works

10 pt totalIncome.asm works

10 pt maxIncome.asm works 10 pt minIncome.asm works

AGAIN: Execute this program perfectly using 2300 instructions of execution or less, and you will get an extra 20% extra credit for this lab!! Note: efficient register spilling will help you with this. This is a good way to make up for lost points.

Regrade Requests

Legal Notice

In the case of sites such as Chegg.com, we have been able to locate course material shared by a previous quarter student. Chegg cooperated with us by providing the student’s contact details, which was sufficient proof of the student’s misconduct leading to an automatic failing grade in the course.
