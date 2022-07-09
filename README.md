# Danmakufu Engine - Italian edition
Questa versione di Danmakufu è stata creata sia allo scopo di ottimizzare e risolvere alcuni problemi con la fonte originale,ed inoltre è completamente retrocompatibile con ph3. Se qualcosa non funziona come previsto, faccelo sapere.

## Cambiamenti principali 
Ecco un elenco di modifiche rispetto al Danmakufu originale che potrebbero consentire al tuo computer di usarlo meglio.
 * Cambia il modo in cui RNG è determinato per essere molto più stabile rispetto al passato (mt19937 rispetto a un Mersenne Twister del 1996, lmao)
 * Rimuove molte chiamate di funzione ripetute (solo con il movimento dei punti elenco a partire dal 24/06/2019)
 * Rimuove MOLTI vertici non necessari calcolati (ma non utilizzati) durante il disegno di laser curvilinei (vedi Ringraziamenti speciali)
 * Abilita molti flag di ottimizzazione che mkm per qualche motivo disabilitato (in pratica tutto sotto / O2)
 * Risolve il problema di risoluzione della finestra (non proprio 640x480) che si verifica con il sorgente al momento della compilazione, ma non con la build ph3 originale.
 * L'estrazione dei dati ora funziona correttamente, consente l'uso di giochi come Hollow Song of Birds di Kaisendo e altri giochi che utilizzano archivi di dati.
 * Le barre laterali a schermo intero ora sono nere rispetto all'onnipresente DNH Grey.

## Requisiti
 * zlib
</br>Usate anche [vcpkg](https://github.com/Microsoft/vcpkg) C++ Library Manager.

## Problemi conosciuti
 * Wine 4.12.1 (confermato almeno su macOS) presenta alcuni problemi di ridimensionamento con le dimensioni della finestra, essendo 9 pixel troppo larghi e 7 pixel troppo alti.Ciò causa un brutto ridimensionamento delle risorse di gioco, probabilmente a causa delle vecchie dimensioni di Windows le chiamate non sono compatibili al 100% con le versioni di Wine.

## Rigraziamenti speciali
Helepolis - per i tutorial su ph3
James7132 - per il bug fix alla versione originale
WishMakers - per il supporto col programma
Xalkas 2K - per l'aiuto dato
Zero - per l'aiuto dato

## Nuove funzionalità 
La versione esiste per coloro che desiderano avere alcuni miglioramenti minori alle funzionalità che non sono completamente 1: 1 con PH3 originale, ma preferiscono non aspettare fino al rilascio di DNH: R per usarli. Queste modifiche potrebbero essere rispecchiato nella compatibilità PH3 di DNH: R, ma a partire dal 09/08/2019 non sono attualmente implementati.

## Licenza
La libreria zlib ha la sua licenza, controlla zlib.h nel repository per queste informazioni. </br> </ br>
(citato dal repository di James7132 della fonte originale, mantenendo la stessa licenza.) </ br> Questo codice è concesso in licenza sotto la NYSL (Licenza Niru nari Yaku nari Suki ni shiro'). Principali punti tradotti:

  * Il disclaimer "Nessuna garanzia" è esplicitamente incluso.
  * La versione modificata del software DEVE essere distribuita sotto la responsabilità del distributore.
  * La versione ufficiale è scritta in giapponese.
