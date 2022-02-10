# stock_analysis

**Overview of Project**
: The purpose of this analysis was to refactor an existing macro to optimize the code and allow the script to run faster and more efficiently.

**Results**
:With much time and review, I found the error in my code!! I was missing a loop at the final step that printed the results. With this find, the refactored code worked significantly faster than the original, although hard to quantify per my original notes below stating that the runtimes were much higher than the actual elapsed time.  

Unfortunately, I had a good deal of issues refactoring the code with errors that seemed to pop up in different places after the previous error was corrected. For that reason, I can't provide updated screenshots of the refactored code running successfully. 

: I have included the original runtimes of the base code. Hoping that we can isolate the issue so I can learn what I was missing and update this assignment. I also noticed that while the script ran almost instantaneously, the seconds displayed in these screenshots appear to show much more time than what actually elapsed.

![2017](https://github.com/ozzirk/stock_analysis/blob/main/VBA_Challenge_2017.png?raw=true)
![2017 Refactored](https://github.com/ozzirk/stock_analysis/blob/main/Results.png?raw=true)

**Summary**
: In summary, it's great to refactor code as your knowledge of the subject/coding increases. This allows for the code to be more versatile, and use less computer resources while running. The downside, of course is that sometimes things can become overcomplicated, as I was unsuccessful in being able to refactor the existing code that was working to my expectations.
: These pros and cons apply 

Original Code
 
 **Pros**
 - Easier to interpret with less variables
 - Executed as expected

**Cons**
 - Was somewhat redundant, allowing lines of code to run each iteration that may not have needed to

Refactored code

**Pros**

 - Included nested loops, so executed code was minimized
 - Increased number of variables allowed for more flexibility

**Cons**
 - Additional variables sometimes made the code harder to interpret
