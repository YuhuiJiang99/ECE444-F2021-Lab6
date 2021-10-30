# ECE444-F2021-Lab6

## Replaying TDD Example
Please refer to project/screenshots for the results of every step in the replaying example: https://github.com/mjhea0/flaskr-tdd.

## TDD Pros&Cons
Pros:
1. Ensure product quality. TDD makes sure that every single functionality and feature involved in the application is checked by a test case before getting into production phase. With the help of TDD, lots of potential bugs and logical problems can be detected during the development phase. 
2. Makes code easier to maintain and refactor. TDD helps to provide clarification and safety check when we need to modify or expand our codes during the implementation process. 
3. Makes team collaboration easier and more efficient. TDD asks each team member to generate corresponding test cases and logs when trying to merge codes into the development branch. It not only provides the basic safety check for code merging but also enables team members to edit each other's code with confidence since tests can be utilized to check if the changes are generating any unexpected effect.
4. Forces good architecture design. In order to perform unit-test, we must split the application into several modules. Thus, the application can have a clean structure, which improves its scalability and maintainability.

Cons:
1. Delays the development lifecycle. Additional workload and time cost is inevitable for every team member to learn, generate, and maintain various test cases during the implementation process. 
2. Can't find bugs in the test case itself. While the test case can be designed to check the application functionality, we can't guarantee that it has any potential bugs or misses any corner case check.
3. Introduce communication complexity in the team cooperation. In addition to explaining the functionalities and features to the team, every team member has to demonstrate the use of their corresponding test cases and expected outputs, which can result in some misconception. 
4. Increase the size of the application.
