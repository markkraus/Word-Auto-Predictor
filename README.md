# Word-Auto-Predictor
Program that, given a dictionary of words, will predict a valid word based off of previous sequence of letters from user. Program uses a De la Briandias (DLB) Trie to store the passed in dictionary. Program can add words to the DLB trie during program execution.

# Files in this repository

*launch.json*: File for debugging purposes. <br>
*a2.md*: Github markdown file explaining how I implemented each method in AutoComplete.java, as well as time complexity for each method.<br>
*A2Test.java*: Main method used to run the program.<br>
*AutoComplete.java*: Methods that perform fundamental word predicting properties.<br>
*AutoCompleteInterface.java*: Interface explaining how each method operates in AutoComplete.java.<br>
*dict8.txt*: Full-scale dictionary of words.<br>
*small.txt*: Smaller set of words that acts as a dictionary of words.<br>

# How to Run

Main file: A2Test.java<br>
Args: dictionary txt file

## Command line input

javac A2Test.java<br>
javac AutoComplete.java<br>
<br>
java A2Test dict8.txt      - [can substitute dict8.txt with small.txt to see how a smaller dictionary of letters works]
