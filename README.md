## This repository contains my final project on manual testing for the Programmer's Assistant accreditation 

The final project is testing an API.

The Swagger Petstore API is an API where you can insert, view, modify, or delete animals in a pet store's database. This API can do the same for orders or users. In the final project, I chose to test the API module where you can insert, view, modify, or delete animals in the pet shop database. This will also include writing Java Script tests.

 #### API Documentation: [Documentaţie](https://petstore.swagger.io)
 
For the API testing tool, I chose to use Postman.

In the Authorization section, it will be used for each test as API Key: special-key

Collection link: [Test Collection](https://www.postman.com/winter-robot-829234/workspace/petstore/collection/16723409-2ca90359-b93c-4898-b810-404229196dd7?action=share&creator=16723409)
  
## Tests performed

**1. Adding a new animal to the shop**

HTTP method for request: POST

An animal was inserted in the petstore via the Body-raw section of Postman using the dictionary from API documentation. 

Response code status: 200 OK

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/33032aea-1fe3-45a1-9aa4-27790c1f7b5a)

***JavaScript Tests:***

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/396a9636-c894-4b71-8c06-6c7ff74212f1)

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/1ffc3cac-9d26-4cd1-94e8-3859f9804e15)

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/91c88cf2-2a57-43fe-8160-51a7fb190a19)

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/d0fb3091-7c20-4838-8cc3-64c83c7659a9)


-----------------------------------------

**2. Adding a new animal to the store with a general id -1**

HTTP method for request: POST

An animal was inserted in the petstore via the Body-raw section of Postman using the dictionary from API documentation. 

Response code status: 200 OK

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/27150510-30d4-4967-8478-1452d1be9c35)

***JavaScript Tests:***

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/2974101d-e693-4d88-9912-412752d74b6d)

-----------------------------------------
**3. Adding an animal to the shop with a category id of string type "dog"**

HTTP method for request: POST

An animal was not inserted in the petstore via the Body-raw section of Postman using the dictionary from API documentation. 

Response code status: 500 Server Error

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/56fc176a-8cab-430b-b942-8a6a7c678b26)

***JavaScript Tests:***

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/2f686d08-572f-4d6a-82d7-b9615b1c4eae)


-----------------------------------------

**4. Adding a new animal to the shop with a status number**

HTTP method for request: POST

An animal was inserted in the petstore via the Body-raw section of Postman using the dictionary from API documentation. 

Response code status: 200 OK

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/ddb9be47-9baa-40cd-be83-ec53fd7abf5f)

***JavaScript Tests:***

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/f738d279-332d-42c0-a34c-3d777a77eeb9)

-----------------------------------------

**5. Adding a new animal to the shop with a text id for tags**

HTTP method for request: POST

An animal was not inserted in the petstore via the Body-raw section of Postman using the dictionary from API documentation. 

Response code status: 500 Server Error

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/b7287e7d-01fb-4086-ba5f-98f8b06b333d)


***JavaScript Tests:***


![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/76dc1aab-609b-4911-a0c7-ebce43b51d36)

-----------------------------------------

**6. Updating the data of an existing animal in the database**

HTTP method for request: PUT

Animal updated in petstore via Body-raw section in Postman using dictionary from API documentation

Response code status: 200 OK

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/b18df86d-9101-41cf-a77a-d2d599ff5929)

***JavaScript Tests:***

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/445ab2d2-7a8f-4a71-86f0-5f056451c18e)

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/b45886a2-0ac7-45e8-9226-a04504ca5bb5)

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/bdc274d9-602a-47b4-93fe-dc19b8d78951)


-----------------------------------------

**7. Update the data of an existing animal in the database with a 25-character species name**

HTTP method for request: PUT

Animal updated in petstore via Body-raw section in Postman using dictionary from API documentation

Response code status: 200 OK

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/ce6dd5db-b761-402a-a67f-2cde05eb1b8e)

***JavaScript Tests:***

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/f293a766-ebef-45ee-8554-b7d2205ba06f)


-----------------------------------------

**8. Update the data of an existing animal with a 19-digit category id**

HTTP method for request: PUT

Animal updated in petstore via Body-raw section in Postman using dictionary from API documentation

Response code status: 200 OK

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/88605c95-cc7a-4a60-81c6-7ce6cd605cdd)

***JavaScript Tests:***

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/6ec2ad2b-6f1b-4713-97b8-3e06a12b1482)

-----------------------------------------

**9. Finding an animal by id**

HTTP method for request: GET

Animal found by entering its id 2 in the endpoint

Response code status: 200 OK

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/9fefd78d-dde9-43ea-aade-5c911411e7ec)

***JavaScript Tests:***

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/645f20a4-028b-451c-a4f7-2a37e8b12114)

-----------------------------------------

**10. Finding an animal by a negative id**

HTTP method for request: GET

Animal not found by entering id -2 in the endpoint

Response code status: 404 Not Found

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/a53f902b-97be-4e85-a9c0-65528ee2c8de)

***JavaScript Tests:***

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/f92355b1-3dfd-4851-ad63-dd7e53cdc1f0)

-----------------------------------------

**11. Deleting an animal by id**

HTTP method for request: DELETE

Animal deleted by entering its id 2 in the endpoint

Response code status: 200 OK

Note: As an improvement, it would be good if the developer would add an appropriate "Pet deleted" confirmation message.

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/915ef1b6-8bb5-4110-9c1f-73a119b44f6f)

***JavaScript Tests:***

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/e2ec92b3-8e96-42c1-9884-97c0f12462b1)


-----------------------------------------

**12. Deleting an animal by negative id**

HTTP method for request: DELETE

The animal was not deleted by entering its id -2 in the endpoint

Response code status: 404 Not Found

Note: As an improvement, it would be good if the developers would add a corresponding error message "Pet not found"

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/666392aa-67cb-445f-b39a-92722ecbd442)

***JavaScript Tests:***

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/64b16e25-973f-4afb-8d4c-d7b1434f858e)


-----------------------------------------

Running the Pet collection, the one in which I conducted the above tests

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/773cf709-bf3a-4724-a381-8b006745c72b)

Execution report 

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/5e192f86-7f72-4b00-8ee2-81e8fc72ba9c)

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/6a012d68-bf4c-4056-bdf2-43058e967551)

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/72a63f04-b9a7-4977-a6c5-978e0c3ce6af)

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/961423a3-c41f-4b79-881a-e1b840cac097)

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/4d7e9db6-e39c-485a-adc8-95f1cf066968)

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/e22ffe18-3502-43f7-9b8a-ee70529f9a69)


**Bugs found**

**Bug Id:** 1

**Title:** Inserting multiple animals with the same id is possible

**Severity:** High

**Preconditions:** Use API Key: special-key in Authorization

**Steps:**
1. Use HTTP POST method
2. Enter the endpoint: https://petstore.swagger.io/v2/pet
3. Enter and fill in the Body-raw specific dictionary from the API documentation in the pet section for POST:
https://petstore.swagger.io
4. Press the "Send" button twice

**Expected Result:**

It will not be possible to insert more than one animal with the same id, code 405 invalid input will appear

**Actual Result:**

You can insert more than one animal with the same id, code 200 ok appears

-----------------------------------------
**Bug Id:** 2

**Title:** Inserting an animal with a status number is possible

**Severity:** Medium

**Preconditions:** Use API Key: special-key in Authorization

**Test Data:**: 5

**Steps:**
1. Use HTTP POST method
2. Enter the endpoint: https://petstore.swagger.io/v2/pet
3. Enter in Body-raw the specific dictionary from the documentation in the pet section for POST:
https://petstore.swagger.io
4. Fill in "Status" with 5
5. Press the "Send" button
 
**Expected Result:**

It will not be possible to insert an animal with the status of type number

**Actual Result:**

Can insert an animal with status type number

-----------------------------------------

**Bug Id:** 3

**Title:** Inserting an animal with a negative id generates an animal with id 9223372036854775807

**Severity:** Medium

**Preconditions:** Use API Key: special-key in Authorization

**Test Data:**: -1

**Steps:**
1. Use HTTP POST method
2. Enter the endpoint: https://petstore.swagger.io/v2/pet
3. Enter in Body-raw the specific dictionary from the documentation in the pet section for POST:
https://petstore.swagger.io
4. Fill in "id" with -1
5. Press the "Send" button

**Expected Result:**

An id should not be generated at all for a negative number but an error and a corresponding status code should appear

**Actual Result:**

Id 9223372036854775807 is generated and the status code is 200 OK

-----------------------------------------

**Bug Id:** 4

**Title:** Adding text to the id for tags results in a status code 500 Server Error "type" unknown

**Severity:** Medium

**Preconditions:** Use API Key: special-key in Authorization

**Test Data:**: Bubu

**Steps:**
1. Use HTTP POST method
2. Enter the endpoint: https://petstore.swagger.io/v2/pet
3. Enter in Body-raw the specific dictionary from the documentation in the pet section for POST:
https://petstore.swagger.io
4. Fill in the "id" tags with Bubu
5. Press the "Send" button

**Expected Result:**

We should get a 400 series status code and an error message

**Actual Result:**

We receive a 500 series status code related to server error

-----------------------------------------

**Bug Id:** 5

**Title:** Adding text to the id for the category results in a status code 500 Server Error "type" unknown

**Severity:** Medium

**Preconditions:** Use API Key: special-key in Authorization

**Test Data:**: Caine

**Steps:**
1. Use HTTP POST method
2. Enter the endpoint: https://petstore.swagger.io/v2/pet
3. Enter in Body-raw the specific dictionary from the documentation in the pet section for POST:
https://petstore.swagger.io
4. Fill in "id" category with Caine
5. Press the "Send" button

**Expected Result:**

We should get a 400 series status code and an error message

**Actual Result:**

We receive a 500 series status code related to server error

-----------------------------------------
**Conclusions**

* 12 requests were sent and 46 JavaScript tests were executed, of which only 42 were successfully executed
* 91.3% of tests passed and 8.7% failed
* 5 bugs were found and reported, one of high severity and 4 of medium severity
* We have a high risk because the database allows multiple insertions on the same animal id
  

