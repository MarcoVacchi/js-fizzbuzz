# FizzBuzz

## Consegna:
Scrivi un programma che stampi i numeri da 1 a 100,
ma per i multipli di 3 stampi “Fizz” al posto del numero e per i multipli di 5 stampi Buzz.
Per i numeri che sono sia multipli di 3 che di 5 stampi FizzBuzz.
Prima di partire a scrivere codice poniamoci qualche domanda:
Come faccio a sapere se un numero è divisibile per?
Abbiamo visto qualcosa di particolare che possiamo usare?
Consigli del giorno:
1. scriviamo sempre prima dei commenti in italiano per capire cosa vogliamo fare
2. proviamo ad immaginare le operazioni che vogliamo far svolgere al nostro programma così come lo faremmo "a mano"
Nota bene
prima di tutto, nel file README, indicate tutti i passaggi utili allo svolgimento del programma. Soltanto dopo scrivete la vostra soluzione in JS.



### Ragionamento

- Devo creare un ciclo (for)che stampi numeri da 1 a 100 con diverse caratteristiche;
   - per i multipli di 3, deve stampare la stringa "Fizz";
   - per i multipli di 5, deve stampare la stringa "Buzz";
   - per i multipli di entrambi, 3 e 5 deve stampare la stringa "FizzBuzz"

### Procedimento pseudo codice

- creo il ciclo;
  - al suo interno creo una variabile che dovrà essere incrementata di volta in volta fino a 100;
  - do un valore numerico alla mia variabile;
  - imposto il limite al mio contatore
    - creo una condizione all'interno del mio ciclo utilizzando SE;
      - SE multiplo di 3 e 5, stampa FizzBuzz;
      - ALTRIMENNTI SE multiplo di 3, stampa Fizz;
      - ALTRIMENTI multiplo di 5, stampa Buzz; 
 - finché il contatore non arriva a 100;
 - stampo;