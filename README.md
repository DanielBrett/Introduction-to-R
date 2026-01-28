![Tool Logo](IntroR.png)


# Introduction to R
This workshop serves as an introduction to the R programming language as well as to the R Studio interface. By the end of this workshop you should be able to do the following:
 - Navigate the [Posit Cloud interface](https://posit.cloud/)
 - Create and manipulate variables in R
 - Make basic adjustment and perform simple analysis on datasets
 - Create and import new datasets
 - Find and install packages from the CRAN
 - Export your data back out of Posit Cloud

No prior experience with R is needed for this workshop
  
*Estimated workshop length: 2 hours*
  
---
  
## Setup Instructions
In preparation for this workshop, you will need to have a Posit account (previously was an R Studio Cloud account) and have a new R Studio project open on Posit Cloud.  Follow the steps below to get set up.

- (Skip this step if you already have an Posit account) Begin by going to [https://posit.cloud/](https://posit.cloud/) and signing up for an account by clicking on the "Sign Up" text at the top right of the screen, then click the grey "Sign Up" button and fill in the form (or use the convenient Google or GitHub options if you have one of those accounts)
- Log in to Posit
- You should arrive at your workspace.  From here click on the button that says, "New Project" and select "New R Studio Project"
- Once your project has finished building, open the "Source" window by clicking on the double box symbol in the top right corner of the "Console" window

![Source Button Location](sourcebutton.png)

 - Rename your project by clicking on the name at the top.  Name it whatever you like (eg. "Intro to R Workshop")

![Title Change](projecttitle.png)

 - And thats it!  You are all set for the workshop
   
 ---
   
## Function Cheat Sheet
Here is a list of all the functions that we will be using in this workshop along with a description of each.

**data()**  
Used to access the pre-loaded datasets that come with R

**mean(), median(), summary()**  
Performs math on the value(s) given in the brackets and displays the result  

**rm()**  
Removes the designated variable from the environment

**help()**  
Displays the help documentation (if available) for whatever is placed in the brackets (functions, datasets, etc)

**c()**  
Combines values separated by commas into a list (also known as a vector)

**sum()**  
Adds the values in the brackets together and produces the total so long as they are all numerical values

**install.packages()**  
Downloads the designated package from the CRAN into the active instance of R

**library()**  
Activates the designated installed package so that its functions may be used
  
---
  
## Workshop Tasks
These are all of the tasks that will be assigned in the "DO" portions of the workshop.

**Task Set #1**  
A. Save your source file to your working directory using the save button  
B. Run a math problem in the console by typing it and pressing enter  
C. Run the same problem in the Source file using the run button or the keyboard shortcut  
D. When you are done type "DONE!" into the chat  
  
**Task Set #2**  
A. Load the AirPassengers data into your environment  
B. Look at it by typing the name of the dataset  
C. When that is done type "LOADED!" into the chat  
  
**Task Set #3**  
A. Create 2 variables.  One containing the number of passengers for January 1950 and the other containing the passengers for January 1960  
B. Use the variables you just created to find out how many more people flew in 1960 than in 1950.  (Remember that when a variable is used in a formula, it is replaced with whatever is inside of it before calculations are done)  
C. Remove both of the variables that you just created from the environment  
D. Use the help function to learn about one of the other functions we have used so far  
E. Once you are done put a message in the chat saying "GOT IT!"  
  
**Task Set #4**  
A. Create variables for the 1949 and 1950 AirPassengers data.  
B. Calculate the total number of passengers that flew in 1949 and 1950  
C. Make a new variable called AirTotal that contains the total number of passengers that flew in 1949 and 1950  
D. Once you are done, type "SOLVED!" in the chat  
  
**Task Set #5**  
A. Load the mtcars data into your environment.  
B. Find which vehicle has the fastest ¼ Mile Time.  
C. Make a variable called “fastest” that contains just the row with the fastest cars data  
D. Write a .csv file that contains the information for the fastest car and name it "FastestCar.csv"  
E. When you are done type "COMPLETED!" in the chat.  
  
**Task Set #6**  
A. Go to https://cran.r-project.org/web/packages/available_packages_by_name.html#available-packages-A and find a package that sounds interesting  
B. Use install.packages() to add it to your environment  
C. Turn on the package using library()  
D. Read its help documentation using help()  
E. When you are done type "WOOHOO!!!!!!!" into the chat.  Feel free to share the name of the package you found as well if you think others might find it interesting.  
  
---
  
## Next Steps
If you are looking to continue enhancing your knowledge of R, check out the options below!

[YaRrr! The Pirate's Guide to R](https://bookdown.org/ndphillips/YaRrr/)   
  
[W3Schools R Tutorial](https://www.w3schools.com/r/default.asp)
