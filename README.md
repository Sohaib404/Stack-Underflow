# Stack-Underflow
Fully functional command line style forum that utilizes python, MongoDB, and SQL to create an experience similar to Stack Overflow.

## User Guide

### Phase 1 is ran first:
User enters the port number needed to connect to a server. This creates a database and fills it
with collections to be used for phase 2.

### Phase 2 ran after Phase 1:
User enters a port number and is connected to a database. User should be connecting to same
port as in phase 1

**User input:**
User is asked if they want to enter in a User id. If No then the command menu appears.
If the user decides yes, then they enter a numeric value for the ID and are presented with a
User report.

A menu then appears with the commands: Post a question, Search for questions, Exit program
and go back.

**Post Question/Post Answer:**
Users provide a Title and body to the question they are asking and can add tags if they want to.

**Search for Questions:**
The user is required to enter keywords that are used to find questions with the same term.
5 questions are displayed at a time and the user can choose to display 5 more. They can then
choose to enter the id of the post they want to perform these 3 actions on: Post an answer for
the question, list all answers for the question or cast a vote on the question.

**List answers:**
Shows the user all the answers for that specific question. Displays 5 posts at a time, can view
more if the user enters the command. Users can also choose an answer to which they can cast
a vote.

**Cast Vote:**
Users place a vote to a post. If the user has inputted an Id then they can only vote on that
specific post once
