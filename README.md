# PYTHON-Automatic-recruitment-system
This system is aimed for big organizations that get tons of job applications daily whcih don't even meet the job description.

This is a complete recruitment system. It takes the company's email id and password as input and searches for all the unseen emails with subject "resume"(any keyword can be used. for ex: job,cv. It can also take date or search before kind of parameters.). Next it asks for keywords to search in the resume(skillset).

It will download the attachments for emails with subject resume in a specified folder. The attachment can be a pdf or docx.The resumes will be saved with file name as email id to avoid overwriting common names.

The resumes will then be scanned to look for the specified skillset.(it can be modified for different uses.)How to evaluate resume varies for different organizations.

The email id , name , phone number, date will be put in an excel sheet with a decision 'yes' or 'no' against them.

The candidates will be sent an automated reply based on the decision in excel sheet.

Every time the program is run a new directory is created named as current date-time and all the resumes as well as the excel sheet are put in that directory.This is done because each time a resume is downloaded from email its status is changed from seen to unseen and all this resumes are put in the specific date-time folder and this avoids duplication .
