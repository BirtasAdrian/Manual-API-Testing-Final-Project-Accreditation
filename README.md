## Acest repository conţine proiectul meu final de testare manuală pentru acreditare

Proiectul final constă în testarea unui API. 

API Swagger Petstore este un API în care se pot insera, modifica sau sterge animale în baza de date a unui magazin pentru animale. Acest API are posibilitatea de a face acelaş lucru şi pentru comenzi sau useri. În cadrul proiectului final am ales să testez modulul API-ului în care se pot insera, modifica sau şterge animalele în baza de date a magazinului.

 #### Documentaţia API-ului: https://petstore.swagger.io

Ca şi tool de testare API am ales să folosesc Postman.

În secţiunea Authorization se va folosi pentru fiecare test ca şi API Key: special-key

## Testele realizate

**Adăugarea unui nou animal în magazin**

Metoda HTTP pentru request: POST

Animal introdus în petstore prin cod JavaScript în secţiunea Body

Status cod de răspuns: 200 OK

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/b76606bc-adcd-4b48-a9e0-9a66cd24091d)

-----------------------------------------

**Adăugarea unui nou animal în magazin cu un id general -1**

Metoda HTTP pentru request: POST

Animal introdus în petstore prin cod JavaScript în secţiunea Body

Status cod de răspuns: 200 OK

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/ef9efbd4-cbbb-417c-b5d3-439ab0d2b7bc)

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

Animal şters prin introducerea id-ului său 2 în endpoint

Status cod de răspuns: 404 Not Found

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/3752c286-c300-48a1-8f22-6dc1150c8976)






