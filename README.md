# Test-Score-Calculator

Objectives
This project aims to provide teachers with an efficient, data-driven tool for analyzing student test scores. By automating score evaluation, the system will enable educators to gain deeper insights into class performance, reducing the time spent on manual calculations. Teachers will be able to enter student test scores, and the program will automatically compute the highest, lowest, and average scores, presenting the data in a clear and accessible format.

Beyond saving time, the system will help educators identify trends in student performance, allowing them to pinpoint areas for improvement and adjust teaching strategies accordingly. Without this tool, teachers will continue relying on outdated methods, limiting their ability to make informed, data-backed decisions. Implementing this solution will not only streamline workflow for educators but also benefit students, as schools and administrators will be able to monitor academic trends and student success more effectively. The insights generated will contribute to refining educational approaches, ensuring students receive the necessary support to enhance their learning experience.  

Statement of Functionality

•	Prompt User for Input – The program will display instructions for the user to enter the test scores to be analyzed. 

•	Store Test Scores – The system will read and securely store the entered test scores in a stack for processing.

•	Determine Highest and Lowest Scores – Using a linear search algorithm, the program will compare each test score against the current highest and lowest values. The first entered score will be initialized as both the highest and lowest, and subsequent scores will be evaluated. If a score is higher than the stored highest, it will replace the previous highest value. If a score is lower than the stored lowest, it will replace the previous lowest value.

•	Calculate Average Score – The program will iterate through all stored test scores, summing them together and dividing by the total number of scores to compute the average.

•	Generate Output – The system will display the highest, lowest, and average scores in a clear format. Additionally, it will assign a letter grade equivalence to each score using structured conditional logic (if-else statements) and will output it with the score

 
Scope

Phase 1: User Input

1. 	Develop ability to prompt user for input.
2.	Allow the user to type 5 test scores to be analyzed.
3. 	Read the data. 
4. 	Store the data in a stack.

Phase 2: Determine Highest and Lowest Scores
1. 	Set the first score as the highest and lowest.
2. 	Loop through all the scores. If a score is higher than the stored highest, it will replace the previous highest value. If a score is lower than the stored lowest, it will replace the previous lowest value.
3. 	Store the highest and lowest scores.

Phase 3: Average
1.  Add all the test scores together.
2.  Divide by the number of test scores.
3. 	Store the average score.

Phase 4: Output
1. 	Output the lowest score and use an if-else statement to find the letter grade equivalence and output it. 
2. 	Output the highest score and use an if-else statement to find the letter grade equivalence and output it. 
3. 	Output the average score and use an if-else statement to find the letter grade equivalence and output it. 

Phase 5: Testing and Debugging 
1. 	Test and debug the program making improvements as necessary. 

