## Acest repository conţine proiectul meu final de testare manuală pentru acreditare

Proiectul final constă în testarea unui API. 

API Swagger Petstore este un API în care se pot insera, modifica sau sterge animale în baza de date a unui magazin pentru animale. Acest API are posibilitatea de a face acelaş lucru şi pentru comenzi sau useri. În cadrul proiectului final am ales să testez modulul API-ului în care se pot insera, modifica sau şterge animalele în baza de date a magazinului.

 #### Documentaţia API-ului: https://petstore.swagger.io

Ca şi tool de testare API am ales să folosesc Postman.

În secţiunea Authorization se va folosi pentru fiecare test ca şi API Key: special-key

## Testele realizate

**Adăugarea unui nou animal în magazin**

Metoda HTTP pentru request: POST

Animal introdus în petstore în secţiunea Body-raw din Postman cu ajutorul dictionarului din documentatie 

Status cod de răspuns: 200 OK

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/33032aea-1fe3-45a1-9aa4-27790c1f7b5a)


-----------------------------------------

**Adăugarea unui nou animal în magazin cu un id general -1**

Metoda HTTP pentru request: POST

Animal introdus în petstore în secţiunea Body-raw din Postman cu ajutorul dictionarului din documentatie 

Status cod de răspuns: 200 OK

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/b9ef2657-b8f3-4197-8697-cf5b3b060079)

***Teste JavaScript:***

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/396a9636-c894-4b71-8c06-6c7ff74212f1)

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/1ffc3cac-9d26-4cd1-94e8-3859f9804e15)

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/91c88cf2-2a57-43fe-8160-51a7fb190a19)

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/755c6abd-ddb7-4311-acbd-160ca7287d86)


-----------------------------------------
**Adaugărea unui animal în magazin cu un id la categorie de tip string "caine"**

Metoda HTTP pentru request: POST

Animal introdus în petstore prin cod JavaScript în secţiunea Body

Status cod de răspuns: 500 Sever Error

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/d754f0e7-4482-4fe7-9ccd-9e92fb924ef6)

-----------------------------------------

**Adăugarea unui nou animal în magazin cu un număr la status**

Metoda HTTP pentru request: POST

Animal introdus în petstore prin cod JavaScript în secţiunea Body

Status cod de răspuns: 200 OK

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/90fe25ce-00bb-44fd-afeb-2d54c66bfce5)

-----------------------------------------

**Adăugarea unui nou animal în magazin cu un text la id pentru tags**

Metoda HTTP pentru request: POST

Animal introdus în petstore prin cod JavaScript în secţiunea Body

Status cod de răspuns: 500 Server Error

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/07a193b9-697b-4e64-83db-bbe16b420334)

-----------------------------------------

**Actualizarea datelor unui animal existent în baza de date**

Metoda HTTP pentru request: PUT

Animal actualizat în petstore prin cod JavaScript în secţiunea Body

Status cod de răspuns: 200 OK

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/6f3356e1-9195-4e8e-8ff2-b5e4ae24dede)

-----------------------------------------

**Actualizarea datelor unui animal existent în baza de date cu un nume de 25 de caractere pentru specie**

Metoda HTTP pentru request: PUT

Animal actualizat în petstore prin cod JavaScript în secţiunea Body

Status cod de răspuns: 200 OK

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/dc06df94-2b9f-46f5-825c-7c4c7ad2fb6f)

-----------------------------------------

**Actualizarea datelor unui animal existent cu un id pentru categorie de 20 de cifre**

Metoda HTTP pentru request: PUT

Animal actualizat în petstore prin cod JavaScript în secţiunea Body

Status cod de răspuns: 500 Server Error

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/7f832a86-70e8-4278-900d-9f5ee85b1e04)

-----------------------------------------

**Găsirea unui animal după id**

Metoda HTTP pentru request: GET

Animal găsit prin introducerea id-ului său 2 în endpoint

Status cod de răspuns: 200 OK

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/c332c912-2234-477e-ba3a-5c9e69548610)

-----------------------------------------

**Găsirea unui animal după un id negativ**

Metoda HTTP pentru request: GET

Animal negăsit prin introducerea id-ului său -2 în endpoint

Status cod de răspuns: 404 Not Found

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/a36858dc-93d3-4b6a-94c6-b7727d69bca0)

-----------------------------------------

**Ştergerea unui animal după id**

Metoda HTTP pentru request: DELETE

Animal şters prin introducerea id-ului său 2 în endpoint

Status cod de răspuns: 200 OK

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/b142f473-8021-461b-960e-b801d8828b65)

-----------------------------------------

**Ştergerea unui animal după id negativ**

Metoda HTTP pentru request: DELETE

Animal şters prin introducerea id-ului său -2 în endpoint

Status cod de răspuns: 404 Not Found

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/3752c286-c300-48a1-8f22-6dc1150c8976)


Rularea colecţiei Pet, cea în care am realizat testele de mai sus

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/ebd8ce82-10f6-4d09-b95f-e2967970969c)

Raportul de execuţie 

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/031d6306-cccb-494f-91b0-7004a58d4d7e)

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/4c74b96a-ab8f-4736-b85d-199aded2e51f)

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/9e65c3af-f1bb-437b-bbe8-334b0c14934d)


**Bug-uri găsite**

Bug Id: 1

**Titlu:** Inserarea mai multor animale cu acelaşi id este posibilă

**Precondiţii:** Se foloseşte API Key: special-key în Authorization

**Paşi de execuţie:**
1. Se foloseşte metoda HTTP POST
2. Se introduce endpoint-ul: https://petstore.swagger.io/v2/pet
3. Se introduce în Header codul JavaScript specific din documentaţie din secţiunea pet pentru POST:
https://petstore.swagger.io
4. Se apasă butonul Send de 2 ori

**Rezultat Aşteptat:**
Nu se va putea insera mai mult de un animal cu acelaşi id, codul 405 invalid input va apărea

**Rezultat Actual:**
Se poate insera mai mult de un animal cu acelaşi id, codul 200 ok apare


