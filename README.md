Self: Zack Roland 

1. Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.
Option 1. The whole point of automated tests is so that they run automatically and often to ensure the quality of your code. Having these tests within a Github action will that runs whenever code is pushed will allow is to maintain code quality in the long run.

2. Would you use an end to end test to check if a function is returning the correct output?
The point of End-to-end testing is to automate tests cases that involve emulating user actions. To this end it may not be efficent to use E2E testing to check if a function is returning the correct output because that is not necessarily user action focused.

3. Navigation mode simulates a full page reload while snapshot mode takes in the page at its current state. They both have their uses in regards to E2E testing though. Navigation mode allows us to audit user experiences upon coming into the page and snapshot allows us to see that is going on at certain moments of the users experience.

4. Name 3 things we could do to improve the CSE110 shop site based on lighthouse results
    1. Based on lighthouse results we can improve our accessibility by having a lang attribute in our html.
    2. Based on lighthouse results we can improve our SEO score by having a meta description to enable crawlers to better understand our content
    3. Based on lighthouse results we can improve our performance by taking care for proper image display



