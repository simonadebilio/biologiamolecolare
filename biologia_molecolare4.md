# Il clonaggio del DNA

Il termine clonaggio di un segmento di DNA indica làintroduzione di un gene )o un suo segmento= allòinterno di una cellula, in modo che tale frammento venga copiato quando la cellula si replica, determinando la produzione di numerose cellule tutte contenenti almeno una copia di quel frammento.

Per gli esperimenti di clonaggio viene generata una molecola di **DNA ricombinante**, cioè isolata dal suo contesto e introdotta in un **replicone** (una unità di DNA capace di replicarsi detta vettore).

La molecola di DNA ricombinante viene introdotta in un sistema cellulare appropriato. Tutti i discendenti di questa singola cellula, detta **clone**, conterranno la medesima molecola di DNA ricombinante originariamente isolata, permettendo di produrne quantità praticamente illimitate.

Il clonaggio molecolare di un frammento di DNA parte d auna miscela complessa di frammenti generati dalla rottura meccanica o dal taglio con ER (enzimi di restrizione) del genoma di un certo organismo e usa poi cellule viventi per riprodurre molte copie di uno specifico frammento che è stato inserito all'interno di "trasportatori specializzati" chiamati **vettori di clonaggio**.

Esistono diversi tipi di vettori di clonaggio.

La principale considerazione da fare è relativa alle **dimensioni** dell'inserto di DNA che ogni vettore può accettare.

Dai plasmidi batterici naturali sono derivati **vettori di clonaggio plasmidici**. Tra i vari vettori disponibili, i plasmidi hanno acquistato un posto privilegiato per la loro *affidabilità* e *facilità di manipolazione*.

## Caratteristiche ideali di un vettore

Per svolgere la sua funzione, un vettore plasmidico *deve possedere* le seguenti proprietà:

+ un **origine di replicazione** (*ori*) che gli permetta di replicarsi autonomamente una volta introdotto all'interno della cellula ospite;
+ uno o più **marcatori genetici** o **"marcatori di selezione"** che permettano di individuare le cellule che contengono il vettore e qualsiasi frammento di DNA in esso inserito. I marcatori genetici possono essere *resistenze ad antibiotici* o *marcatori nutrizionali* (es. auxotrofie). In questo ultimo caso si devono usare ceppi batterici con mutazioni adatte;
+ contenere il maggior numero possibile di **siti di restrizione unici**, cioè presenti una sola volta nel loro DNA (siti di taglio che presentano il più alto numero possibili di enzimi di restrizione. Questi siti devono stare **al di fuori** delle regioni essenziali (replicone e marcatore).

Non è essenziale, ma molto utile:

+ *conoscere l'intera sequenza nucleotidica del vettore*, in modo da poter analizzare al computer tutti gli elementi di interesse (siti
di taglio, prodotti di digestione..);
+ che il *sito di clonaggio sia fiancheggiato da sequenze per i*
**primer universali** usati nella PCR e nel sequenziamento;
+ che il sito di clonaggio sia fiancheggiato da elementi di controllo che consentano la trascrizione dell'inserto di DNA in RNA (**vettori di trascrizione**) o la sua espressione in cellule di procarioti o di
eucarioti (**vettori di espressione**).

### I plasmidi come vettori

I plasmidi sono degli **elementi genetici extracrosomali** che si *replicano autonomamente* e che *segregano autonomamente* rispetto al DNA cromosomale batterico.

Variano da 1 a 200 Kb e sono molto diffusi tra i procarioti. 
Esempi di plasmidi batterici naturali sono i **plasmidi pcolE1** di E.coli (colina), i **plasmidi F** di E.coli (coniugazione), i **plasmidi Ti** o **Ri** di Agrobacterium (galla del colletto nelle dicotiledoni)...

I plasmidi possono essere *lineari* o *integrati* nel cromosoma batterico ma, nella maggior parte dei casi, sono molecole di DNA *circolari*. 

Nell'ospite batterico i plasmidi si presentano come **molecole circolari superavvolte** che, durante le manipolazioni sperimentali,
possono rilassarsi o linearizzarsi in seguito a rotture a singolo
o a doppio filamento.

La caratteristica più importante dei plasmidi è quella di essere dei **repliconi**, cioè molecole capaci di replicazione autonoma.
Un replicone è costituito da un **origine di replicazione, chiamata ori e da elementi di controllo. 

Si conoscono circa 30 repliconi, ma la maggior parte dei plasmidi di clonaggio possiede il replicone di **pMB1** (un plasmide naturale) che è *identico al replicone di pcolE1*.

I plasmidi si replicano per replicazione $\theta$ (uni o bi-direzionale) o per circolo rotante.

Richiedono proteine plasmidiche e/o dell'ospite batterico.

Oltre ad essere essenziale per la replicazione, l'origine di replicazione controlla:

+ il numero di copie del plasmide;
+ la specificità d'ospite.

#### I marcatori di selezione

I plasmidi naturali a volte codificano per *funzioni non essenziali*, mentre a volte *conferiscono un vantaggio selettivo* in alcune
situazioni. 
Per esempio possono codificare per le tossine batteriche o per geni di resistenza agli antibiotici. 

In alcuni casi, tuttavia, nessun vantaggio competitivo sembra essere associato alla presenza di geni di resistenza.

Tutti i vettori di clonaggio includono *almeno* un marcatore di selezione.
Lo scopo essenziale è di **distinguere** e di **selezionare** le molecole ricombinanti.
I marcatori di selezione più utilizzati nei batteri sono i geni di resistenza agli antibiotici. 

Per esempio il gene per la $\beta$-lattamasi codifica per un enzima capace di idrolizzare l'anello lattamico degli antibiotici di tipo penicillinico (es. l'ampicillina). 
I batteri che contengono un plasmide con questo gene, quindi,(simboleggiato con Amp o Ap) possono crescere in terreni di coltura che contengono l'antibiotico ampicillina.

#### I siti di restrizione unici

Per effettuare un clonaggio molecolare è necessario avere sempre
*almeno un sito di riconoscimento* per una **endonucleasi di restrizione**.

Il sito di riconoscimento per una endonucleasi di restrizione deve essere *presente* nel vettore *una sola volta* per non distruggere l'integrità fisica del plasmide e *non deve essere presente in regioni cis essenziali* (es. ori o promotori) o *in geni che codificano per funzioni essenziali* (es. geni di resistenza).


+ Un esempio di plasmide di clonaggio è il **PBR322**.

Questo è un vettore primitivo con un numero limitato di siti di restrizione unici (20) distribuiti su tutta la molecola di DNA.
È di piccole dimensioni, 4363 bp.

Contiene **due geni per la resistenza agli antibiotici**, **Amp e Tet** (insieme di geni che codificano per enzimi detossificanti la tetraciclina), al cui interno sono presenti siti di restrizione unici utilizzabili per il clonaggio. 

Per es. la clonazione in PstI inattiva il gene Amp, mentre la clonazione in BamHI inattiva il gene Tet.

+ Un vettore plasmidico più evoluto è il **pUC19**.

Questo vettore presenta un sito di clonaggio introdotto con la tecnica delle clonazione di oligonucleotidi sintetici.

È una serie plasmidica che differisce per la lunghessa e l'orientamento del **polylinker**.

Un polylinker o **multiple cloning site (MCS)**, è un corto segmento di DNA contenente molti siti di restrizione (circa 21).
I siti di restrizione all'interno di un MCS sono solitamenti unici, ovvero sono presenti una sola volta all'interno dello stesso plasmide.

Il polylinker è una regione del plasmide nella quale può essere inserito un DNA esterno.

Il sito di policlonaggio è inserito nel **gene lacZ** in modo da tenere la cornice di lettura della proteina; questo permette di individuare i cloni ricombinanti con un saggio enzimatico ($\alpha$-complementazione) e di esprimere la proteina corrispondente se l'inserto è inserito in fase.

Presenta resistenza all'Amp.

È un plasmide di espressione.

#### Evoluzione dei vettori di clonaggio

Da questi due vettori di clonaggio sono derivati decine di nuovi altri vettori. 

La tendenza è quella di creare vettori più piccoli e sempre più funzionali.

Ci sono numerosi vantaggi, infatti, a ridurre la dimensione di
un plasmide:

1. è **più maneggevole**. Per esempio è più difficile danneggiarlo o introdurvi interruzzioni a singola elica durante le manipolazioni sperimentali;
2. è **più facile estrarlo**. I principali metodi di separazione dei plasmidi dal cromosoma batterico si basano sulla denaturazione degli acidi nucleici (per es. mediante calore o basi diluite) e sulla loro successiva rinaturazione.
Mentre i plasmidi, di piccole dimensioni, rinaturano rapidamente, il grosso cromosoma batterico non riesce a rinaturare velocemente e viene
selettivamente eliminato. 

La *velocità di rinaturazione plasmidica è* **inversamente proporzionale** *alla dimensione*. Quanto più piccoli sono, tanto più facile é il loro isolamento;

3. è **più facile introdurlo dentro un batterio**. I metodi di
"trasformazione" sono essenziali nella tecnologia del DNA ricombinante. Esistono varie tecniche, come la *trasformazione con CaCl 2 o l'elettroporazione*.

In tutti i casi *l'efficienza di trasformazione è* **inversamente proporzionale** *alla dimensione plasmidica*.

Un'ulteriore tendenza è quella di **sostituire i siti di
restrizione unici con "Multi Cloning Sites"** sempre più completi.
Questa caratteristica (in genere) facilita il lavoro di clonaggio
permettendo di utilizzare l'enzima di restrizione più conveniente.

Questo problema é particolarmente sentito quando si devono clonare inserti di grosse dimensioni in cui possono essere presenti numerosi siti di restrizione.

Numerosi altri vettori più o meno "specializzati" sono reperibili
per gli utilizzi più disparati: "trascrizione in vitro", inserzioni di
trasposoni, selezione di mutazioni, clonaggio di frammenti amplificati con PCR, vettori "shuttle" che contengono più origini di replicazione ecc.

+ Il **pET system**

Un vettore pET consiste in un plasmide batterico "disegnato" per attivare una rapida produzione di una grande quantità di una qualsivoglia proteina, quando attivata.

Questo plasmide contiene diversi elementi importanti:

+ un **gene lacI** che codifica per il repressore proteico di *lac*;
+ un **promotore di T7**, specifico solo per la T7 RNA polimerasi (non per le RNA polimerasi batteriche) e che non è presente ovunque nel genoma procariotico;
+ un *operatore che può bloccare la trascrizione*;
+ un **polylinker**;
+ un'**origine di replicazione f1** (così che un plasmide a singolo filamento possa essere prodotto quando co-infettato con un fago M13)
+ un **gene di resistenza all'ampicillina**;
+ un'**origine di replicazione ColE1**.

Per iniziare il processo, un gene a scelta che chiamereno **YFG**, viene clonato nel sito del polylinker all'interno di un plasmide pET.

Sia il promotore T7 che l'operatore lac sono localizzati all'estremità 5' dell'YFG.
Quando lA T7 RNA polimerasi è presente e l'operatore lac non è represso, la trascrizione di YFG procede rapidamente.

Poichè T7 è un promotore virale, viene trascritto rapidamente e in abbondanza finchè la T7 RNA polimerasi è presente.

L'espressione di YFP (la proteina codificata dal gene da noi scelto) cresce rapidamente insieme all'aumento dell'mRNA trascritto da YFG.
In poche ore, YFP diventa uno the componenti maggiormente presenti nella cellula.

# Isolamento e purificazione di DNA e RNA

Il primo passo di qualunque tecnica di biologia molecolare consiste nell'isolare e purificare gli acidi nucleici. 

I dettagli sperimentali variano a seconda degli organismi, del tipo di acido nucleico che si vuole separare, dal tipo di esperimento che si deve effettuare, ecc. 

In tutti i casi dovremo:

+ rompere la parete o la membrana cellulare;
+ separare gli acidi nucleici dagli altri componenti cellulari;
+ separare gli acidi nucleici tra loro (per es. il DNA dal RNA).

## Rottura della parete o della membrana cellulare

Sebbene esistano metodi differenti per estrarre acidi nucleici dalle cellule, tutti hanno in comune alcune caratteristiche di base.

Per prima cosa è necessario procurarsi il materiale biologico di partenza, separandolo per centrifugazione dal terreno di coltura, come nel caso dei batteri, o frazionandolo ed omogenizzandolo, in caso di tessuti più complessi.

Il secondo passo consiste nella lisi delle cellule, affinchè queste rilascino i loro componenti cellulari (in funzione di diversi tipi cellulari vengono utilizzati metodi diversi). 
Nel caso delle cellule procariotiche oltre alle membrane cellulari bisogna distruggere la parete cellulare di peptidoglicano. 
In genere si utilizzano miscele di *lisozima*, *detergenti ionici* (tipicamente SDS) ed *EDTA*.

Il lisozima serve per indebolire la parete di peptidoglicano, l'SDS provvede a solubilizzare i lipidi delle membrane, mentre l'EDTA è un agente chelante che sequestra cationi bivalenti necessari per la stabilizzazione delle membrane e per l'attività di molti enzimi tra cui la DNasi.

Per cellule animali in genere bastano omogenizzazioni in tamponi
ipoosmolari e/o detergenti ionici e non ionici.

Nel caso di cellule protette da pareti cellulari più resistenti, come i lieviti o le cellule vegetali, è necessario rompere la parete con metodi fisici (cicli di congelamento-scongelamento, biglie di vetro, sonicazione, utilizzo di mortaio e pestello ecc.) oppure ricorrere a metodi enzimatici capaci di digerire la parete cellulare.

Dopo la rottura delle pareti cellulari e della membrana plasmatica, e la
separazione della frazione solubile da quella insolubile, si otterà una miscela complessa costituita da varie componenti cellulari come DNA, RNA, lipidi, mono e polisaccaridi, proteine e sali. 

La rottura delle cellule induce quasi sempre una parziale frammentazione del DNA cromosomale. 
Il cromosoma batterico, in particolare, che nella sua forma nativa si trova sempre in forma circolare, verrà ridotto in frammenti lineari più o meno lunghi in funzione del tipo di trattamento.
In tutti i casi è opportuno utilizzare il metodo più blando possibile per minimizzare eventuali danni al DNA, particolarmente a quello genomico.

## Separazione degli acidi nucleici da altri componenti cellulari

Una volta lisata la membrana (ed eventualmente la parete) bisogna separare gli acidi nucleici dagli altri componenti cellulari. 

A questo scopo è pratica comune precipitare gli acidi nucleici con alcol da soluzioni preventivamente deproteinizzate.

La rimozione delle proteine dal lisato cellulare è particolarmente importante sia perché tra le proteine sono presenti enzimi capaci di degradare gli acidi nucleici, sia per la presenza di proteine capaci di legarsi agli acidi nucleici impedendone la funzione e/o la purificazione.

Una tecnica comunemente utilizzata per rimuovere il grosso delle proteine dagli acidi nucleici consiste nel trattare la soluzione acquosa contenente gli acidi nucleici con solventi organici immiscibili (quasi) in acqua, tipicamente fenolo/cloroformio.

Emulsionando i due componenti si formano due fasi distinte, all'interfaccia delle quali si denaturano e si stratificano la maggior parte delle proteine.
Poiché l'acqua ed il fenolo sono solo parzialmente immiscibili, il fenolo deve essere equilibrato con una soluzione tampone.
Se si usa un fenolo equilibrato con un tampone a pH neutro o alcalino, sia il DNA che llRNA si ripartiranno nella fase acquosa superiore.

Se si effetua un'estrazione con un fenolo equilibrato con un tampone acido o con acqua (visto che il fenolo è naturalmente acido), il solo RNA ripartirà nella fase acquosa superiore mentre il DNA verrà trattenuto nella fase organica inferiore.

{img/estrazione-con-fenolo}

Poiché il fenolo è parzialmente solubile in acqua, alcune sue tracce possono rimanere in soluzione e inibire successivi trattamenti enzimatici (denaturando gli enzimi!). 
È importante, quindi, rimuovere ogni traccia di fenolo estraendolo
con cloroformio e, in qualche caso estraendo anche eventuali tracce di
cloroformio con etere che, infine verrà eliminato per evaporazione.

## Separazione degli acidi nucleici tra loro

Dopo aver rotto l'involucro cellulare e separato gli acidi nucleici dagli altri componenti solubili (proteine, carboidrati ecc.) avremo una miscela costituita prevalentemente da DNA genomico, DNA plasmidico ed RNA (rRNA, tRNA, mRNA).

### Separazione del DNA plasmidico da quello genomico

Per separare il DNA si compie un trattamento con Rasi seguito da una precipitazione selettiva con isopropanolo (a temperatura ambiente).

In questo modo si ottiene una miscela contenente DNA genomico e plasmidico.

Per separare i 2 DNA si sfruttano le differenze di peso molecolare mediante un ciclo di denaturazione e rinaturazione.

Per separare il DNA plasmidico da quello cromosomale si sfruttano le
differenze chimico-fisiche tra questi due tipi di macromolecole.

In particolare si utilizza la capacità che hanno i plasmidi, specie quelli di piccole dimensioni, di riassumere una conformazione covalentemente chiusa, in seguito a una moderata denaturazione.

In condizioni normali i plasmidi si trovano prevalentemente in forma **circolare superavvolta (supercoiled)** e, in misura minore, in forma circolare rilassata, caratteristica delle molecole che hanno perduto il superavvolgimento a causa di un interruzione in uno dei due filamenti (nick). Possono trovarsi anche in forma **lineare**, caratteristica delle molecole con una interruzione in entrambi i filamenti.

Sottoponendo la soluzione contenente gli acidi nucleici a condizioni
moderatamente denaturanti (per esempio in condizioni alcaline intorno
a pH 12), il DNA cromosomale si frammenta in lunghi frammenti lineari,
denaturandosi irreversibilmente, mentre i plasmidi, pur ridotti in condizioni denaturate, manterranno i due filamenti fisicamente concatenati (**denaturazione alcalina**).

Dopo aver riportato la soluzione in condizioni normali (pH neutro) neutralizzando con acido, mentre i frammenti cromosomali rimarranno
prevalentemente denaturati (si aggregano in un reticolo), i plasmidi
saranno in grado di rinaturarsi velocemente riassumendo una forma
circolare covalentemente chiusa.

Per facilitare la separazione tra DNA plasmidico e cromosomale, si usano
spesso tamponi contenenti **SDS** e ioni **K$^+$ che, legandosi alle proteine cromosomali, contribuiscono a creare un reticolo insolubile formato da un complesso nucleo-proteico cromosomale inglobato in micelle di SDS-K, che precipita.


### Separazione del'mRNA dai restanti RNA

Per separare l'RNA, invece, si compie un trattamento con Dnasi seguito da una precipitazione selettiva con LiCi e da un trattamento con guanidina tiocinato o con inibitori delle RNasi.

A questo punto, per separare l'mRNA dal resto dell'RNA si compie una purificazione per affinità su cellulosa.

### Precipitazione con alcol

Dopo l'estrazione fenolica e, in linea generale, per purificare ulteriormente o per concentrare gli acidi nucleici, si ricorre alla precipitazione con alcol.

In soluzioni alcoliche, infatti, gli acidi nucleici precipitano, insieme a parte dei sali, e possono essere efficacemente separati da altri componenti cellulari più solubili.

Anche la maggior parte delle proteine sono insolubili in alcol e co-
precipiterebbero in larga misura con gli acidi nucleici se non fossero
preventivamente rimosse.

Generalmente si usano 2 volumi di etanolo a (15' a -20°C) o 0,7 volumi di isopranolo (5' a temperatura ambiente). **???**

Dopo la precipitazione, che avviene in presenza di cationi monovalenti (Na$^+$) con funzione di carrier, la soluzione viene centrifugata, seccata e risospesa in adeguati tamponi alla concentrazione desiderata.

L'alcool etilico determina modificazioni strutturali degli acidi nucleici che ne inducono l'aggregazione e quindi la precipitazione.

Gli acidi nucleici possono essere completamente ed efficacemente separati anche mediante centrifugazioni differenziali. 

La purificazione del DNA su gradiente isopicnico di saccarosio in bromuro di etidio è stata molti anni il metodo di purificazione più usato. Nonostante questo metodo fornisca DNA di grande purezza, a causa della sua laboriosità e potenziale tossicità, è stato in gran parte soppiantato da metodi basati su resine a scambio ionico.

### Kit di rupificazione

In alternativa ai classici metodi di purificazione degli acidi nucleici esistono in commercio numerosi kit di isolamento e purificazione degli acidi nucleici che rappresentano un'alternativa sempre più utilizzata.

Esistono molti prodotti commerciali che garantiscono facilità d'uso, riproducibilità ed elevato livello di purificazione. 

Si basano essenzialmente sull'utilizzo di:

+ resine a scambio ionico (scambiatori anionici come la DEAE cellulosa);
+ matrici silicee;
+ gel filtration;
+ ultrafiltrazione.

Il principio sul quale si basa la purificazione degli acidi nucleici con matrice silicea è semplice: gli acidi nucleici si legano alle particelle della matrice in presenza di sali caotropici. 
Dopo avere lavato la matrice silicea, gli acidi nucleici vengono eluiti in tamponi a basso contenuto di sali e sono pronti per le successive reazioni (clonaggio, digestione con enzimi di restrizione, blotting,
sequenziamento manuale ed automatico, amplificazione, trascrizione inversa ecc.).













































