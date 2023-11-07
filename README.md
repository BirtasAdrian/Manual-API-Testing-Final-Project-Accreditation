## Acest repository conţine proiectul meu final de testare manuală pentru acreditare

Proiectul final constă în testarea unui API. 

API Swagger Petstore este un API în care se pot insera, modifica sau sterge animale în baza de date a unui magazin pentru animale. Acest API are posibilitatea de a face acelaş lucru şi pentru comenzi sau useri. În cadrul proiectului final am ales să testez modulul API-ului în care se pot insera, modifica sau şterge animalele în baza de date a magazinului.

 #### Documentaţia API-ului: https://petstore.swagger.io

Ca şi tool de testare API am ales să folosesc Postman.

În secţiunea Authorization se va folosi pentru fiecare test ca şi API Key: special-key

## Testele realizate

**Adăugarea unui nou animal în magazin**

Metoda HTTP pentru request: POST

Animal introdus în petstore prin secţiunea Body-raw din Postman cu ajutorul dicţionarului din documentaţie 

Status cod de răspuns: 200 OK

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/33032aea-1fe3-45a1-9aa4-27790c1f7b5a)

***Teste JavaScript:***

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/396a9636-c894-4b71-8c06-6c7ff74212f1)

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/1ffc3cac-9d26-4cd1-94e8-3859f9804e15)

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/91c88cf2-2a57-43fe-8160-51a7fb190a19)

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/d0fb3091-7c20-4838-8cc3-64c83c7659a9)


-----------------------------------------

**Adăugarea unui nou animal în magazin cu un id general -1**

Metoda HTTP pentru request: POST

Animal introdus în petstore prin secţiunea Body-raw din Postman cu ajutorul dicţionarului din documentaţie 

Status cod de răspuns: 200 OK

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/27150510-30d4-4967-8478-1452d1be9c35)

***Teste JavaScript:***

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/2974101d-e693-4d88-9912-412752d74b6d)

-----------------------------------------
**Adaugărea unui animal în magazin cu un id la categorie de tip string "caine"**

Metoda HTTP pentru request: POST

Animal introdus în petstore prin secţiunea Body-raw din Postman cu ajutorul dicţionarului din documentaţie 

Status cod de răspuns: 500 Sever Error

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/09ef507d-3078-448a-b7bc-0066fbd430b9)

***Teste JavaScript:***

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/fb10e928-2b2a-4f10-aa2f-2b6b7e778354)

-----------------------------------------

**Adăugarea unui nou animal în magazin cu un număr la status**

Metoda HTTP pentru request: POST

Animal introdus în petstore prin secţiunea Body-raw din Postman cu ajutorul dicţionarului din documentaţie

Status cod de răspuns: 200 OK

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/ddb9be47-9baa-40cd-be83-ec53fd7abf5f)

***Teste JavaScript:***

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/4f70e514-7ab7-455a-ae4c-5b4d94367def)

-----------------------------------------

**Adăugarea unui nou animal în magazin cu un text la id pentru tags**

Metoda HTTP pentru request: POST

Animal introdus în petstore prin secţiunea Body-raw din Postman cu ajutorul dicţionarului din documentaţie

Status cod de răspuns: 500 Server Error

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/90eeb6b5-84cd-4296-b313-4e6f674e3cb5)

***Teste JavaScript:***

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/82e474b7-d4ae-43f4-a6cd-b982deaf22f7)

-----------------------------------------

**Actualizarea datelor unui animal existent în baza de date**

Metoda HTTP pentru request: PUT

Animal actualizat în petstore prin secţiunea Body-raw din Postman cu ajutorul dicţionarului din documentaţie

Status cod de răspuns: 200 OK

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/b18df86d-9101-41cf-a77a-d2d599ff5929)

***Teste JavaScript:***

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/445ab2d2-7a8f-4a71-86f0-5f056451c18e)

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/b45886a2-0ac7-45e8-9226-a04504ca5bb5)

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/bdc274d9-602a-47b4-93fe-dc19b8d78951)


-----------------------------------------

**Actualizarea datelor unui animal existent în baza de date cu un nume de 25 de caractere pentru specie**

Metoda HTTP pentru request: PUT

Animal actualizat în petstore prin secţiunea Body-raw din Postman cu ajutorul dicţionarului din documentaţie

Status cod de răspuns: 200 OK

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/ce6dd5db-b761-402a-a67f-2cde05eb1b8e)

***Teste JavaScript:***

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/f293a766-ebef-45ee-8554-b7d2205ba06f)


-----------------------------------------

**Actualizarea datelor unui animal existent cu un id pentru categorie de 19 cifre**

Metoda HTTP pentru request: PUT

Animal actualizat în petstore prin secţiunea Body-raw din Postman cu ajutorul dicţionarului din documentaţie

Status cod de răspuns: 200 OK

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/88605c95-cc7a-4a60-81c6-7ce6cd605cdd)

***Teste JavaScript:***

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/6ec2ad2b-6f1b-4713-97b8-3e06a12b1482)

-----------------------------------------

**Găsirea unui animal după id**

Metoda HTTP pentru request: GET

Animal găsit prin introducerea id-ului său 2 în endpoint

Status cod de răspuns: 200 OK

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/9fefd78d-dde9-43ea-aade-5c911411e7ec)

***Teste JavaScript:***

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/645f20a4-028b-451c-a4f7-2a37e8b12114)

-----------------------------------------

**Găsirea unui animal după un id negativ**

Metoda HTTP pentru request: GET

Animal negăsit prin introducerea id-ului său -2 în endpoint

Status cod de răspuns: 404 Not Found

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/a53f902b-97be-4e85-a9c0-65528ee2c8de)

***Teste JavaScript:***

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/f92355b1-3dfd-4851-ad63-dd7e53cdc1f0)

-----------------------------------------

**Ştergerea unui animal după id**

Metoda HTTP pentru request: DELETE

Animal şters prin introducerea id-ului său 2 în endpoint

Status cod de răspuns: 200 OK

Notă: Ca şi improvement ar fi bine să se adauge de către developeri un mesaj de confirmare corespunzător "Pet Deleted"

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/915ef1b6-8bb5-4110-9c1f-73a119b44f6f)

***Teste JavaScript:***

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/e2ec92b3-8e96-42c1-9884-97c0f12462b1)


-----------------------------------------

**Ştergerea unui animal după id negativ**

Metoda HTTP pentru request: DELETE

Animal şters prin introducerea id-ului său -2 în endpoint

Status cod de răspuns: 404 Not Found

Notă: Ca şi improvement ar fi bine să se adauge de către developeri un mesaj corespunzător de eroare "Pet not found"

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/666392aa-67cb-445f-b39a-92722ecbd442)

***Teste JavaScript:***

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/64b16e25-973f-4afb-8d4c-d7b1434f858e)


-----------------------------------------

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
3. Se introduce în Header dicţionarul specific din documentaţie din secţiunea pet pentru POST:
https://petstore.swagger.io
4. Se apasă butonul Send de 2 ori

**Rezultat Aşteptat:**
Nu se va putea insera mai mult de un animal cu acelaşi id, codul 405 invalid input va apărea

**Rezultat Actual:**
Se poate insera mai mult de un animal cu acelaşi id, codul 200 ok apare


