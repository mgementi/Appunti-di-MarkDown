
# Appunti su MarkDown !

## Titoli e sottotitoli

Di seguito elenco tutti i titoli esistenti su MD:

## Titolo 2

### Titolo 3

#### Titolo 4

##### Titolo 5

###### Titolo 6

<br>
Ricordo che i titoli necessitano di *una linea vuota prima e dopo.

<br><br>

## Paragrafi e testo
Questo è un paragrafo  
Vado a capo con 2 spazi + enter oppure con il tag br.

t*est*o corsivo in mezzo.  
*testo* corsivo.  
__testo__ sempre corsivo.  
**testo**  spesso.  
***testo*** oppure ___testo___ corsivo e spesso.  
t***est***o corsivo e spesso in mezzo.

<br><br>

## Blockquotes


> Questa è una blockquote.
> Necessita di uno spazio prima e dopo la sua creazione.
> > Permette l'indentazione.

<br><br>

## Elenchi

### **Elenco non numerato:**

- indentazione 1
  - indentazione 2
    - indentazione 3

### **Elenco numerato:**

1. uno
2. Se si vuole indentare una lista non ordinata servono 4 spazi.
     - Ecco la lista
     - Eccomi ancora.

3. Se si vuole aggiungere del codice al punto bisogna indentare di 8 spazi e andare a capo.
   
        <html>
          <head>
            <title>titolo</title>
          </head>
        </html>

4. Se si vuole aggiungere dei commenti basta indentare di 4 spazi e andare a capo.

    Ecco un commento inutile.
5. Se si vuole aggiungere un'immagine ecco quà:
  ![Una mela prelibata !](./immagini/mela.png)

<br>

## Codice

Se voglio scrivere in codice mi basta fare `così`.  
`` Se ho dei backtick nel codice tipo `così`, ora non ho più problemi ``

Per creare dei codici di blocco devo indentare di almeno 4 spazi.

    <html>
        <head>
            <title>titolo</title>
        </head>
    </html>


<br>

```C++
//Qui scrivo del codice in C++
int variabile = 2;
```

<br><br>

## Horizontal Rule

Posso creare una horizontal rule in più modi, ma è necessario una linea vuota prima e dopo.

modo 1

***

modo 2

___

modo 3

---

<br><br>

## Links

Ecco un link a [Wikipedia](https://www.wikipedia.org)  
Ecco un link a [Links](#links)  
Ecco un link con tanto di commento in sovrimpressione a [Wikipedia](https://www.wikipedia.org "Il miglior sito per imparare cose nuove")  
I commenti si possono mettere anche con \` \` oppure \( \)  
Ecco un quick link: <https://www.wikipedia.org>  
Ecco una quick link con mail: <mymail@gmail.com>  
Ecco un link in grassetto ! [**Wikipedia**](https://www.wikipedia.org)  
Ecco un link in corsivo ! [*Wikipedia*](https://www.wikipedia.org)  
Ecco un link in monospace ! [`Wikipedia`](https://www.wikipedia.org)  
<br>
**NB**: se ci sono degli spazi nei link usare %20%  
<br>

### Link compatti

Ecco un link in forma compatta ! [Wikipedia][1]

Ora definisco \[1\], stando attendo a lasciare uno spazio prima.  

[1]: https://www.wikipedia.org "Commento al top !"

<br><br>

## Immagini

Riutilizzo la mela di prima.  
Posso anche aggiungere commenti in sovrimpressione e un link.

[![Una mela prelibata !](./immagini/mela.png "Una mela rossa")](https://www.apple.it)

<br>

## Escapes

Il carattere di escape è il **\\**

<br><br>


## Tabelle:

In questo modo creo una tabella:
 nome | cognome 
 --- | ---
michele | suco




