Descrizione:
Attraverso l'apposita API di Boolean
https://flynn.boolean.careers/exercises/api/random/mail
generare 10 indirizzi email e stamparli in pagina all'interno di una lista.
Bonus
Far comparire gli indirizzi email solamente quando sono stati tutti generati.


- inizializzare vue e importate libreria axios
- nuova variabile array vuota (es: emails) in data() per salvare le email
- nuova funzione getEmails() in methods per generare email
- console.log( 'ciao' ) nella funzione
- eseguire funzione getEmails() in created()
_ verificare in console che la funzione venga eseguita
- dentro funzione ciclo di 10 giri che fa chiamata axios a API
- salvare risultato della chiamata in variabile result o res (importante che è il risultato della chiamata e non la mail)
- analizzare result con console.log per vedere quale proprietà ha la mail come risultato
- pushare la proprietà con mail dentro array emails
- ciclo vfor in html di emails e stampare valore di ogni email