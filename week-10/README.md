
## Week 10 Quiz Questions and Answers

In order to prepare your Week 10 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-10" in your fork of this repo. Then, after all edits have been made/committed, your Week 10 Quiz should be submitted by initiating a pull request using

- the master branch of the stat660/course_questions_wiki repo as the base fork and

- the week-10 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.



********************************************************************************



[Course Textbook Chapter 14, Problem 1]
What would happen if 'of' is omitted in the mean function?
The word 'of' is used when a variable list is used to specify a range of variables as the function argument,if it is omitted, the function argument might not be interpreted as expected.



[Course Textbook Chapter 14, Problem 2]
When data type is automaticlly converted, will a message is written to the SAS log stating the conversion?
Yes.


[Course Textbook Chapter 14, Problem 3]
What's the difference between 'input' and 'put' function?
The 'input' function is used to convert character values to numeric values while 'put' is used the opposite way.



[Course Textbook Chapter 14, Problem 4]
What's the use of format in 'put' function?
A right format is used to make sure the function can read the form of the values properly.


[Course Textbook Chapter 14, Problem 5]
What is MDY function in SAS?
The MDY function returns a SAS date value from month, day, and year values. Its syntax is MDY (month, day, year).The use of four-digit year values in the MDY function is recommended.


[Course Textbook Chapter 14, Problem 6]
What's the use of SCAN function?
The SCAN function is used to extract words from a character, and the positions of words are marked by a delimiter. 

[Course Textbook Chapter 14, Problem 7]
What's the difference between SUBSTR and SCAN?
The SUBSTR function is best used when you know the exact position of the substring to extract from the character value while SCAN is used to extract words by its position which is marked by a delimiter.



[Course Textbook Chapter 14, Problem 10]
Why 'lowcase' function is needed in this case?


[Week 10 SAS Recipe: basic_recipe_for_combining_data_vertically]



[Week 10 SAS Recipe: adv_recipe_for_combining_data_vertically]


