**Jumping man GAME**

Este un joc in care sarim peste obstacole pentru a face scor folosind un buton.

Pentru implementarea acestui proiect am avut nevoie de urmatoarele componente:

-Arduino Uno
-Cablu USB
-Breadboard
-buton
-Potentiometru de 10k ohm
-2 rezistente de 220ohm
-LCD 16*2
-Fire

*Conectarea schemei:
1.5V de la Arduino catre + la breadboard
2.Ground-ul de la Arduino catre - la breadboard
3.VSS de la LCD cu -
4.VDD la +
5.Adaugam potentiometrul pe breadboard
6.V0 la mijlocul potentiometrului 
7.Rs la pinul 11 la Arduino
8.R/w la - 
9.Enable la pinul 9 la Arduino
10.D4 la pinul 6 la Arduino
11.D5 la 5
12.D6 la 4
13.D7 la 3
14.A la + cu un rezistor
15.k la -
16.pinul din dreapta de la potentiometru la -
17.atasam butonul la breadboard
17.partea dreapta jos de la buton la pinul 2 Arduino
18.aceeasi parte la - cu o rezistenta
19.partea stanga jos cu +

*In cod:
-Am definit omuletul care alearga si sare
-Cream pozitiile de alergare, saritura, si asa mai departe prin reprezentarea pe biti
-Cream caracterul
-Cream o functie care gliseaza terenul spre stanga
-Desenam scena


