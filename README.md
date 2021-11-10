**Test plan DEMOQA**
This test plan includes the most important scenarios to automate and why I chose them. I also advice for testing tool and the CI platform.  


**TEST SCENARIOS DEMOQA**

**Scenario 1. Check the Category**
Category Forms (https://demoqa.com/forms)
Demoqa is a website designed to practice test automatisation. The categories (Elements, Forms, Alerts, Frame & Windows, Widgets, Interactions) are the core functionality of this demo website. The Forms category is one the of most time consuming to test, since it include multiple fields with several input options. Therefore I chose to automate this scenario.  

Test cases
TC1. Fill in the fields according to the requirements
TC2. Fill in the fields with the minimum requirements
TC3. Fill in the fields with the maximum requirements 
TC4. Fill in the fields with more/less than minimum/maximum requirements
TC5. Leave mandatory fields blank
TC6. Fill in fields with invalid values

**Scenario 2. Check the internal and external linking**   
Links that work correctly are necessary to access the core functionality of the demo website: the categories. Users use links to navigate on the website. Automated tests can make you aware of broken links or links that go to the wrong page. Executing this test manually would be time consuming. 

Test cases
TC1. Check the Logo on the homepage
TC2. Check the external links in the top menu
TC3. Check the internal links of the category cards
TC4. Check the buttons below the categories

**Scenario 3. Check Book Store Application**
This scenario includes multiple steps, from creating an account, to login, adding books to your Book Store and deleting your account. Automating these steps will test coverage. 

Test cases
TC1. Fill in the fields according to the requirements
TC2. Fill in the fields with the minimum requirements
TC3. Fill in the fields with the maximum requirements 
TC4. Fill in the fields with more/less than minimum/maximum requirements
TC5. Leave mandatory fields blank
TC6. Fill in fields with invalid values
TC7. Fill username with already existing username.
TC8. Create account.
TC9. Attemped login with wrong username.
TC10. Attemped login with wrong password.
TC11. Login with credentials
TC12. Add book(s) to your book store (maximum amount).
TC13. Remove books.
TC14. Logout
TC15. Remove account.

**Scenario 4. Check performance of the website**
To execute proper load and stress test, you need to automate those tests. 

TC1. Open the homepage
TC2. Directing to the different categories (internal linking)
TC3. Creating account in the Book Store Application
TC4. Login/Logout
TC5. Clicking on the external links


**TEST SCENARIOS PETSTORE**

Scenario 1. Execute single API requests 
These are the basic steps of testing an API. If the test fails already, executing further steps is useless. Executing each step is time consuming and therefore a good scenario to automate. This is also a test which you want to run over and over again, after any chance, to check if nothing has broken down. Automating single API request is also easier to maintain. 

	- Validate status code
	- Validate response
	- Validate correct state 
	- Validate headers (security and performance) 
	- Validate performance

