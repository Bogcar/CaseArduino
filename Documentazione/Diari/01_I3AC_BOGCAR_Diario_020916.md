##### Carlo Bogani SAMT 02.09.2016

# Diario

## Lavori Svolti

Dalle ore 10:05 alle ore 11:35 :
Parte di teoria riguardante il modulo 306,
spiegazione del programma, date dei test e presentazioni del software GitHub e
versioning.
Introduzione e spiegazione del primo progetto da svolgere, ovvero un case per
Arduino in cui dobbiamo farci stare Arduino ed utensili legati ad esso oppure
un sistema di collocazione per Arduino e BreadBoard senza che i due si separino,
ovviamente bisogna scegliere se fare uno o l'altro.

Dalle ore 13:20 alle ore 16:00 :
Installazione e configurazione dei software SourceTree e GitHub.

* ###### GitHub
Innanzitutto, mi sono recato sul sito di GitHub, https://github.com/,
 per creare un account ed una repository in cui metterci tutti i documenti
 riguardi il progetto "CaseArduino".
 In seguito, ho scaricato il software e creato un file .gitconfig in modo che
 il programma funzioni correttamente.

* ###### SourceTree
In principio, mi sono recato sul sito di SourceTree,
https://www.sourcetreeapp.com/, e scaricato il setup del software.
 In seguito, ho installato il tutto per poi configurare GitHub nel programma,
 immetendo il account GitHub in SourceTree.

Tutto ciò è stato svolto grazie all'aiuto della guida sviluppata dal Prof.
Muggiasca :
https://github.com/LuMug/iSete/blob/master/Guide/ImpostareAmbienteLavoro.md

Dalle ore 16:00 alle 16:30 :
Creazione e sviluppo del diario.

## Problemi Riscontrati

Il problema che ho riscontrato è stato un errore riguardante la connessione
internet, l'applicazione (SourceTree) non riusciva a connetersi ad internet e
per risolvere ciò ho agggiunto la riga dei dati di accesso per http.


File .gitconfig :

[user]
	name = carlo.bogani
	email = carlo.bogani@samtrevano.ch

[core]
  autocrlf = true
  #excludesfile = C:\Users\Carlo\Documents\gitignore_global.txt

[filter "lfs"]
  clean = git-lfs clean %f
  smudge = git-lfs smudge %f
  required = true

[http]
    proxy = http://carlo.bogani:XXXXXXX@10.20.0.1:8080
[https]
  proxy = https://carlo.bogani:XXXXXXXX@10.20.0.1:8080
