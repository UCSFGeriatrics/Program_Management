# Program Management
scripts to assist with Program Management


## Applicant Assignment
[link to code](https://github.com/UCSFGeriatrics/Program_Management/blob/master/applicant_assignment)

This is to assign a list of applicants to a set number of reviewers using python. The list of applicants is pulled from the text tile [applicants.txt](https://github.com/UCSFGeriatrics/Program_Management/blob/master/applicants.txt)

The number of applicants needs to be a multiple of number of reviewers for this to work.

The output for the code provided will appear as follows:

```

The list of applicants are: ['Harry', 'Hermione', 'Ron', 'Ginny', 'Luna', 'Neville', 
'Fred', 'George', 'Myrtle', 'Olaf', 'Elsa', 'Anna', 'Kristoff', 'Marshmallow', 'Snow Boogies']

+-----------+----------------------------------------+
|  Reviewer |          Assigned Applicants           |
+-----------+----------------------------------------+
| ReviewerA |       ['Harry', 'Luna', 'Anna']        |
| ReviewerB |     ['Marshmallow', 'Olaf', 'Ron']     |
| ReviewerC |   ['Neville', 'Kristoff', 'Myrtle']    |
| ReviewerD | ['Snow Boogies', 'Hermione', 'George'] |
| ReviewerE |       ['Fred', 'Elsa', 'Ginny']        |
+-----------+----------------------------------------+

```
