<h1>SPRITECLOUD CANDIDATE QUALIFICATION ASSIGNMENT</h1>

<h2>Given</h2>
<i>Required scripting language</i> </br>
As discussed in my first interview, I'm not yet able to create automated tests. Currectly I'm learing JS and Python, but my skills are basic.</br>
</br>

<i>Required testing tool</i> </br>
Since I have no experience in writing automated tests, I haven't used a testing tool before. I would use a tool that offers codeless options and supports different browsers, desktop and mobile for DEMOQA. 
For Pet Store API I would use Postman. This is an userfriendly tool. I have seen it before, but I haven't work individually with this tool. 

<i>CI Platform</i> </br>
Azure DevOps: you can manage your repository within this tool and create customizable pipelines. This is the only CI tool that I have experience with, I used to run the performance tests.


<h2>When</h2>
<h3>1. Most important scenario's to automate <b>DEMOQA</b></h3> </br>
<b>Scenario 1. Check the Category Forms</b><br />
(https://demoqa.com/forms) Demoqa is a website designed to practice test automatisation. The categories (Elements, Forms, Alerts, Frame & Windows, Widgets, Interactions) are the core functionality of this demo website. The Forms category is one the of most time consuming to test, since it include multiple fields with several input options. Therefore I chose to automate this scenario.  <br />
<br />
Test cases<br />
TC1. Fill in the fields according to the requirements<br />
TC2. Fill in the fields with the minimum requirement<br />
TC3. Fill in the fields with the maximum requirements <br />
TC4. Fill in the fields with more/less than minimum/maximum requirements<br />
TC5. Leave mandatory fields blank<br />
TC6. Fill in fields with invalid values<br />
<br />
<b>Scenario 2. Check the internal and external linking</b>   <br />
Links that work correctly are necessary to access the core functionality of the demo website, the categories. Users use links to navigate on the website. Automated tests can make you aware of broken links or links that go to the wrong page. Executing this test manually would be time consuming. Therefore this is another scenario that is important to automate.<br />
<br />
Test cases<br />
TC1. Check the Logo on the homepage<br />
TC2. Check the external links in the top menu<br />
TC3. Check the internal links of the category cards<br />
TC4. Check the buttons below the categories<br />
<br />
**Scenario 3. Check Book Store Application**<br />
This scenario includes multiple steps, from creating an account, to login, adding books to your Book Store and deleting your account. Automating these steps will help executing these tests faster and increase your test coverage.
<br />
<br />
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
<br />

**Scenario 4. Check performance of the website**<br />
To execute proper load and stress test, you need to automate those tests. A good performance of the website is important for the user experience on the website. Therefore this is important to automate. 
<br />
<br />
Test cases <br />
TC1. Open the homepage<br />
TC2. Directing to the different categories (internal linking)<br />
TC3. Creating account in the Book Store Application<br />
TC4. Login/Logout<br />
TC5. Clicking on the external links<br />
<br />
<h3>1. Most important scenario's to automate <b>PetStore</b> </h3></br>
<b>Scenarios</b><br />
1. Check if you can add, update an existing pet and delete a pet to the store<br />
2. Check if order can be placed, can be found by ID and can be deleted<br />
3. Check if you can create a user, update an user and delete an user<br />
4. Check if user can log in and log out<br />
<br />
I want to validate the following:<br />
Validate status code<br />
Validate response<br />
Validate correct state<br />
Validate header<br />
Validate performance/ response time (stress and load tests)<br />
<br />
These are the most critical end-to-end processes within this API. Focus on these are important to test the connectivity of the API and its response.
Automating this will faster and more accurate. Also you will be able to execute stress and load tests for the different scenarios to measure the performance. <br />
<h3>2. x </h3></br>
<h3>3. x </h3></br>
<h3>4. x </h3></br>
<h3>5. x </h3></br>
<h3>6. x </h3></br>
<h3>7.</h3> a. x<br />
b. x <br />
c. x <br />
d. <i>What did you use to select the scenarios, what was your approach?</i><br />
DEMOQA: first I analysed and explored the website. What is the purpose? This website is used as a demo website for automated tests. Therefore it is important that the categories should work, this is the main function. Since UI testing is required, I also wanted to focus on the usability.<br />
PetStore: first I analysed and explored the API. What are the main activities. Based on that I selected the most important scenarios. Scenarios are based core activities on the website<br />
<br />
e. <i>Why are the scenarios the most important</i><br />
See description below each scenario.<br />
<br />
f. <i>Next steps</i><br />
The next steps after automating these scenarios, is creating a plan to maintain these test scenarios. They need to be reviewed and with any (code) changes the automated test should be updated as well. 
Also the test results need the be evaluated every time the tests are excuted and checked if a follow up action is necessary. 
Furthermore, more tests can be added. For the Petstore for example, it is also important to focus on security testing; making sure that  the end user cannot access things they should not be able to. This is business critical and you want this to be checked during the entire development process. Automating these checks can also simulate more security attacks for example.


