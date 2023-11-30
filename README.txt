Title: Application Of Graph Optimization
By: Saikrishna Sudharshan, Prathik Shetty, Advay Burte

This Folder Contains our 3 Approaches to tackle the Assignment Problem for the "Discrete Structures in Computer Science Project"

Problem Statement:
In a university setting, the task of assigning subjects to professors for the upcoming semester requires careful consideration of various factors, including professor preferences, teaching load requirements, and subject prerequisites.
To effectively manage this allocation process, it's essential to establish a structured approach that ensures each professor is assigned subjects aligned with their interests and expertise while adhering to their desired teaching load.

Problem Components:
1.Subjects: A set of courses offered in the semester, categorized into four groups: "FD-CDCs," "HD-CDCs," "FD-Es," and "HD-Es," with the given priority order.
2.Professors: A collection of faculty members with individual teaching preferences for each subject category.
3.Preferences: Each professor has a priority list for each subject category, indicating their willingness to teach those subjects. Subjects not included in a professor's priority list CANNOT be assigned to that professor.
4.Teaching Load: Each professor has a preferred teaching load, specifying the number of subjects they are willing to teach.

Objective:
1.The primary objective is to distribute university subjects among professors in a manner that satisfies the following criteria:
2.Preference Satisfaction: Minimize the number of unfulfilled subject teaching preferences among professors.
3.Teaching Load Compliance: Respect the teaching load preferences of each professor.
4.Subject Allocation Completeness: Ensure that every subject from the "FD-CDC" and "HD-CDC" catagories is assigned to a single professor.

Approaches:
1.Brute Force(See BruteForceREADME.txt)
2.Binary Integer Linear Programming(See BinaryIntegerProgrammingREADME.txt)
3.A Greedy Algorithm(GreedyAlgorithmREADME.txt)
NOTE: Approaches are discussed in their respective READMEs.

NOTE: Different codes are in their respective folders along with their READMEs. 
NOTE: Please make sure not to change the directory structure in the folders.
