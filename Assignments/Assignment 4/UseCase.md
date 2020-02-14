Use case: Submit file with attached comment

Primary actor: Student

Stakeholders and Interests: 
  * Student: wants to submit an assignment, and add a comment to the submission
  * Instructor and TA: want to collect submissions for grading
Precondition: user is logged in to the system

Main success scenario
1. Student selects an assignment to submit
2. Student uploads file for submission
3. Student types in a text box for the comment
4. Student clicks submit to submit the assignment
5. System checks for constraints
6. Assignment is stored in the system, Instructor and TA can view the submission along with the comment. 

Constraints: 
 * File type must be the correct type for the assignment
 * Comment must be shorter than the maximum number of characters
 * Comment cannot have sql injection
