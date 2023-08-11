# project-java
simple calculator written in Java; supports addition, subtraction, multiplication and division
Calculul metricii LOC:
- Pentru fisierul calculator LOC=188, Linii utile de cod (fara comentarii) = 129;
- Pentru fisierul Start LOC=26, Linii utile de cod = 19;
- Pentru proiectul per general LOC=214, Linii utile de cod = 148 fara luarea in calcul a comentariilor.


Pentru complexitatea ciclomatica:
- Am calculat complexitatea ciclomatica cu ajutorul instrumentului Intellij IDEA si am obtinut urmatoarele valori:
       Complexitatea ciclomatica a metodei evaluateExpression este egala cu 12;
       Complexitatea ciclomatica a metodei Calculate deasemenea este egala cu 12;
  Conform schemei elaborate de Thomas McCabe acest indicator indica o complexitate de cod moderat complex.

   Pentru complexitatea cognitiva:
  - Pentru metoda evaluateExpressiom complexitatea cognitiva este egala cu 14;
  - Pentru metoda Calculate complexitatea cognitiva este egala cu 23;

  ANALIZA INFORMALA:

  Programul este construit din doua fisiere scrise in limbajul de programare JAVA. Odata cu deschiderea programului putem observa ca nu exista probleme majore si programul poate fi rulat. Executia are loc in fisierul Start.java iar logica din spatele programului este scrisa in Calculator.java. Odata cu rularea programului prin fisierul de baza Start.java are loc executarea unei bucle infinite WHILE care face calculul unui set de numere introduse de utilizator. Odata ce utilizatorul introduce optiunea exit are loc iesirea din modul calculator iar programul nu mai poate primi numere.

  Analiza statica:
  
