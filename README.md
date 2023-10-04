[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/QcdN-TgL)
# Assignment 1: Intermediate Text Processing
**Westmont College Fall 2023**

**CS 128 Information Retrieval and Big Data**

*Assistant Professor* Mike Ryu (mryu@westmont.edu) 

## Autor Information
* **Name(s)**: Garrett Buchanan, Livingstone Rwagatare 
* **Email(s)**: gbuchanan@westmont.edu, lrwagatare@westmont.edu  



## Problem Description

- General Overview:
    - In this assignment we were tasked to create (do modification) a Python program to analyze word and 2-word group frequencies in a text file. Set up data structures in freq_models.py, use utility functions in freq_utils.py for processing, and build the main frequency calculations in freq_counter.py. After integration, test the program with sample data.



## Description of the Solution

1.Data Model Implementation 
 - freq_models.py: We modify three classes (Pair,TwoGram, and Frequency Class).
    - Pair Class: Manages two items. Implements getter, setter, and equality. 
    - TwoGram Class: inherits pair. Implements rich comparisons and hash method. 
    - Frequency Class: Manages an object and its frequency. Implements constructor, getters, setters, rich comparisons, and string/ hash methods 

2. Utility Functions
    - Freq_utils.py
        - tokenize_file: Split file contents into alphanumeric tokes
        - print_frequencies: Outuputs a list of Frequency objects in a specific fortat. 

3. Processing Logic: 
    - freq_counter.py 
        - compute_word_freq: compute word frequencies from a list of tokens 
        - compte_twogram_freq: computer 2-gram frequencies from a list of tokens.

## Key Takeaways


- Make sure to get office hour help as early aas possible even though we started early
- We learned how to use multiple files that pull on each other in order to (mostly) complete the project
- We learned that little changes can be the difference between passing all tests and failing most tests
- Ex. One comma changed our failures from 2 to 4 and also created 2 errors
- Biggest takeaway is that We both need to practice out python outside of class to be able to be at a proficient level that is evidently needed for this course
- We learned how to account for None types and types other than instances of out class and how to pair that with a java-style comparator method, which is something neither of us had done before
- We learned how to properly implement regexes and use re
- We learned how to iterate through a file and return values along with formatted text
- We learned how to use a dictionary and lists to return a counter of occurences of words and their frequency within a given document




## Teamwork Report
1. **How did you and your partner collaborate to complete this assignment?**

 - My partner and I met in person four times for this assignment: on Thursday, Sunday, Monday, and Tuesday.
 - Each collaboration session we had lasted for an average of 2 hours and 30 minutes.
 - We completed our tasks, which included implementing different classes, adding them, committing them, and then pulling and pushing so the other could see the changes.
 - We did this while in the same room. After pushing and pulling, we would explain our changes to each other.



2. **How did you and your partner divide up the responsibilities?**

    - Each time we met, we read quetions/ tasks together. 
    -We divided tasks based on the amount of work required. For instance, for freq_models.py, we divided different classes among ourselves. I worked on TwoGram, implementing rich comparisons and the hash method, whereas Garrett focused on the Pair class to implement setters, getters, and equality methods. This division of labor was consistent for the rest of the files. 
    - Garrett tested most of the code because he is proficient at it. I often shared my code with him for testing. If there were any issues, we collaborated to fix the errors.




3. **What is one thing you learned from each other by collaborating?**

    -I learned a lot during this assignment, but what stood out the most was the power of GitHub. I was amazed by how much you can do with GitHub. Collaborating on a platform like GitHub gave me a glimpse into the world of programming, and it deepened my love for computer science.
