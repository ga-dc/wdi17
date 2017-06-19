# Homework

Homework will take more time for some, and less time for others. It is up to you how you want to partition your time for a given exercise.

**Turn in something**. Turning in an incomplete assignment is **infinitely** better than turning in nothing at all. We can't get you the help you need unless we see what you're working on. That said...

**Late homework will not be accepted**. If you have issues submitting homework please let us know.

You can track your homework completion rate in [Garnet](http://garnet.wdidc.org).

**Each assignment will ask you to learn or research something that has explicitly not been covered in class.** Learning how to learn is fundamental to becoming a successful developer.

## Due Dates and Grading

You will generally be assigned homework every day. Due dates can be found in the [calendar](https://github.com/ga-dc/wdi17).

Unless otherwise directed, each assignment should be forked and cloned from a `ga-wdi-exercises` repository, and submitted as a pull request to the original `ga-wdi-exercises` repository from your fork. For more information on pull requests, see below.

**Plagiarized homework will not be accepted.** Concerned about what is considered plagiarism? Consult an instructor.

In order to receive a "Complete" grade on an assignment, your submission must contain functional code that goes towards solving the assignment prompt.

If you are unable to provide any code that goes towards solving the assignment prompt, you should, at the least...

- Provide a pseudocode solution
- Indicate what concept(s) you are struggling with
- Include specific questions you would like an instructor to answer. Also write a two-sentence summary of what you see in Google when you search for those questions

You will receive an "Incomplete" for this submission, which counts for 0% of the assignment. However, it's very much to your advantage to get this done at a minimum so instructors can address your concerns before the unit continues and keep you from falling behind.

If you do not turn in an assignment by the due date or don't meet the requisites for an "Incomplete," it will be marked as "Missing." A missing counts for 0% of the assignment.

**Feedback will not be given on assignments by an instructor unless you specifically request it.** Requests for feedback, however, are highly encouraged. [See below for more details](#in-order-to-get-feedback-on-your-assignment).

## What to include with your submission

On **every submission** -- that is, on every pull request (or, sometimes, issue) -- please include...
- **Comfort score**, out of 5
- **Completeness score**, out of 5

### In order to get feedback on your assignment...

...when submitting your pull request or issue, please...

- Ask specific questions, **ending them with a question mark**. We receive *lots* of assignments, and we rely on questions marks to provide a visual cue that we should stop and address something! Be sure to point us to the lines of code where you encountered issues and what you've already tried to solve your problems.

  For example:

  > Any thoughts as to why the function on line 49 kept returning 'NaN'? I Googled the error and found that I need to convert my inputs to integers but I'm not sure where to apply the method.

## The Submission Process

All homework assignments will have their own Github repository, under the `ga-wdi-exercises` account.

1. Please **fork** new assignments.
2. Then, **clone** your fork to your computer.
3. Create a feature branch in the format of `yourname_solution`.
4. Complete your work inside it.
5. Then, **push** your completed work to your forked repository.
6. Finally, make a **pull request** to the upstream repository (in `ga-wdi-exercises`).

For example, the sequence of commands you might follow to complete the above process is:

```
# Click gray 'Fork' button on Github
js1989: ~/wdi $ git clone git@github.com:js1989/homeworkaroo.git
js1989: ~/wdi/homeworkaroo $ cd homeworkaroo
js1989: ~/wdi/homeworkaroo (master) $ git checkout -b johnsmith_solution
js1989: ~/wdi/homeworkaroo (johnsmith_solution) $ touch did_my_homework.txt
js1989: ~/wdi/homeworkaroo (johnsmith_solution *) $ git add did_my_homework.txt
js1989: ~/wdi/homeworkaroo (johnsmith_solution +) $ git commit -m "Added did_hw file. All done"
js1989: ~/wdi/homeworkaroo (johnsmith_solution) $ git push origin johnsmith_solution
# Click green 'New pull request' button on Github
# Click green 'Create pull request' button
# Click the new 'Create pull request' button
```

### If you have errors...

...please refer to [this readme](https://github.com/ga-wdi-lessons/git-review) for instructions on common Git errors.
