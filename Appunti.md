
# Appunti su MarkDown !

## Titoli e sottotitoli

Di seguito rilascio l'elenco tutti i titoli e sottotitoli esistenti su MD:

# Titolo 1

## Titolo 2

### Titolo 3

#### Titolo 4

##### Titolo 5

###### Titolo 6

<br>

Ricordo che i titoli necessitano di **una linea vuota prima e dopo**.

<br><br>

## Paragrafi e testo
Questo è un paragrafo.  
Per andare a capo servono **2 spazi + invio** oppure basta usare il **tag \<br\>**.  

Di seguito tutte le formattazioni possibili del testo:

t*est*o corsivo in mezzo.  
*testo* oppure __testo__ corsivo.   
**testo**  spesso.  
***testo*** oppure ___testo___ corsivo e spesso.  
t***est***o corsivo e spesso in mezzo.  
~testo~ tagliato.  
`testo` monospaced.

**NB:** è possibile togliere la formattazione dai link usando il monospaced. Ad esempio: https://www.google.it è un link formattato, mentre `https://www.google.it` non lo è.

<br><br>

## Blockquotes


> Questa è una blockquote.  
> Creare blockquotes è semplice, basta ricordarsi che necessitano di **una linea vuota prima e dopo la sua creazione.**  
> > Permette l'indentazione.

<br><br>

## Elenchi

Creare elenchi in MD è **self-explainatory**.  
Ecco alcuni esempi:

### **Elenco non numerato:**

- indentazione 1
  - indentazione 2
    - indentazione 3

### **Elenco numerato:**

1. uno
2. Se si vuole indentare una lista non ordinata **serve inserire 4 spazi e il carattere \-**
     - Ecco la lista
     - Eccomi ancora.

3. Se si vuole aggiungere del codice **serve andare a capo e poi inserire 8 spazi.**
   
        <html>
          <head>
            <title>titolo</title>
          </head>
        </html>

4. Se si vuole aggiungere dei commenti **serve andare a capo e poi inserire 4 spazi.**

    Ecco un commento inutile.
5. Se si vuole aggiungere un'immagine ecco quà:
  ![Mela prelibata](./immagini/mela.png)

<br>

## Escapes

Alcuni caratteri come:
- \`
- \*
- \_
- \-
- \[
- \]
- \(
- \)
- \<
- \>

Sono riservati e dunque è necessario usare l'escape.  
Il carattere di escape è il **\\**.

<br><br>

## Codice

Basta usare \`\` per formattare blocchi di testo in formato monospaced, senza preoccuparci di inserire al suo interno caratteri riservati che potrebbero alterare il formato del documento in MD.

`` Ad esempio ora non ho problemi con dei backtick interni tipo `così` e non sono obbligato ad usare sempre il carattere di escape ``

Per creare dei blocchi di codice **serve inserire almeno 4 spazi**.

    <html>
        <head>
            <title>titolo</title>
        </head>
    </html>


<br>

In alternativa all'indentare posso cavarmela nel modo seguente, riuscendo anche a sfruttare la sintax highlighting, specificando il linguaggio di riferimento dopo le \`\`\`

```C++
//Qui scrivo del codice in C++
int variabile = 2;
```

<br><br>

## Horizontal Rule

Posso creare una horizontal rule \(ossia una riga di divisione\) in più modi ***equivalenti***. In ogni caso è **necessario inserire una linea vuota prima e dopo la notazione**.

modo 1

***

modo 2

___

modo 3

---

<br><br>

## Links

Gestire i link è molto semplice, ecco alcuni esempi:

### Link esterni

Ecco un link a [Wikipedia](https://www.wikipedia.org)  
Ecco un link con tanto di commento in sovrimpressione a [Wikipedia](https://www.wikipedia.org "Il miglior sito per imparare cose nuove")  

**NB**: I commenti si possono mettere anche con \` \` oppure \( \), oltre che con \" \".  

Ecco un link in grassetto ! [**Wikipedia**](https://www.wikipedia.org)  
Ecco un link in corsivo ! [*Wikipedia*](https://www.wikipedia.org)  
Ecco un link in monospace ! [`Wikipedia`](https://www.wikipedia.org)

<br>

### Link speciali
Ecco un link locale a [Links](#links)  
Ecco un extended link: <https://www.wikipedia.org>  
Ecco una mail link con mail: <mymail@gmail.com>  
   
<br>

### Link compatti

Ecco un link in forma compatta ! [Wikipedia][1]

Ora definisco \[1\], stando attendo a lasciare uno spazio prima.  

[1]: https://www.wikipedia.org "Commento fiero"

<br>

**NB**: se ci sono degli spazi nei link usare scrivere **%20%** al posto di ogni spazio, per questioni di compatibilità.

<br><br>

## Immagini

Gestire le immagini è semplice.  

Modi di aggiungere un immagine: 

1. Standard:

    \!\[Mela prelibata\]\(./immagini/mela.png)\]
2. Con commento in sovrimpressione:

    \!\[Mela prelibata\]\(./immagini/mela.png \"Una mela rossa\"\)\]
3. Con link:

    \!\[Mela prelibata\]\(./immagini/mela.png\)\]\(https://www.apple.it\)
4. Con link e commento in sovrimpressione:

    \!\[Mela prelibata\]\(./immagini/mela.png \"Una mela rossa\"\)\]\(https://www.apple.it\)

Ecco una dimostrazione del punto 4:

[![Una mela prelibata !](./immagini/mela.png "Una mela rossa")](https://www.apple.it)

<br>

## Tabelle:

Creare tabelle in MD, è semplice(come tutto del resto anche perchè se no chi cazzo userebbe MD per prendere appunti ?).  

Comunque ecco alcuni esempi:
| nome | cognome | 
| --- | --- |
| Michele | Gementi |
| Gino | Spezzatino |

Posso anche impostare un allineamento per ogni colonna e imporre uno stile su ogni campo della colonna in modo diverso:

| nome | cognome | nascita |
| :--- | :---: | ---: |
| *M.* | **G.** | `2001` |
| *G.* | **S.** | `2000` |

<br><br>

## Footnotes

**Disclaimer:** Non sono disponibili su ogni renderer di MD.  
Per aggiungere una footnote basta fare così[^1].  
Ne aggiungiamo un'altra speciale[^special].  

[^1]: Questa è la prima footnote.  
[^special]: Questa è la special.


<br><br>

## Definition Lists

**Disclaimer:** Non sono disponibili su ogni renderer di MD.  
Servono per fare delle definizioni.  
Eventualmente posso fornire più definizioni.  
Ecco alcuni esempi:

Parola 1
: Definizione

Parola 2
: Definizione 1
: Definizione 2

<br><br>

## Task Lists

**Disclaimer:** Non sono disponibili su ogni renderer di MD.  

Sono semplicemente degli elenchi di checkboxes, come una lista della spesa:

- [x] Task svolto
- [ ] Task da svolgere

<br><br>

## Emoji

**Disclaimer:** Non sono disponibili su ogni renderer di MD.  

Per inserire delle emoji basta copiarle ed incollarle da un database tipo [EmojiPedia][2] oppure inserire gli shortcode tipo :joy: . C'è un database di questi shortcode online, anche se la pagina sembrerebbe non rispondere [Qui][3]

[2]: https://emojipedia.org/ "database di emoji"
[3]: https://gist.github.com/rxaviers/7360908