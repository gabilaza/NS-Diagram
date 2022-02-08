# NS-Diagram

## Introducere
In programarea computerelor, o diagrama Nassi-Shneiderman (NSD) este o metoda de reprezentare a unui flowchart, o reprezentare grafica de proiectare pentru programarea structurata. Proiectul ia drept input un pseudocod simplu, care poate fi citit de la tastatura din program, si afiseaza NSD.

Pseudocodul are urmatoarele instructiuni:
- ```var int/string <variabila>``` - declararea unei variabile de tip int/string

- ```set <variabila> <expresie/string>``` - atribuirea catre o variabila. Daca variabila e int se atribuie o expresie, iar daca e string se atribuie ca string tot cuvantul

- ```read <variabila>``` - citirea unei variabile

- ```print <variabila>``` - afisarea unei variabile

- ```if <expresie> ... else ... endif``` - instructiunea if

- ```while <expresie> ... endwhile``` - instructiunea while
  
- ```repeat ... until <expresie>``` - repeat until

- ```pass``` - instructiune dummy, nu face nimic

## Mentiuni
  
Variabilele sunt litere mari si mici, expresiile din instructiunea set admit doar variabile, numere si operatori de baza (+, -, *, /, %), iar expresiile din if/while/repeat admit in plus comparatii (!=, <. ==, <=, >, >=), fara spatii intre ele. Expresiile nu pot avea operatii cu string-uri. Toate instructiunile se scriu pe o singura linie (si else, endif, endwhile, etc se numara ca instructiuni). Structura unui if trebuie respectata prin folosirea if, else si endif (daca vrem sa avem o ramura if/else goala se poate folosi instructiunea pass), similar pentru bucle.

## Scurtaturi/butoane
- ```ctrl+r (RUN)``` - compileaza codul si afiseaza diagrama

- ```ctrl+s (SAVE)``` - salveaza codul si input-ul/output-ul

- ```ctrl+l (LOAD)``` - incarca codul si input-ul/output-ul
  
- ```ctrl+o (CENTER)``` - aduce diagrama la forma initiala
  
- ```ctrl+d (CLEAR)``` - sterge tot textul din caseta curenta

- ```ctrl+j (SAGEATA DREAPTA)``` - mutare caseta de text curenta la dreapta
  
- ```ctrl+k (SAGEATA STANGA)``` - mutare caseta de text curenta la stanga
 
## Echipa
Laza Gabriel si Aliciuc Alexandru, grupa B2, UAIC
