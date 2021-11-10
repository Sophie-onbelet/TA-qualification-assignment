
**TEST SCENARIOS DEMOQA (UI)**

**Scenario 1. Check the Category Forms**<br />
(https://demoqa.com/forms) Demoqa is a website designed to practice test automatisation. The categories (Elements, Forms, Alerts, Frame & Windows, Widgets, Interactions) are the core functionality of this demo website. The Forms category is one the of most time consuming to test, since it include multiple fields with several input options. Therefore I chose to automate this scenario.  

Test cases<br />
TC1. Fill in the fields according to the requirements<br />
TC2. Fill in the fields with the minimum requirement<br />
TC3. Fill in the fields with the maximum requirements <br />
TC4. Fill in the fields with more/less than minimum/maximum requirements<br />
TC5. Leave mandatory fields blank<br />
TC6. Fill in fields with invalid values<br />

**Scenario 2. Check the internal and external linking**   <br />
Links that work correctly are necessary to access the core functionality of the demo website, the categories. Users use links to navigate on the website. Automated tests can make you aware of broken links or links that go to the wrong page. Executing this test manually would be time consuming. Therefore this is another scenario that is important to automate.

Test cases<br />
TC1. Check the Logo on the homepage<br />
TC2. Check the external links in the top menu<br />
TC3. Check the internal links of the category cards<br />
TC4. Check the buttons below the categories<br />

**Scenario 3. Check Book Store Application**<br />
This scenario includes multiple steps, from creating an account, to login, adding books to your Book Store and deleting your account. Automating these steps will help executing these tests faster and increase your test coverage.

Test cases<br />
TC1. Fill in the fields according to the requirements<br />
TC2. Fill in the fields with the minimum requirements<br />
TC3. Fill in the fields with the maximum requirements <br />
TC4. Fill in the fields with more/less than minimum/maximum requirements<br />
TC5. Leave mandatory fields blank<br />
TC6. Fill in fields with invalid values<br />
TC7. Fill username with already existing username<br />
TC8. Create account<br />
TC9. Attemped login with wrong username<br />
TC10. Attemped login with wrong password<br />
TC11. Login with credentials<br />
TC12. Add book(s) to your book store (maximum amount)<br />
TC13. Remove books<br />
TC14. Logout<br />
TC15. Remove account<br />

**Scenario 4. Check performance of the website**<br />
To execute proper load and stress test, you need to automate those tests. A good performance of the website is important for the user experience on the website. Therefore this is important to automate. 

Test cases <br />
TC1. Open the homepage<br />
TC2. Directing to the different categories (internal linking)<br />
TC3. Creating account in the Book Store Application<br />
TC4. Login/Logout<br />
TC5. Clicking on the external links<br />


**TEST SCENARIOS PETSTORE**

**Scenario 1. End-to-end processes**<br />
Check if you can add, update an existing pet and delete a pet to the store<br />
Check if you can find a pet by ID and/or status<br />
Check if order can be placed, can be found by ID and can be deleted<br />
Check if you can retrieve inventory by status<br />
Check if you can create a user, update an user and delete an user<br />
Check if user can log in and log out<br />
Check if you can find user by user name<br />
Check if user cannot access things they should not be able to<br />

These are the most critical end-to-end processes within this API. Focus on these are important to test the connectivity of the API and its response.
I want to validate the following:<br />
Validate status code<br />
Validate response<br />
Validate correct state<br />
Validate header<br />
Validate performance/ response time (stress and load tests)<br />

Automating this will faster and more accurate. Also you will be able to execute stress and load tests for the different scenarios to measure the performance. <br />

**Scenario 2. Check Invalid input**<br />
Execute the API requests but this time with incorrect data. 
 

**Scenario 3. Check security of the API**<br />
Make sure the end user cannot access things they should not be able to. This is business critical and you want this to be checked during the entire development process. Automating these checks can also simulate more security attacks for example. <br />

Test cases<br />
TC1. SQL injections<br />
TC2. Authentication<br />
TC3. Autorization<br />

**NEXT STEPS**<br />
The next steps after automating these scenarios, is creating a plan to maintain these test scenarios. They need to be reviewed and with any (code) changes the automated test should be updated as well. 
Also the test results need the be evaluated every time the tests are excuted and checked if a follow up action is necessary. 


