_______________________________________________________________________

  G r a n d  T h e f t  A u t o  III

  ReadMe.txt

_______________________________________________________________________

 Sommario
__________

	Informazioni preliminari
	Requisiti di sistema
	Informazioni generali
	Installazione
	Configurazione
	Risoluzione dei problemi
	Driver per schede video	

_______________________________________________________________________

 Informazioni preliminari
__________________________

Grazie per aver acquistato "Grand Theft Auto III".

Questo file ReadMe contiene le informazioni dell'ultimo minuto e alcuni suggerimenti per risolvere i problemi più comuni.

Per novità, suggerimenti e per mettersi in contatto con la comunità di Grand Theft Auto III, consulta i seguenti siti:
	 
	www.rockstargames.com
	www.take2games.com
	www.gta3.com

Per il supporto tecnico:

Consulta il manuale utente.


_______________________________________________________________________

 REQUISITI DI SISTEMA
______________________

Sistemi operativi supportati:

Grand Theft Auto III richiede Microsoft DirectX 8.1.
I sistemi operativi supportati sono:

	Windows 98
	Windows 98 Seconda Edizione
	Windows Millennium
	Windows 2000 Professional (Workstation)
	Windows XP (Home e Professional)

I seguenti sistemi operativi NON sono supportati:

	Windows 95
	Windows NT (qualsiasi versione)
	Mac OS
	Linux
	BEOS

Requisiti hardware minimi 
	
	Processore Intel Pentium III o AMD Athlon a 450 MHz
	96 MB di RAM
	Lettore CD/DVD-ROM 4x o superiore 
	700 MB di spazio libero su disco
	Scheda video con 16 MB di memoria con driver compatibili DirectX 8.1
	Scheda audio compatibile DirectX 8.1
	Tastiera
	Mouse

Requisiti hardware raccomandati 

	Processore Intel Pentium III o AMD Athlon a 700(+) MHz
	128(+) MB di RAM
	Lettore CD/DVD-ROM 8x o superiore
	700 MB di spazio libero su disco
	Scheda video con 32(+) MB di memoria con driver compatibili DirectX 8.1
	Scheda audio compatibile DirectX 8.1 con supporto per il surround
	Gamepad (USB o porta joystick)
	Tastiera
	Mouse

_______________________________________________________________________

 INFORMAZIONI GENERALI
_______________________

DirectX:
Grand Theft Auto III richiede le librerie Microsoft DirectX 8.1 per poter funzionare. Di conseguenza, raccomandiamo di controllare che i driver delle schede audio e video siano compatibili DirectX 8.1. Le prestazioni migliori si hanno con schede 100% compatibili DirectX 8.0/8.1.

Windows XP:
Raccomandiamo i driver distribuiti dai produttori di hardware invece di quelli standard forniti da Microsoft e installati automaticamente dal sistema.

Memoria:
Grand Theft Auto III richiede almeno 96 MB di memoria per poter funzionare. Per prestazioni ottimali, consigliamo 128 MB (o meglio ancora 256 MB).

Applicazioni in esecuzione:
Grand Theft Auto III è stato progettato per sfruttare appieno tutte le risorse disponibili del sistema, per cui consigliamo di chiudere qualsiasi applicazione prima di avviare il gioco.

Memoria video:
Grand Theft Auto III richiede una scheda video con almeno 16 MB di memoria; in caso contrario, il gioco non può neanche essere eseguito.

Processori AMD K6/2 e K6/III:
Questi processori AMD eseguono Grand Theft Auto III a una velocità troppo bassa per risultare giocabile.

_______________________________________________________________________

 INSTALLAZIONE
_______________

Inserisci il CD 1 di Grand Theft Auto III nel lettore CD/DVD-ROM; se la funzione di AutoPlay è abilitata, il programma di installazione verrà attivato automaticamente. 
Se la funzione di AutoPlay non è abilitata, raggiungi con l'esplora risorse il CD di Grand Theft Auto III ed esegui manualmente il file setup.exe.

Spazio su disco
Grand Theft Auto III richiede circa 700 MB di spazio su disco.

Rimozione
Durante la rimozione di Grand Theft Auto III, non vengono eliminate le cartelle "MP3", "SKINS" e "SAVEGAMES"; spetta all'utente rimuoverle manualmente.

_______________________________________________________________________

 CONFIGURAZIONE
________________

Gestione dell'audio:
Il gestore API dell'audio selezionato nella configurazione di Grand Theft Auto III può influenzare le prestazioni di gioco; prova a utilizzare un altro gestore se le prestazioni non sono ottimali. Quelli consigliati sono: Software, MSS Fast, RSX, Direct Sound Hardware, Direct Sound Software.

Modellazione acustica dinamica
Disabilita la modellazione acustica dinamica nelle opzioni audio per un leggero miglioramento delle prestazioni.

Tracce
Disabilitare l'effetto traccia nelle opzioni grafiche di Grand Theft Auto III può migliorare le prestazioni.

Risoluzione video
Selezionare risoluzioni video minori in Grand Theft Auto III permetterà prestazioni migliori sui sistemi meno potenti. Anche utilizzare una profondità di colore di 16 bit color, invece che di 32 bit, può aiutare drasticamente.

_______________________________________________________________________

 RISOLUZIONE DEI PROBLEMI
__________________________

Windows XP e schede video con chipset nVIDIA (e forse anche altre marche):
Abbiamo rilevato un possibile problema con Windows XP che causa difetti grafici nel menu e durante il gioco. Il problema è limitato agli utenti che fanno uso di questo sistema operativo. 
Il problema può essere risolto utilizzando la versione aggiornata del file d3d8.dll (la versione che dà problemi è quella sul CD di Windows XP CD 5.1.26000.0 - mentre le versioni certificate che funzionano correttamente sono quelle 5.1.2600.15 e 5.1.2600.29). Attualmente, l'unica modo per aggiornare questa .dll è di installare la patch per Windows XP Patch: "The Computer Cannot Enter Standby or Hibernate 
If a Direct3D-Based Screen Saver Is Running (Q306676)", disponibile sul seguente sito web:
http://download.microsoft.com/download/whistler/Patch/Q306676/WXP/IT/Q306676_WXP_SP1_x86_ITA.exe

Questo aggiornamento potrebbe diventare parte integrante di un Windows XP Service Pack, di un aggiornamento di compatibilità di Windows XP o di un possibile aggiornamento di DirectX 8.1.

Schede video Power VR Kyro 2
Non siamo riusciti a fornire un supporto completo per questa scheda a causa della modalità di rendering da lei utilizzata; di conseguenza, alcuni effetti sulle texture potrebbero non essere riprodotti correttamente (si tratta comunque di disturbi limitati). Raccomandiamo di utilizzare questa scheda con una profondità di colore di 32 bit, poiché a 16 bit è stato rivelato un raro problema di funzionamento. Consigliamo inoltre di modificare le seguenti impostazioni:
=> Accedi alle impostazioni avanzate dello schermo 
	Seleziona la pagina Direct 3D e crea un nuovo profilo per gta3.exe.
	Dentro il profilo inserite:
		DISABLE W buffer
		ENABLE external depth / stencil buffer format
		ENABLE Direct 3d / stencil buffer format
		ENABLE depth / stencil buffer format
		ENABLE depth / stencil buffer loading

Schede audio Aureal:
Abbiamo riscontrato un gran numero di crash correlati alla presenza delle schede audio Aureal. Il relativo produttore ha da tempo smesso di esistere e non esistono driver aggiornati. Abbiamo avuto numerosi problemi nel supportare le schede Aureal nei prodotti passati, ma con i driver attualmente in circolazione, il problema non può essere aggirato (anche se utilizzare un gestore audio differente come quello Software, MSS Fast, RSX, Direct Sound Hardware, Direct Sound Software, potrebbe risolvere il problema).

Chipset audio incorporati su schede madri:
Abbiamo scoperto che alcuni chipset montati su motherboard non hanno un supporto hardware per il sound buffer e causano un crash di sistema quando viene avviato Grand Theft Auto III. Eseguendo il programma Microsoft "DXDIAG" ed eseguendo i test audio, viene mostrato un messaggio secondo cui l'hardware buffer non è supportato e che si consiglia di utilizzare un software buffer. Selezionando software buffer sarà possibile utilizzare questi chipset con Grand Theft Auto III.

Deframmentazione del disco
Se riscontri rapidi e periodici rallentamenti durante la guida, Grand Theft Auto III potrebbe avere dei problemi nel recuperare i dati di gioco in modo sufficientemente veloce. Raccomandiamo di lanciare il programma di deframmentazione regolarmente per prestazioni ottimali del disco.

_______________________________________________________________________

 DRIVER PER SCHEDE VIDEO 
_________________________

Raccomandiamo di utilizzare i driver più recenti per la tua scheda video. Quando possibile, consigliamo di utilizzare i "Reference" driver del chipset invece dei driver specifici e modificati dal produttore della scheda video o quelli certificati Microsoft WHQL.

Di seguito sono riportati i siti web dei produttori delle schede video più comuni. 
Grand Theft Auto III potrebbe non supportare alcune o tutte le schede video prodotte da un particolare produttore; la presenza di un produttore in questa lista non implica in nessun modo la compatibilità dei loro prodotti con questo gioco.

3Dfx Interactive 			- http://www.3dfx.com/
3Dlabs 				- http://www.3dlabs.com/
Asus 					- http://www.asus.com/
ATI 					- http://support.atitech.ca/
Aztech Labs 			- http://www.aztechlabs.com/
Canopus 				- http://www.canopuscorp.com/
Creative Labs 			- http://www.creativelabs.com/
Diamond Multimedia 		- http://www.diamondmm.com/
Elsa Technology 			- http://www.elsa.de/
Guillemot 				- http://www.guillemot.com/
Hercules (vedi Guillemot) 	- http://www.guillemot.com/
I/O Magic 				- http://www.iomagic.com/
Jaton 				- http://www.jaton.com/
Leadtek 				- http://www.leadtek.com/
Matrox 				- http://www.matrox.com/
NVIDIA 				- http://www.nvidia.com/
Orchid (vedi Diamond MM) 	- http://www.diamondmm.com/
SIII Incorporated 		- http://www.sIII.com/
SiS 					- http://www.sis.com.tw/
VIA Technologies 			- http://www.viatech.com/
VideoLogic 				- http://www.videologic.com/

_______________________________________________________________________

Software e documentazione
Copyright (c) 2002 Rockstar Games.