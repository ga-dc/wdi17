# Homework

Homework will take more time for some, and less time for others. It is up to you how you want to partition your time for a given exercise.

**Turn in something**. Turning in an incomplete assignment is **infinitely** better than turning in nothing at all. We can't get you the help you need unless we see what you're working on.

**Late homework will not be accepted**. If you need help submitting homework, an instructor can assist during [office hours](https://github.com/ga-dc/wdi15/blob/master/office-hours.md).

You can track your homework completion rate in [Garnet](http://garnet.wdidc.org).

**Assignments may ask you to learn or research something that has not been explicitly covered in class.** Learning how to learn is fundamental to becoming a successful developer.

## Due Dates and Grading

You will generally be assigned homework every day. Due dates can be found in the [class schedule](https://ga-dc.github.io/wdi15).


Unless otherwise directed, each assignment should be forked and cloned from a `ga-wdi-exercises` repository, and submitted as a pull request to the original `ga-wdi-exercises` repository from your fork. For more information on pull requests, see below.

**Plagiarized homework will not be accepted.** Concerned about what is considered plagiarism? Consult an instructor.

**Homework is graded only on meaningful progress**. That is: that you made an effort to complete it, regardless of whether you were successful. 

There are three possible grades for each assignment:
- **Complete:** something was turned in, and meaningful effort was made.
- **Incomplete:** something was turned in, but meaningful effort was not made: the submission is blank, or it was blatantly copied wholesale from somewhere.
- **Missing:** nothing was turned in.

**We rely on homework to know where you're at.** It's very much to your advantage to begin your homework the day it's assigned. Any problems can be addressed before the unit continues, preventing you from falling behind.


### Feedback

**Feedback will only be given in response to specific questions.** Requests for feedback, however, are encouraged (see below).

When submitting your pull request or issue, please ask specific and targeted question in the form:

1. I wanted...
2. I tried...
3. I expected...
4. I got...


For example:

> I wanted to double the input number. I tried `var doubled = userInput * 2`. I expected the value to be twice the input number but instead got `NaN`. What is causing this?


## What to include with your submission

On **every submission** -- that is, on every pull request (or, sometimes, issue) -- please include...
- **Comfort score**, out of 5
- **Completeness score**, out of 5

## The Submission Process

All homework assignments will have their own Github repository, under the `ga-wdi-exercises` account.

1. Please **fork** new assignments.
2. Then, **clone** your fork to your computer.
3. Add and commit your work.
4. Then, **push** your completed work to your forked repository.
5. Finally, make a **pull request** to the upstream repository (in `ga-wdi-exercises`).

For example, the sequence of commands you might follow to complete the above process is:

```
# Click grey 'Fork' button on Github
js1989: ~/wdi $ git clone git@github.com:js1989/homeworkaroo.git
js1989: ~/wdi/homeworkaroo $ cd homeworkaroo
js1989: ~/wdi/homeworkaroo (master) $ git checkout -b johnsmith_solution
js1989: ~/wdi/homeworkaroo (master) $ touch did_my_homework.txt
js1989: ~/wdi/homeworkaroo (master) $ git add did_my_homework.txt
js1989: ~/wdi/homeworkaroo (master) $ git commit -m "Added did_hw file. All done"
js1989: ~/wdi/homeworkaroo (master) $ git push origin master
# Click green 'New pull request' button on Github
# Add a title with your name and the name of the assignment
# Add your comfort and completeness scores and any requests for feedback
# Click green 'Create pull request' button
# Click the new 'Create pull request' button
```

### If you have errors...

...please refer to [this readme](https://github.com/ga-wdi-lessons/git-review) for instructions on common Git errors.
