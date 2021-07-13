# TEST PLAN:

##  High level test plan

| **Test ID** | **Description**                                              | **Expected Input** | **Expected Output** | **Actual Output** |**Type Of Test**  |    
|-------------|--------------------------------------------------------------|------------|-------------|----------------|------------------|
|  H_01       |Check if the User selects an option from the available choices, to perform the below actions such as find out the day ,print all the days of month,add note,exit.|User's choice, as an integer  | SUCCESS| SUCCESS|Requirement based |
|  H_02       |Check if the User selects an option from the available choices to enter date,month and year can check which day is occured on that date. |User's choice as an integer and alphabets  | SUCCESS| SUCCESS|Requirement based |
|  H_03       |If the user want to see all the days of the month then chech the available choice given below and proceed according to it    |User's choice as an integer and alphabets| PASS | SUCCESS|Requirement based |
|  H_04       |If the user want to check the year which is not there in our program then display that year does not exist |Display in a terminal| SUCCESS| SUCCESS|Technical |
|  H_05       |If the user want to add note choose the choice from below and after getting note we can perform some tasks|User's choice | SUCCESS| SUCCESS|Requirement based |
|  H_06       |Check after getting the note by pressing q we can quit the red background by pressing s we can see the note |User's choice | SUCCESS| SUCCESS|Requirement based  |
|  H_07       |If the user want to exit then check the choice from the below and exit from from the code  |User's choice | SUCCESS| SUCCESS|Requirement based  




## Low level test plan

| **Test ID** | **Description**                                              | **Expected Input** | **Expected Output** | **Actual Output** |**Type Of Test**  |    
|-------------|--------------------------------------------------------------|------------|-------------|----------------|------------------|
|  L_01       |When choosing from the available options, check if the input is valid or invalid|User's Choice| Invoke the process| SUCCESS|Scenario based |
|  L_02       |When user get the add note then  by clicking the p we will get to prevoius and by clicking n we will go to next. |User's choice| SUCCESS| SUCCESS|Scenario based    |
|  L_03       |Check the details of the program from which year to which year we can get acess| User's choice as an integer| PASS| SUCCESS|Scenario based    |
|  L_04       |If the Unknown year is provided |User's choice as an alphabets| Invalid Message| Invalid message|Scenario based    |

