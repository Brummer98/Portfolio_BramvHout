# Testing FitOne

## Types of tests
Tests are divided into two different kinds: ***Functional testing*** and ***Non-functional testing***. 

| Functional  | Non functional  |
|---|---|
| Unit Testing | Performance Testing  |
| Integration Testing  | 	Load Testing  |
| Regression Testing  | Security Testing  |
| Acceptance Testing  | Usability Testing  |
| End to end testing  | Compatibility Testing  |

## What kind of testing would be useable for FitOne?

### Functional

#### Unit testing
Unit and integration testing seems like some solid options to begin my functional testing with.
With unit testing i can test all of the functions within my project on the front- and the backend.
So testing one function at the time and seeing the result.

###### Why Unit testing?
So test every single function within the project, for front- as for backend, seems like a solid thing to do.
Testing every function as is makes sure you don't skip ahead or leave the project with faulty functionalities. 
I think unit testing should be a standard test for every project.

#### Integration testing
With integration testing you're testing the entire flow of functionalities trough the project. 
So that could be interesting to see for showing the entire workflow.

###### Why integration testing?
Making use of an integration test and going trough the system part by part, seems like a good thing to do.
Because you're testing multiple components at the same time, for front- and backend and going trough bits of the system.
For testing the entire system, an ***End to end*** test also seems reasonable to me. But purely because i'm running out of time, i choose to do several integration
tests instead.

#### Regression testing
To see if the whole system still works fine after modifying one single component, is where the regression test is for.

###### Why regression testing?
It seems like a solid type of test for overal projects. I think it's quite logical to test the system this way, because during the deployment you might want to change
some code or functions within the project. So this kinde seems like a no-brainer to me.

### Non functional 

#### Performance testing
Performance tests are run to check if the software’s performance is good or not. 

###### Why performance testing?
Doing a performance test shows how strongly the application actually performs when going live. By doing this test you might find several flaws in your system, which
you can then fix to increase perfomance again. This seems like a reasonable non functional first test to do.

#### Security testing
Security tests are performed to ensure the security of your application, in order that security breaches can be prevented. Security experts run this kind of tests to see how much your software is secure from attacks and to find security issues so that the app’s security can be strengthened

###### Why security testing?
Seems like a no-brainer to me to test the security wihtin the FitOne project. Security is a very important part of the project because user's their personal data could
be thrown into the open, which we don't want to happen.

## Sources
https://fhict.instructure.com/courses/12517/pages/testing-what-when-and-where?module_item_id=835976

https://hackr.io/blog/types-of-software-testing

https://www.softwaretestinghelp.com/types-of-software-testing/
