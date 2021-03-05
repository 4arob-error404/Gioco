# SPEEDHIGWAY
Lo scopo del gioco è quello di allenare l'equilibrio di una persona.
Rimanendo fermi sul posto bisogna infatti spostare il busto a destra e a sinistra per schivare degli ostacoli che compaiono sullo schermo
Il giocatore deve essere munito di un marker di colore rosso da attacare sul petto.
Il gioco sfrutta due librerie: opencv e PyGame.
![pygame](https://user-images.githubusercontent.com/61046970/110098840-ec710000-7da0-11eb-83b8-0da86a2f2e64.png)
![opencv](https://user-images.githubusercontent.com/61046970/110098845-eda22d00-7da0-11eb-9bb6-d17dafc2c0d3.png)
Tramite opencv, sfruttando la fotocamera, si rilevano gli oggetti di colore rosso e si ricavano le coordinate di questi ultimi.
![schermateVideocamera](https://user-images.githubusercontent.com/61046970/110099029-23dfac80-7da1-11eb-9668-405f0178cd51.png)
Sfruttando le coordinate rilevate si sposta una macchina sull'asse delle ascisse tramite la libreria PyGame.
Gli ostacoli da evitare sono: file di macchine e autobus che vengono spawnate sullo schermo in ordine e posizione randomici.
Ogni volta che il giocatore supera un ostacolo viene incrementato il punteggio ma ATTENZIONE, la velocità degli ostacoli aumenta!!!
![immagineGioco](https://user-images.githubusercontent.com/61046970/110099060-2a6e2400-7da1-11eb-927f-f34591b395e6.png)
Occhio  anon colpire gli ostacoli se non vuoi perdere!!!
![gameOver](https://user-images.githubusercontent.com/61046970/110099083-335ef580-7da1-11eb-90b5-28fecd024ed3.png)
