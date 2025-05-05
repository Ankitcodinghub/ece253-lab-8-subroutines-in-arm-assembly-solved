# ece253-lab-8-subroutines-in-arm-assembly-solved
**TO GET THIS SOLUTION VISIT:** [ECE253 Lab 8-Subroutines in ARM assembly  Solved](https://www.ankitcodinghub.com/product/ece253-lab-8-subroutines-in-arm-assembly-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;94380&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;ECE253 Lab 8-Subroutines in ARM assembly&nbsp; Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Laboratory Exercise 8

Subroutines in ARM assembly

The purpose of this lab is to:

1. learn how to write basic programs in assembly language

2. learn how to use loops and subroutines in assembly language

1 Preparation

Please refer to the Lab 7 handout for resources related to the ARM processor and the cpulator simulator. A portion of the mark for this lab will be allocated to questions posed by the TAs in your lab session.

2 PartI

In Lab 7, you were given sample code in Part 2 to review and understand. Now you will be modifying that code to use subroutines.

Specifically, perform the following:

<ol>
<li>Make a copy of the file part2.s from Lab 7 and call it part1.s.</li>
<li>Take the code which calculates the number of consecutive 1s and make it into a sub- routine called ONES. Have the subroutine use register R1 to receive the input data and register R0 for returning the result. At the top of your file, make the subroutine global .global ONES. This will allow the automarker to call your subroutine from another file.</li>
<li>Add more words in memory starting from the label TESTNUM. You can add as many words as you like—but include at least 10 words. Terminate the list with a -1.</li>
<li>In your main program (in a separate file), call the newly-created subroutine in a loop for every word of data that you placed in memory. Keep track of the longest string of 1s in any of the words, and have this result in register R5 when your program completes execution. Note: The cpulator simulator requires all your code to
1
</li>
</ol>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
3

</div>
</div>
<div class="layoutArea">
<div class="column">
5.

6.

</div>
<div class="column">
be in one file. For testing and debugging with the simulator, please put all your code in one file and then copy paste the subroutine to a separate file for submission. You can have multiple files when running on the DE1-SoC boards in lab.

Make sure to use the single-step capability of the simulator to step through your code and observe what happens when your subroutine call and return instructions are executed.

For the code you submit from this part, your file should only contain the ONES sub- routine. The submitted file should not contain your main program or your TESTNUM list.

Part II

</div>
</div>
<div class="layoutArea">
<div class="column">
Write an assembly language program to sort a list of 32-bit unsigned numbers into ascending order. The first 32-bit number in the list gives the number of items in the list and the remainder of the entries are the numbers to be sorted. The list of data must be sorted “in place”, meaning that you are not allowed to create a copy in memory of the list to do the sorting. The list you should sort, including the number count, can be defined using the .word directive at the end of your program as follows:

<pre>LIST: .word 10, 1400, 45, 23, 5, 3, 8, 17, 4, 20, 33
</pre>
Note that the first number in the list is 10, indicating that there are 10 numbers following it. In your code you should have a main program that loops through the list of numbers as needed to perform the sorting operation. Use bubble sort to perform the sorting. Provide pseudo code, similar to C code, that illustrates how your sorting algorithm works. Then, write an assembly language program.

As your main program loops through the list of numbers it will be necessary to compare the values of pairs of list elements to see if they need to be swapped. You are to use a subroutine, called SWAP, to compare such list elements. The SWAP subroutine is passed the address of a list element, compares it to the following element in the list, and swaps the two elements in memory if necessary. The SWAP subroutine should return 1 if a swap is performed, and 0 if not. Pass the address of the first list element to SWAP in register R0, and also pass the return value back to the main program in register R0.

1. Your main program (start:) and your subroutine SWAP should be submitted as one file called part2.s. Please make both start and SWAP global.

2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
2. You should test your code using the CPUlator simulator.

3. Prior to submitting your code, please remove the line starting with “LIST: ”.

</div>
</div>
</div>
