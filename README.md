# cop4600---project-3-reader-writer-locks-solved
**TO GET THIS SOLUTION VISIT:** [COP4600 – Project 3: Reader/Writer Locks Solved](https://www.ankitcodinghub.com/product/cop4600-project-3-reader-writer-locks-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;109887&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COP4600 - Project 3: Reader\/Writer Locks Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (1 vote)    </div>
    </div>
In this project, you are to:

a. Design and implement a readers/writers lock using semaphores that do not starve the readers and do not starve the writers;

b. Write the main C program that uses Reader/Writer locks;

c. Come up with a set of input scenarios that shows the behavior of your nonstarving lock compared to the starving lock.

This is an individual project.

The output of this project includes:

• A report (in PDF) that includes:

o Your name.

o A short description of the problem you address (hopefully not cut-andpasted from this project but written in your own words).

o A description in plain English and pseudocode of your solution.

o An estimation of the time you spent working on the project.

This is likely to be a very short report – do not try to make it longer than it needs. But do make it neater than your usual.

• A tar file that includes:

o A makefile for easy compilation. The target executable should be rwmain. o A README file that describes how to run your project (arguments, etc). o A C program, named readerwriter.c, that implements the nonstarving locks. o A C program, named main.c, that uses the locks and shows their functionality. Note that the reading/writing parts of the code are only simulated: you do not have to read or write a particular data structure; instead, you might want to pretend to do it, and take some time such as:

reading_writing(){

int x=0, T; T = rand()%10000; for(i = 0; i &lt; T; i++)

for(j = 0; j &lt; T; j++)

x=i*j;

}

This function is only meant to waste time for a variable amount of time. Feel free to adjust this code as you see fit (or ignore all together if not useful in your solution).

o An input file, named scenarios.txt, that proves that your lock:

▪ Is a correct readers/writers lock.

▪ Does not starve the writers.

▪ Does not starve the readers.

▪ Each scenario takes one line (as the traces file in last project) ▪ An example and interpretation of this file is below:

rwrrrrwrr wwrrrrwr

This file contains two scenarios:

1. One in which one reader arrives first, then a writer, then four more readers, another writer, then two more readers.

2. And the second in which two writers arrive first, then four readers, one more writer, and one more reader.

▪ You want these scenarios to test corner cases that are relevant for the point of your design: specifically, that writers will not starve. Thus, you design these test scenarios to make it possible for writers to starve. You do not need lots of readers/writers to make the case. You might want to limit each scenario to 10–15 readers and writers at the very most.

To ease the task of grading, please name your files as requested and put all these files in the same folder. In addition, please hardcode the file name for scenarios.txt with the relative path (not the absolute path) in your main.c code, e.g.:

FILE* ptr = fopen(“scenarios.txt “,”r”);

Suggestions on how to approach this project:

1) Understand the Readers/Writers problem and the solution provided:

b. Check textbook (Chapter 31.5)

c. Look at the code (provided in the text but also on GitHub, linked from the web version of the textbook).

d. (optional) Experiment with the code. If you use the GitHub version, you will realize that it is more complicated than it needs to be because it is written to work on both Mac and Linux systems. It thus obscures the API you will be using on Linux machines. It is, however, a very good

2 opportunity to learn a bit more about programming. Alternatively, you can use the code from the textbook and add what is needed (e.g., a main function to call the functions presented in Figure 31.13) to test it and become comfortable with it.

2) Understand what the problem is with starving writers.

3) Design a solution to this problem (on “paper” first. Don’t code and hope you’ll fix your understanding by debugging concurrency issues. Think first, then implement).

4) Ask questions:

5) Implement, debug, test on C4 lab machines, etc.

7) Write report, edit, edit, edit, spell check, ….

8) Submit, of course.

3
