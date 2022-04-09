# Pewlett-Hackard-Analysis

## Overview:
This analysis is being conducted on the workforce of PH Corp. As with many major US corporations PH is facing a potential “silver tsunami” of experienced people retiring in large numbers leaving a critical skills and knowledge gap. Once the magnitude of the problem is identified, there are several actions that could be taken. E.g. develop a mentorship program where soon-to-retire employees start working part-time and train/mentor younger staff to ensure continuity in workplace. The objective of this analysis is to look at the entire workforce in two important ways:
- Determine the number of employees who may be expected to retire shortly by title
- Identify those employees who are eligible to participate in an employee mentorship program.

### Deliverable 1:

First, a table was created listing all the employees who were born between 1/1/52 and 12/31/55. These are potential retirees who impact the analysis. This is shown in the table below.
<img width="527" alt="retirement_titles" src="https://user-images.githubusercontent.com/99691015/162566817-8c1c2757-7bb9-42b6-b313-fd8c5fbb861f.png">

Because some employees may have multiple titles in the database, e.g. due to promotion, the DISTINCT ON statement was used to list employees with their most recent title. 

<img width="375" alt="unique_titles" src="https://user-images.githubusercontent.com/99691015/162566844-e257fceb-48c2-4722-9411-4f2afe525245.png">

### DELIVERABLE 2:

To develop a potential mentor program where a soon-to-retire employee would mentor a less experienced associate to pass on skills, an analysis was conducted to identify potential associates eligible to participate in such a mentorship program. This would help pitch the program to senior management. The results are shown below. 

<img width="600" alt="mentor_eligibility pny" src="https://user-images.githubusercontent.com/99691015/162567013-e125c04a-f8d4-436a-9279-ace0a78819db.png">

## CONCLUSIONS:
Major conclusions:
- There are a lot of employees who are close to retirement (>90,000!), i.e. there will certainly be a ‘silver tsunami’.
- About 64% of those eligible to retire have the word “Senior” in their title, i.e. there will be enough qualified employees to help design and rive a=n effective mentorship program. [Total = 90,398, “Senior” in title = 29414 + 28254 = 57,668 = 64%!!]
- By identifying who these mentor-eligible associates are by title, the magnitude of this impending problem can be clearly communicated to senior management. 

<img width="563" alt="Group_by_tilte" src="https://user-images.githubusercontent.com/99691015/162567087-d0017eeb-93d4-43ab-aa6f-0c9890a78a12.png">
