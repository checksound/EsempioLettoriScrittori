# Esempio lettori-scrittori

Una base di dati è condivisa fra vari thread concorrenti:
* Lettori: accedono solo in lettura; non modificano la base di dati;
* Scrittori: possono sia leggere che scrivere;

**Problema:**

* permettere a lettori multipli di leggere contemporaneamente (non crea interferenze);
* permettere ad un solo scrittore alla volta di accedere alla base di dati (accesso esclusivo);