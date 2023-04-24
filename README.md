# SoftwareEngineering-

a)	The project would follow an Agile development method, with one-week sprints,
The project is a short and not too complex project, four weeks long, so we believe that using an Agile approach is the most suitable for the project allowing us to review with the customer and deliver value at the end of every sprint re-assessing the requirements as needed.
As the security of the project is one of the most important aspects in this project we would put focus on it by developing our own security system and relying on third party software for network and performance monitoring. 

b)	
•	Requirements gathering:
In this phase we would gather the requirements by having meetings with the client and by investigating different systems that try to accomplish similar core requirements.

•	Analysing requirements:
In this phase we would analyse the requirements and try to assess their value and how accomplishable those are and planning the user stores for the sprints.

•	Design:
In this phase we would design and plan which are the more suitable technologies to carry out the project, as well we would sketch user interfaces, use case diagrams, class models and the overall architecture for the project.

•	Develop:
In this phase we would develop the software adding unit test to test the functionality of the code.

•	Test:
In this phase we would perform black-box manual testing to check that the software meets the requirements, as well performance and integration tests but we would put focus on security tests because of the importance of security in this particular project.

•	Deploy:
In this phase we would deploy the system on the servers that would hold the system

•	Maintenance:
In this phase that would be ongoing from the first sprint we would try to improve performance and security of previous sprints, as well offer support and training to the client in using the system.

c)	
•	Functional requirements:

	The user should be able to login into their account.

	The user should be able to check their account balance.

	The user should be able to deposit checks and cash into their account.

	The user should be able to withdraw cash.

	The user should be able to perform any operation at any time.


•	Interface requirements:

	The interface should be easy to use for users with any background.

	The contrast in the colours should be high to facilitate the task at any light condition and make the task easier for people all ages and as well disabled people.

	The buttons should be big and the UI/UX design compressive and as simple as possible. 


•	Infrastructure requirements:

	The server should be hold and planned having redundancy of data and access to services at all time in mind.

	The network should be encrypted and secure at times.

	The server room area should be restricted to as little people as possible.

	The performance and security of the system and network should be monitored at all times.

d)	Use case diagram

 ![Blank diagram](https://user-images.githubusercontent.com/87866314/233974954-aa6a2d3b-2cf3-44aa-a412-013ec87169d8.png)

e)	

First sprint:
	The user should be able to login into their account.
	The user should be able to check their account balance.

Second sprint: 
	The user should be able to deposit checks and cash into their account.
Third sprint:
	The user should be able to withdraw cash.

Since we consider security and reliability the most important aspects of this project the last week of the development process would be used to perform more thorough tests,
Including integration, performance, penetration tests user tests. 
While delivering the software on every sprint we would like to include user testing to analyse how users with different backgrounds and experiences interact with the software.

f)	

•	Main class
•	Login
After login
•	Show balance (sends a get request for the balance)
•	Deposit (checks the amount and sends a deposit request to add that amount to the balance if the request is successful add the money into the account)
•	Withdraw (sends a request to withdraw the money from the account if the request is successful the money is expended it, if the money is expended it correctly the amount is taking from the account) 
•	Logout



The data models should include 

User: 	
- id
- password
- UserDetails	
- AccountNumber
	
 Account:	
-	AccountNumber
-	Balance 
-	DisplayBalance method
-	Deposit method
-	Withdraw method

UserDetails:
- Name
- Address
- Birth date
- PPSN

g)	

•	Validation: For the validation we would conduct user testing and observe how the users interact with the system and that the UI/UX design are understandable for users of all ages and backgrounds. As well that the project meets all the demands from the requirements.

•	Verification: We would use peer review on all the instances of the project and perform pen testing to make sure that the security meets all the standards and improve to the security of the project in general. As well to check the scalability and maintainability of the project in general.
