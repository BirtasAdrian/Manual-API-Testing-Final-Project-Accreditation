## Acest repository conţine proiectul meu final de testare manuală pentru acreditare

Proiectul final constă în testarea unui API. 

API Swagger Petstore este un API în care se pot insera, modifica sau sterge animale în baza de date a unui magazin pentru animale. Acest API are posibilitatea de a face acelaşi lucru şi pentru comenzi sau useri. În cadrul proiectului final am ales să testez modulul API-ului în care se pot insera, modifica sau şterge animalele în baza de date a magazinului.

 #### Documentaţia API-ului: [Documentaţie](https://petstore.swagger.io)
 
Ca şi tool de testare API am ales să folosesc Postman.

În secţiunea Authorization se va folosi pentru fiecare test ca şi API Key: special-key

Link colecţie: [Colectia de teste](https://www.postman.com/winter-robot-829234/workspace/petstore/collection/16723409-2ca90359-b93c-4898-b810-404229196dd7?action=share&creator=16723409)
  
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

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/56fc176a-8cab-430b-b942-8a6a7c678b26)

***Teste JavaScript:***

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/2f686d08-572f-4d6a-82d7-b9615b1c4eae)


-----------------------------------------

**Adăugarea unui nou animal în magazin cu un număr la status**

Metoda HTTP pentru request: POST

Animal introdus în petstore prin secţiunea Body-raw din Postman cu ajutorul dicţionarului din documentaţie

Status cod de răspuns: 200 OK

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/ddb9be47-9baa-40cd-be83-ec53fd7abf5f)

***Teste JavaScript:***

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/f738d279-332d-42c0-a34c-3d777a77eeb9)

-----------------------------------------

**Adăugarea unui nou animal în magazin cu un text la id pentru tags**

Metoda HTTP pentru request: POST

Animal introdus în petstore prin secţiunea Body-raw din Postman cu ajutorul dicţionarului din documentaţie

Status cod de răspuns: 500 Server Error

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/b7287e7d-01fb-4086-ba5f-98f8b06b333d)


***Teste JavaScript:***


![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/76dc1aab-609b-4911-a0c7-ebce43b51d36)

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

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/773cf709-bf3a-4724-a381-8b006745c72b)

Raportul de execuţie 

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/5e192f86-7f72-4b00-8ee2-81e8fc72ba9c)

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/6a012d68-bf4c-4056-bdf2-43058e967551)

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/72a63f04-b9a7-4977-a6c5-978e0c3ce6af)

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/961423a3-c41f-4b79-881a-e1b840cac097)

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/4d7e9db6-e39c-485a-adc8-95f1cf066968)

![image](https://github.com/BirtasAdrian/Testare-Manuala-Proiect-Final-Acreditare/assets/90641668/e22ffe18-3502-43f7-9b8a-ee70529f9a69)


**Bug-uri găsite**

**Bug Id:** 1

**Titlu:** Inserarea mai multor animale cu acelaşi id este posibilă

**Severitate:** Mare

**Precondiţii:** Se foloseşte API Key: special-key în Authorization

**Paşi de execuţie:**
1. Se foloseşte metoda HTTP POST
2. Se introduce endpoint-ul: https://petstore.swagger.io/v2/pet
3. Se introduce şi completează în Body-raw dicţionarul specific din documentaţie din secţiunea pet pentru POST:
https://petstore.swagger.io
4. Se apasă butonul "Send" de 2 ori

**Rezultat Aşteptat:**

Nu se va putea insera mai mult de un animal cu acelaşi id, codul 405 invalid input va apărea

**Rezultat Actual:**

Se poate insera mai mult de un animal cu acelaşi id, codul 200 ok apare

-----------------------------------------
**Bug Id:** 2

**Titlu:** Inserarea unui animal cu un număr la status este posibilă

**Severitate:** Medie

**Precondiţii:** Se foloseşte API Key: special-key în Authorization

**Date de test:**: 5

**Paşi de execuţie:**
1. Se foloseşte metoda HTTP POST
2. Se introduce endpoint-ul: https://petstore.swagger.io/v2/pet
3. Se introduce în Body-raw dicţionarul specific din documentaţie din secţiunea pet pentru POST:
https://petstore.swagger.io
4. Se completează la "Status" cu 5
5. Se apasă butonul "Send"

**Rezultat Aşteptat:**

Nu se va putea insera un animal care sa aibă statusul de tip număr

**Rezultat Actual:**

Se poate insera un animal care sa aibă statusul de tip număr

-----------------------------------------

**Bug Id:** 3

**Titlu:** Inserarea unui animal cu un id negativ genereaza un animal cu id-ul 9223372036854775807

**Severitate:** Medie

**Precondiţii:** Se foloseşte API Key: special-key în Authorization

**Date de test:**: -1

**Paşi de execuţie:**
1. Se foloseşte metoda HTTP POST
2. Se introduce endpoint-ul: https://petstore.swagger.io/v2/pet
3. Se introduce în Body-raw dicţionarul specific din documentaţie din secţiunea pet pentru POST:
https://petstore.swagger.io
4. Se completează la "id" cu -1
5. Se apasă butonul "Send"

**Rezultat Aşteptat:**

Nu ar trebui să se genereze deloc un id pentru un număr negativ ci să apară o eroare şi un status cod corespunzător

**Rezultat Actual:**

Id-ul 9223372036854775807 este generat, iar status cod-ul este de 200 OK

-----------------------------------------

**Bug Id:** 4

**Titlu:** Pentru adăugarea unui text la id pentru tags se primeşte un status code 500 Server Error "type" unknown

**Severitate:** Medie

**Precondiţii:** Se foloseşte API Key: special-key în Authorization

**Date de test:**: Bubu

**Paşi de execuţie:**
1. Se foloseşte metoda HTTP POST
2. Se introduce endpoint-ul: https://petstore.swagger.io/v2/pet
3. Se introduce în Body-raw dicţionarul specific din documentaţie din secţiunea pet pentru POST:
https://petstore.swagger.io
4. Se completează la "id" tags cu Bubu
5. Se apasă butonul "Send"

**Rezultat Aşteptat:**

Ar trebui să primim un status cod din seria 400 şi un mesaj de eroare

**Rezultat Actual:**

Primim un status code din seria 500 ce ţine de eroare de server

-----------------------------------------

**Concluzii**

* Au fost trimise 12 request-uri şi executate 46 de teste JavaScript, din care doar 42 au fost executate cu succes
* 91.3% din teste au trecut si 8.7% au căzut
* 3 bug-uri au fost găsite şi raportate, unul de severitate mare si 2 de severitate mică
* Se prezintă un risc crescut deoarece baza de date permite inserări multiple pe acelaş id pentru animale
  

