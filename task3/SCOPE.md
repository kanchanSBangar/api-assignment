#✏️ Reflection on the automation exercise


###❗️ test scope

> In this task I have automated the CRUD operations of the SUT
> to cover the CRUD operations I decided to do System Testing <br>
> 

### ❗️ Possibility of automating these in different scope

> CRUD operation can be covered in unit test cases
> In order to do that we need to mock the response or
> use third party solutions such as `wiremock`
> As a QA I believe mocking should only be used in case there
> is a dependency on another WS which is not yet ready.
> 

PROS:
1) Unit tests are faster to execution thus quick feed back to developer on new changes
2) improves DEV code quality and bugs could be found in early stage


CONS: 
2) Unit Tests doesn't guarantee integration or system will work properly
3) QA sign-off on unit tests or mock tests is not .
> 
> Hence, I decided to use the System testing (E2E) tests as these are more reliable and 
> are the best candidate to give the QA sign-off.
