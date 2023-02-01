# Corso STM32
In questa repository verranno inseriti tutti i codici proposti nel corso sul microcontrollore STM32

# Materiale
Per ogni lezioni è possibile trovare il codice sorgente spiegato nei video. Inoltre è presente un file che contiene la guida di riferimento per le funzioni HAL utilizzate nella programmazione.

Lezioni:
  1. Presentazione del software STM32CubeIDE e guida al primo poggetto
  2. Avvio e lettura ADC

# Lezione 1
Nella prima lezione viene presentato l'ambiente di programmazionione e si eseguirà passo passo la programmazione del microcontrollore per poter accendere e spegnere un LED ogni 1s tramite un Timer interno.

# Lezione 2
Nella seconda lezione viene presentato un software per utilizzare l'ADC. In particolare l'ADC dovrà convertire i dati presenti su 3 canali in modo temporizzato da un Timer. Inoltre i dati vengono trasferiti in memoria tramite l'uso della DMA che è uno strumento molto potente che permette lo scambio di dati tra periferiche in modo efficiente. 

# Lezione 3
Nella terza lezione vengono presentate delle tecniche di debug molto potenti per risolvere diversi problemi come: Monitor seriale, lettura SFR, live expression. Il codice sorgente non è importate perchè queste tecniche di applicano a qualsiasi contesto. 
  ### NOTA: Nel video mi sono dimenticato di specificare che per utilizzare la trasmissione seriale in modalità interrupt è necessario abilitare l'interrupt     corrispodnente nell'interfaccia grafica sulla periferica USART nella sezione NVIC.
