# Detective-SQL
![image](https://github.com/iamasprout/Detective-SQL/assets/114030254/2dfae36d-7c59-4fd4-af1e-85e043108181)
## Case Study
A crime has taken place and the detective needs your help. The detective gave you the crime scene report, but you somehow lost it. You vaguely remember that the crime was a murder that occurred sometime on Jan.15, 2018 and that it took place in SQL City. Start by retrieving the corresponding crime scene report from the police department’s database.
## Data
Follow these steps to solve this challenge:

Download the sql-murder-mystery.db file [here](https://drive.google.com/drive/folders/1SLlSSzIqhu9m4p8HmoJYjn5X_GTYdDsf?usp=share_link)
Visit www.sqliteonline.com
Click on file, then open db and load in the database file you downloaded above
Write your SQL queries to see the different tables and the content
## Tools
SQLiteonline.com
## Entity Relationship Diagram
Since We are analysing with SQL it is best that we know the relationship between our tables.
we can always get that. I Published  a document concerning that you can read up [here](https://medium.com/@olumayowaoyeyinka/how-to-generate-an-er-diagram-for-a-database-in-mysql-workbench-658c077bfef0)

![schema (2)](https://github.com/iamasprout/Detective-SQL/assets/114030254/e12f0dd1-bf7a-4e8e-bf6a-7bd733634600)

## Analysis
We need to note the some few things;
* Date was on Jan.15, 2018.
* Location was SQL City. 
#### Firstly checking if the details exist in the database
![image](https://github.com/iamasprout/Detective-SQL/assets/114030254/4aba20a1-cdd0-47e8-b70d-757b079adaf9)

since it does i would love to know the description

_Security footage shows that there were 2 witnesses. The first witness lives at the last house on "Northwestern Dr". The second witness, named Annabel, lives somewhere on "Franklin Ave"._

So with this lead i need to get to the two witness 
the first witness

![image](https://github.com/iamasprout/Detective-SQL/assets/114030254/8c400d74-be65-45e0-9de0-dc99a7b440e5)

the second witness 

![image](https://github.com/iamasprout/Detective-SQL/assets/114030254/087c6174-4bd3-4a94-93f5-a1eacf0392b7)

##### the next thing i decided to do was to check the witnesses account

![image](https://github.com/iamasprout/Detective-SQL/assets/114030254/552c51ac-07cd-4550-87a7-489fad21d543)

the first witness said

_I heard a gunshot and then saw a man run out. He had a "Get Fit Now Gym" bag. The membership number on the bag started with "48Z". Only gold members have those bags. The man got into a car with a plate that included "H42W"._

Second said:

_I saw the murder happen, and I recognized the killer from my gym when I was working out last week on January the 9th._

Since they were both related to gym i decided to go futher to investigate the first witness account

![image](https://github.com/iamasprout/Detective-SQL/assets/114030254/4bfcd573-bbb6-4f45-9649-3bc40bab1605)

we are getting close to knowing who the murderer is but we can't just nail him based on one witness when we have two let's confirm if it mattches the other witness report

![image](https://github.com/iamasprout/Detective-SQL/assets/114030254/e448bee4-97be-486c-8edf-b751e36f62b7)

so i need to check if the two witnessess account matches

![image](https://github.com/iamasprout/Detective-SQL/assets/114030254/26266399-b48a-4e1a-b16a-4bba22acb63f)\

so finally we can say the killer if _**Jeremy Bowers**_

Never imagined this. He was already interviewed and he confessed to the Murder

![image](https://github.com/iamasprout/Detective-SQL/assets/114030254/51e899da-03b4-438c-895c-a673de0bee6c)

Saying 
_I was hired by a woman with a lot of money. I don't know her name but I know she's around 5'5" (65") or 5'7" (67"). She has red hair and she drives a Tesla Model S. I know that she attended the SQL Symphony Concert 3 times in December 2017.
_

so we need to get the woman that hired Jeremy .

![image](https://github.com/iamasprout/Detective-SQL/assets/114030254/b0b38f6e-da4b-418c-899d-18bd86036da8)

While we already know the killer we now get to know the person that hired him was _**Miranda Priestly**_

and according to jeremy i decided to go futher to check hoe rich she was and lo and behold she was part of the top 50 Richest in SQL City to be precise she is the 47 richest person in the city.

If you're able to follow along or like it here please do give a star and follow me on [Linkedin](https://www.linkedin.com/in/olumayowa-oyeyinka-33ba29272/) ,[Medium](https://medium.com/@olumayowaoyeyinka) and [Twitter](https://twitter.com/oyeyinka_mayowa?t=6mlZ2rG0oDKErJW5LgNzHQ&s=09)












