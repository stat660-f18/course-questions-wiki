## Week 1 Quiz Questions and Answers

In order to prepare your Week 1 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-1" in your fork of this repo. Then, after all edits have been made/committed, your Week 1 Quiz should be submitted by initiating a pull request using

- the master branch of the stat660/course_questions_wiki repo as the base fork and

- the week-1 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.



********************************************************************************



[Course Structure Quiz, Problem 1]
- Question (flee11-stat660): For component (10), by "customized", the qustion asks for the screenshot of our __*modified*__ codes of the fizz-buzz recipe codes given in the box, not the screenshot of the fizz-buzz recipe codes given in the box, correct?

- Answer (flee11-stat660): Yes, screenshot of our modified codes. And by "customized", it means editing the codes given in the box so that all 3 conditions below are fulfilled: 
* If a number is only divisible by 3, print first name
* If a number is only divisible by 5, print last name 
* If a number is divisible by 15, print both first name and last name

[Course Structure Quiz, Problem 2]
- Question (flee11-stat660): FlowingData Blog (http://flowingdata.com/) is one of the websites provided by Professor Lankham. When I clicked on a blogpost on that website, it led me to another website (the website of Harvard Business Review). And I read the full article on the Harvard Business Review website. Is that considered still technically an article from the FlowingData Blog website?
- Answer (flee11-stat660): Yes, I hope so.

[Course Structure Quiz, Problem 3]
- Question (flee11-stat660): How much does one have to score on a weekly quiz for that quiz that week to be considered "completed", and to be counted toward the total of 12 quizzes "completed" to earn the Readig for Depth achievement in the course?


[Course Structure Quiz, Problem 4]
- Question (flee11-stat660): Will the team be created according to similar interests for the projects? Will we have different teams for the two projects?


[Course Structure Quiz, Problem 5]
- Question (flee11-stat660): Is a score of 70 and a score of 100 on the final exam treated the same way, in the sense that both scores earn the Building General Knowlege achievement for the course?


[Course Structure Quiz, Problem 6]
- Question (flee11-stat660): Is the Team-based Problem Solving Achievement given the same weight in one's final course letter grade as any other achievement? For example, one can still get an A- if all achievements were earned, but the Team-based achievement is not earned?


[Course Structure Quiz, Problem 7]
- Question (flee11-stat660): By "incomplete submissions can be eligible for resubmission at the instructor's discretion", does it mean upon receiving Professor Lankham's feedback, one should attempt to resubmit with errors fixed?



[Course Structure Quiz, Problem 8]
- Question (flee11-stat660): Should we post in the #-q-and-a-and-a channel (in the course Slack Workspace) any typos or lack of clarity in any course materials?
- Answer (flee11-stat660): Yes, or DM Professor Lankham?


[Course Structure Quiz, Problem 9]
- Question (flee11-stat660): Is there a place where one can post and read our classmates' posts for commonly asked questions, instead of each person indiviually DM the professor perhaps similar questions?


[Course Structure Quiz, Problem 10]
- Question (flee11-stat660): Will we be able to see the questions our classmates created for each quiz? Will some of our questions get answered by the professor or classmates?


[hello_world Week 1 SAS Recipe]
- Question (flee11-stat660): The instruction for the hello world Week 1 SAS Recipe says: "Open SAS 9.4 in BayCloud (or SAS University Edition, if BayCloud VCL is not yet setup), and then type in and run the following hello-world recipe". Can we also use SAS installed to our own computers for this exercise and any future exercises in this SAS course? Baycloud tends to disconnect unexpectedly.

- Question (flee11-stat660): How can we see the output of these 3 lines of SAS code? Will Proc Print work? Since we used _null_, I could not find any saved folder under the work folder. 

[fizz_buzz Week 1 SAS Recipe]
- Question (flee11-stat660):Do the following two chunks of SAS codes (SAS Code chunk 1 and SAS Code chunk 2) give us different results?

SAS Code chunk 1: 

data _null_ ;
do i = 1 to 100;
if mod (i ,3) = 0 then put " < your - first - name >";
else if mod (i , 5) = 0 then put " < your - last - name >";
else put i =;
end ;
run ;

SAS Code chunk 2: 

data _null_ ;
do i = 1 to 100;
if mod (i ,5) = 0 then put " < your - last - name >";
else if mod (i , 3) = 0 then put " < your - first - name >";
else put i =;
end ;
run ;

- Answer (flee11-stat660): Yes, SAS Code chunk 1 puts first name for numbers divisible by 15, whereas SAS Code chunk 2 puts last name for numbers divisible by 15.
