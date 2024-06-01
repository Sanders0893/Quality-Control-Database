# Quality-Control-Database
Quality Control Database. Randomized test questions, tracking, automates records and queries/reporting.

This MS Access Database was created using Visual Basic Programming language, switch boards (for navigation), and SQL. In my previous work, the Quality Control section required a more efficient way to track test scores and quickly make use of the dataset/information. Additionally, the other concern was that the test takers were beginning to memorize test versions and the quality of the knowledge of the performers was diluted.
 This database was created to:

 (1) Allow the QC personnel to input sensitive questions, the answer, and corresponding reference for the information as a record to the database. I used SQL to extract the desired position to be tested on a used a randomized number generator function to traverse that dataset to a random record not already selected so that it could output 25 random questions.

(2) After a person finishes an exam the score is automatically saved into the database. In the true version, there are local file paths used to archive the scores and information into a restricted digital storage on the military installation. This code still exist in the code base and they system might attempt to access the file path, which can create an error. It is an acceptable error that is expected because this file exist outside of that digital space. Moreover, in the original version the ability to access the restricted drive allowed the team to have a back up of all scores outside of the database.

(3) There are extra features such as queries and options available to track all 500 personnel expiring certifications as well as which phase they are in. Example, "Phase II," in the database are members that are in a 45/60 study period and are due to test at the end.
