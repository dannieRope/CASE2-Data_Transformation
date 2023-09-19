# Background:
You have been provided with a dataset containing registration information for participants of a training 
program. 

The dataset includes the following fields:

`Full name` (which contains title, first name, 2nd name, and 3rd name)

`DOB` (Date of Birth)

`Registration Date`

`Skill` 

The challenge is to create an Excel solution that will dynamically update additional fields as new data is 
added to the dataset. 
The additional fields to be generated are as follows:

`Title:` Extract the title from the "Full name" field.

`Initials:` Create initials from the first letter of the first name, second name.

`Last Name:` Extract the last name from the "Full name" field.

`Full name Short:` Create a shortened version of the "Full name" field.

`Age:` Calculate the age based on the "DOB" field.

`Age Group:` Group participants into different age groups of 25-30, 31-35, 36-40, 41-45,46-50.

`Reg ID:` Generate a unique registration ID for each participant in the format TR-YY-XXX

* TR stands for training (everyone has this), 

* YY would be CS, DA, MA, PM, GD & PG for customer support, data analysis, marketing, project management, graphics design, and programming respectively. 

* XXX stands for the rank of the participant by date and time, the first participant to register would have a rank of 001.

# Challenge Requirements:

Your Excel solution should be designed to handle new data entries. As new rows of registration data are added to the dataset, the additional fields should be updated automatically.

# Solving The Challenge
