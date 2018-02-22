
Simulated Reality - Part 1
========================================================
author: Silas Furu Friby 
date: 2018-02-22
autosize: true


Program
========================================================

- $\texttt{R}$ 
  
  - $\texttt{R}$-projects
  - "good to know"
  - "correct" coding
  
- Version control with Git

- Keywords and assigment part 1

- real world example


R: projects
========================================================

Always use project!

- working directory

- project options

- git


R: projects
========================================================

Good projeckt structure:

- folders: data, results, function, assumptions, etc.

- one main file where data is loaded and functions are sourced


R: "good to know" - variable types
========================================================

Short list - much more!

- clear work space

- vaiable types: numeric, character, vector, matrix, data frame, lists, NA, NULL

- vector and matrix can only be one type

- data frame and list can have several types

- watch out for factors! Use option stringAsFactors = FALSE


R: "good to know" - local and global
========================================================

- Basically everything outside a function is global

- This can create problems if not aware!

- Try to wrap as much as possible in functions

- First make the code work, then write a function around it


R: "correct" coding
========================================================

Again, this is subjective.

- Let Rstudio help you: tools -> global options -> code -> diagnostics (set it now!)

- keep it organised! Minimize risk of errors

- A lot of comments in code

- Loooooog variable names using "_". E.g. this_is_a_good_name

- Use R oxygen and R markdown for documentation


R: Version control with Git
========================================================

Amazing!!

- Used everywhere in the job market - software developement

- We are actually developeing software, when writing mathematical models

- wish I had known about this at University for bachelor and master thesis

- Get used to Git - it is not complicated! All about habbits

- draw a sketch illustrating the idea: remote (gitHub) and local (gitHub Desktop / Rstudio)



Start up project
========================================================

Example with Rstudio, git, markdown, slides, etc.

1) create empty repository named simulating_reality at your own user

1) go to gitHub and clone simulating_reality from user "SilasFriby" to gitHub Desktop

2) change remote repository in gitHub Desktop -> repository -> settings

3) let us check out the history (only really possible at gitHub not in gitHub Desktop)

4) main script

5) markdown

6) slides




Keywords and assigment part 1
========================================================

- Stochastic calculus, Wiener proces, stochastic integrals, stochastic differential equation
- Arbitrage free and Complete market
- Risk neutral pricing, equivalent probability measures, martingales
- Monte Carlo simulation
- European call and put options 



Real world example
========================================================

Bonus option in pension liabilities

New legislation from the FSA implies the use of an ESG!



