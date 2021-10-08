

### Overview
I am a member of the team under Todd Huston, Senior Vice President, head of the State and Disctrict Partnerships of the College Board. We aim to allow for every student to have access to the courses.

Standardized tests like ACTs and SATs have been recognised for stong indicators on a student's capability to cope or excel in college, however, our main focus is now on widening the reach of standardized tests to students across USA.
While there are states with high participation, we noticed there are still a large number of states that have abysmally low participation. As part of our mission, our team has set out to see what we can do on improving the participation of these states


### Problem Statement
This project aims to explore what can be further done to increase participation across low participation states based on successful examples

### Assumptions
Nil



### Datasets
1)act_2017.csv: 2017 ACT Scores by State
2)act_2018.csv: 2018 ACT Scores by State
3)sat_2017.csv: 2017 SAT Scores by State
4)sat_2018.csv: 2018 SAT Scores by State



#### Data Dictionary
Feature	Type	Dataset	Description
state	object	ACT	Description of all 50 states + Washington DC
act_participation_2017	float	ACT	Average participation rate for the respective state in the year 2017. This list allows us to focus on the states which have improved participation and how we can emulate its sessions through the changes implemented
act_composite_2017	float	ACT	Average composite score for the respective state in 2017. Composite score is the mean scaled score for the 4 test parameters; (1)english (2)math (3)reading (4)science. This is computed based on the score for the each subject, the raw scores of each subject falls within a range of 1 to 36, the composite score is then tabulated by the mean scores of all 4 subjects. EG; if a student were to score 21 for math, 21 for english, 30 for reading and 30 for science, the composite score of the student will be tabulated as (21+21+30+30)/4 = 25.5
act_participation_2018	float	ACT	Average participation rate for the respective state in the year 2018. By comparing the participation rate of ACT 2017, we can find out the changes made and attempt to find out the cause(s) behind the change and implement it via College Board partnerships
act_composite_2018	float	ACT	Average composite score for the respective state in 2018. While scores are not bell-curbed, elite US universities like those in the ivy league and equally competitive score, generally accept students who score well above average. A higher composite score gives you a better chance of entering into a more reputable or prestigious university
state	object	SAT	Aescription of all 50 states + Washington DC
sat_participation_2018	float	SAT	Average participation rate for the respective state in the year 2018
sat_reading_writing_2018	int	SAT	Average score for reading and writing test for the respective state in 2018. Score of this component ranges from 200 to 800. One cannot score below 200 for each component of the SAT score, nor can one score above 800.
sat_math_2018	int	SAT	Average score for math for the respective state in 2018. Similar to the reading writing component of SAT, this component score ranges from 200 to 800 too.
sat_total_2018	int	SAT	Sum of the 2 tests; math test and reading writing test for 2018. The score of this component is the addition of both the math component and the read writing component. giving it a range of 400 to 1600. As with composite score of ACT, the higher the SAT total score, the better chance it is to get into a better school
sat_participation_2017	float	SAT	Average participation rate for the respective state in the year 2017
sat_reading_writing_2017	int	SAT	Average score for reading and writing test for the respective state in 2017
sat_math_2017	int	SAT	Average score for math for the respective state in 2017
sat_total_2017	int	SAT	Sum of the 2 tests; math test and reading writing test for 2017

### Summary
The main goal of the College Board is to expand access to higher education throught standardized tests like the ACTs and the SATs. While there are states that have high level of participation in the SATs and ACTs allowing broard reach to higher education, some states have consistently low participation that is not in line with our goal.

This project aims to explore what can be further done to increase participation across low participation states based on successful examples

We found out through EDA, that there were specfically 3 states which had a large increase in SAT participation from 2017 to 2018.
These states were
1)Illinois - 1100%
2)Colorado - 900%
3)West Virginia - 200%


Illinois partnered up with College Board to administer the SAT as the state's accountability exam. And every Illinois high school juniors in 2017 will be taking the SAT Illinois has also covered the cost for the students partaking in the mandated SAT tests.



Likewise for Colorado, the state partnered up with College Board to implement the SAT as a statewide high school accountability, and every high school juniors is required to participate. Furthermore, the test is an official administration of the SAT and counts for college Admissions, and it is absolutely free for the students.


West Virginia was a different story, while the participation did go up by 100%, it didnt jump as much as Colorado or Illinois; which made SAT mandatory. West Virginia took a different approach and allowed for SAT to be taken for free, this was the main cause for the spike in number of test takers.

### Conclusion
In conclusion, we found out that there are 2 main reasons on why participation for SAT increased from 2017 to 2018, the first was that the states partnered up with College Board, mandating SAT to be compulsory. The second was that the states which had increase in participation made taking SAT free, this resulted in increase in participation ase seen from West Virgina participation in SAT 2017-18

When pairing both reasons together, removing the cost from taking SAT and mandating it a requirement, participation of the states jumps to 100%. 