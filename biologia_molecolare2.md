# Tecniche di biologia molecolare
## Enzimi di restrizione

Enzimi che apportano tagli sui filamenti di DNA vengono chiamati **nucleasi**, e si distinguono in:

+ **endonucleasi**, se tagliano i legami fosfodiesterici interni in una molecola di DNA circolare o lineare;
+ **esonucleasi**, se si legano a una delle due estremità libere e iniziano a tagliare in maniera processiva verso l'altra estremità.

Gli enzimi di restrizione **(ER)** sono delle endonucleasi che provocano delle rotture interne a doppio filamento sul DNA in corrispondenza di particolari sequenze nucleotidiche.

Le endonucleasi di restrizione si legano ad una sequenza specifica di DNA, detta *"sito di riconoscimento"*, e tagliano entrambi i filamenti dell'elica.

Gli ER vengono distinti in ER del I, del II e del III tipo.
Gli **ER del I e del III tipo** portano l'attività di restrizione e metilazione nella stessa molecola.
Filamenti di DNA *non metilati* possono essere attaccati da questi enzimi, mentre filamenti metilati ne impediscono l'azione.
Questi enzimi riconoscono una specifica sequenza di nucleotidi, ma tagliano il DNA in posizioni non specifiche a una certa distanza dalla sequenza riconosciuta. Poichè il sito di taglio non corrisponde a una specifica coppia di basi, gli enzimi di restrizione del I tipo non sono quasi mai utilizzati nelle tecnologie del DNA ricombinante.

Gli **ER del II tipo** riconoscono anch'essi specifiche sequenze di nucleotidi, ma tagliano il DNA all'interno di quelle specifiche sequenze, chiamate **siti di taglio**.

La sequenza di riconoscimento per la maggioranza degli ER del II tipo è lunga 4-6 nucleotidi, ma esistono ER chiamati **rare cutter** che riconoscono sequenze più lunghe.
La frequenza di taglio di un ER è legata alla lunghezza della sequenza riconosciuta da quello specifico enzima. 
Una sequenza si 4 basi significa una probabilità di taglio di (1/4)$^4$, cioè 1 volta ogni 256 nucleotidi.

ER isolati da batteri differenti ma che riconoscono e tagliano la stessa sequenza nucleotidica sono chiamati **isoschizomeri**.

La maggior parte degli ER riconoscono sequenze sulla doppia elica del DNA definite **palindromiche**, ovvero possiedono la stessa sequenza sui due filamenti letti in direzione 5' $\rightarrow$ 3' (es. la sequenza 5'GAATTC3' riconosciuta dall'ER noto come EcoRI).

L'utilizzo degli enzimi di restrizione é molto semplice; la maggior parte di essi funziona in semplici tamponi tra pH 7 e 8, generalmente a 37°C. Le condizioni di utilizzo sono comunque sempre specificate dai fornitori.
Per definizione *un'unità di un enzima di restrizione è la quantità di enzima richiesta per digerire completamente 1 $\mu$g di DNA substrato in un'ora*.
Tutti gli enzimi, in condizioni non ottimali, danno l'**"effetto star"**, che consiste nella capacità dell'enzima di "confondersi" riconoscendo e tagliando sequenze simili, ma non identiche a quella target.
Per evitare l'effetto target é opportuno attenersi alle condizioni specificate dai fornitori, con particolare riferimento al glicerolo e alla quantità di enzima, che non devono essere mai in eccesso.

### Nomenclatura

Per assegnare in modo chiaro ed univoco un codice ad un enzima si è deciso che:

+ le prime **3 lettere** sono prese dal nome del batterio di origine. La prima lettera dal genere e le altre due dalla specie (es. Eco **E**scherichia **co**li);
+ tipi differenti dello stesso organismo sono indicati da una **quarta lettera** minuscola (es. Hin**d** Haemophilus influenzae sierotipo Rd, Hin**f** Haemophilus influenzae sierotipo Rf);
+ segue una lettere maiuscola o numero che identificano un ceppo particolare di batterio (Eco**R** Escherichia coli ceppo RY13);
+ un **numero romano** indica l'ordine di scoperta qualora dallo stesso batterio vengano isolati enzimi diversi.

**Esempio**

**EcoRI**:

+ **E** = genere Escherichia;
+ **co** = speie coli;
+ **R** = ceppo RY13;
+ **I** = prima endonucleasi isolata.

Sequenza riconosciuta: G/AATTC - CTTAA/G

**BamHI**:

+ **B** = genere Bacillus;
+ **am** = specie amyloliquefaciens G/GATCC;
+ **H** = ceppo H;
+ **I** = prima endonucleasi isolata.

Sequenza riconosciuta: G/GATCC - CCTAG/G 


Come fa un organismo che produce una endonucleasi a proteggersi dall'azione dell'enzima prodotto?
Tramite un sistema di **protezione per modificazione**.

Dopo aver effettuato il taglio, l'ultimo nucleotide (quello rimasto "scoperto") viene metilato. La metilazione non altera la normale struttura del DNA, ma inibisce il taglio.

Il taglio tramite enzimi di restrizine può generare diversi tipi di estremità.

Esistono ER in graod di tagliare entrambi i filamenti della doppia elica nello stesso punto, generando delle **estremità piatte (blunt end)**; altri ER, invece, operano un taglio obliquo lasciando delle **estremità sporgenti**.
In questo caso le estremità possono sporgere al 5' o al 3' e vengono chiamate **sticky end**.
Frammenti di DNA generati da tagli con ER possono essere legati tra di loro o inseriti in un vettore di clonaggio in provetta utilizzando l'enzima DNA ligasi.

## L'elettroforesi su gel

Molecole diverse di DNA, RNA  e proteine possono essere separate modiante elettroforesi su gel perchè differiscono nella loro carica elettrica, dimensione e struttura.

L'elettroforesi rappresenta lo strumento classico di cui si serve un biologo molecolare per *separare*, *identificare* e *isolare* frammenti di DNA o RNA.

Le prime elettroforesi, che venivano eseguite in fase liquida, sono state soppiantate da quelle in fase solida, più riproducibili. 
Le matrici solide generalmente usate sono costituite da:

+ **gel di agarosio**, uno zucchero solubile in acqua alla temperatura di ebollizione che diventa solido quando si raffredda, formando una matrice attraverso dei legami idrogeno tra le catene lineari;
+ **gel di poliacrilammide**, si forma tramite copolimerizzazione di acrilammide, un monomero solubile in acqua, e di un agente che forma legami trasversali così da formare un reticolo tridimensionale.

I gel più utilizzati in biologia molecolare sono quelli di agarosio con
percentuali varianti tra 0,7 e 2%. 
A basse concentrazioni di agarosio si risolvono meglio i pesi molecolari alti, mentre ad alte concentrazioni si risolvono meglio i pesi molecolari bassi. Per risolvere frammenti di DNA molto piccoli (tra 200 e 1 bp) si ricorre a gel di poliacrilammide.

I due tipi di gel differiscono per le dimensioni dei pori del reticolo: gel con pori grandi permettono la separazione di molecole di grandi dimensioni, gel con pori piccoli separano molecole di dimensioni limitate.

La separazione tramite elettroforesi consiste nel movimento di una molecola carica sottoposta ad un campo elettrico. Questo campo elettrico viene creato dal collegamento di un alimentatore di corrente elettrica all'apparecchio per l'elettroforesi.

Poiché gli acidi nucleici sono molecole cariche negativamente, a causa dei loro gruppi fosfato (in un tampone neutro o alcalino), migreranno verso il polo positivo (anodo) e si separano in base alla loro massa molecolare.

(immagine 66)

Per poter visualizzare lo spostamento dei frammenti di DNA su un gel, altrimenti invisibili, è necessario applicare un colorante specifico come il *bromuro di etidio* (mutageno). Questa sostanza si intercala tra i due filamenti di DNA ed emette una fluorescenza di colore arancione quando esposta a raggi UV.

(immagine 64)

Il DNA sottoposto ad un campo elettrico migra ad una *velocità
proporzionale all'inverso del log 10 del suo peso molecolare*.

**D = a-b(LogM)**

Dove:

+ **D** è la distanza coperta;
+ **M** è il peso molecolare del frammento;
+ **a** e **b** sono costanti.

Facendo migrare il campione in esame insieme ad uno standard di frammenti con pesi molecolari di dimensione nota è possibile estrapolare il peso molecolare del campione ignoto.

Utilizzando questa serie di frammenti di DNA a peso molecolare noto è possibile costruire una **curva di taratura**, dove ogni banda sul gel corrisponde ad un punto le cui coordinate sono costituite, in **ascissa**, dalla **distanza in cm dal pozzetto** e in
**ordinata**, dal **Log 10 del peso molecolare**. 
Congiungendo tutti i punti, riportati su un grafico semi-logarittimico, si dovrebbe formare una linea approssimativamente retta,da cui, nota la distanza dal pozzetto percorsa da una banda incognita, è possibile estrapolare il peso molecolare approssimativo.

(immagine 65)

# RNA interference

L'RNA interference consiste nel processo biologico in cui molecole di RNA inibiscono l'espressione di un gene (solitamente causando la distruzione di specifiche molecole di mRNA).

Storicamente questo fenomeno è stato indicato anche con altri nomi, quali:

+ **co-soppressione**. Il fenomeno dell'interferenza è stato per prima scoperto nei vegetali. Nel 1990, Jorgenson e colleghi, cercando di ottenere un fiore di colore scuro, avevano introdotto un **transgene** per la *chalone synthase* (responsabile della sintesi del pigmento anthocyanina) in cellule di petunia. Sorprendetemente, ottennero un fiore variegato. L'analisi delle cellule bianche rivelò che in queste erano assenti i mRNAs sia del transgene che del gene endogeno
Con co-soppressione (1990) si indica il fenomeno per cui l'introduzione di un gene esogeno codificante per l'*enzima calcone sintasi* in petunia, silenzia sia il gene esogeno che quello endogeno;
+ un altro esempio di RNA interference è il **post-transcriptional gene silencing (PTGS)** del *gene par-1* di C. elegans tramite l'introduzione di RNA antisenso. 
Lo stesso risultato venne ottenuto mediante l'introduzione di RNA senso usato come controllo negativo;
+ un altro fenomeno simile al PTGS è il **quelling**. Questo fenomeno è stato osservato in petunia ma avvenuto in una coltura di N. crassa trasformata con un plasmide contenente il *gene al1*.

Nel 1998 gli studiosi Fire e Mello catalogarono tutti questi fenomeni
isolati sotto un principio comune: RNA interference (**RNAi**).

Continuando gli studi su C. elegans di Guo & Kemphues per cercare delle spiegazioni agli eventi da essi osservati, Fire e Mello ipotizzarono che le preparazioni di RNA antisenso contenessero piccole quantità di RNA senso e che la formazione di molecole ibride a doppio filamento (**dsRNA**) fosse responsabile del silenziamento genico osservato con l'anti-senso (RNAi).


I meccanismi responsabili del fenomeno possono essere:

+ il silenziamento trascrizionale del gene;
+ il silenziamento post-trascrizionale del gene (PTGS), l'mRNA è sintetizzato e poi degradato.

Nel 1995 Guo & Kemphues, per dimostrare che avevano clonato il gene par-1 (un gene necessario per la divisione mitotica dello zigote) di C.elegans, condussero esperimenti di PTGS con oligonucleotidi antisenso.

Nel 1998, Fire & Mello circonstanziarono che l'iniezione di dsRNA era un modo molto efficiente per ottenere fenotipi mutanti in C.elegans.

L'introduzione di una soluzione contenente filamenti di RNA senso ed antisenso era almeno dieci volte più efficace dei filamenti singoli.

Le analisi elettroforetiche mostrarono che, all'interno dell'organismo, il materiale iniettato si conformava per la maggior parte come doppio filamento (dsRNA, RNA double strand) infatti le molecole di ssRNA (single strand RNA) venivano rapidamente degradate nel citoplasma.

Di contro, osservarono che un tempo prolungato tra l'iniezione del filamento senso e di quello antisenso dava un calo drastico dell'efficienza fino alla totale assenza di effetto.

Sorprendentemente, gli effetti di questa interferenza genica si
mostravano sia nei soggetti iniettati che nella progenie.


Che cos'è la RNA interference? Un fenomeno in cui l'espressione (o introduzione) di un RNA a doppio filamento (dsRNA) in un diverso range di organismi e tipi cellulari causa la degradazione di un mRNA bersaglio complementare.

# Formazione e azione di siRNA e miRNA

## Biochimica dei siRNA (small interfering RNA)

**Fase iniziatrice**: Dicer processa lunghe molecole di dsRNA in siRNA maturi di 21-23 bp con 2 nt liberi e complementari al 3' e un monofosfato al 5'.

**Fase effettrice**: siRNA viene incorporato nel RISC che lo denatura. Il filamento antisenso giuda il legame del RISC all'mRNA bersaglio causandone la degradazione.

Possibili applicazioni degli siRNA sono:

+ determine la funzione di un gene;
+ studiare "persorsi biologici" (pathways)
+ identificare e convalidare bersagli;
+ generare modelli knock-out.

Nel futuro gli siRNA potranno essere utilizzati per terapie mediche.

Esistono almeno 5 modi per produrre gli siRNA:

1. tramite sintesi chimisa;
2. tramite trascrizione in vitro;
3. tramite digestione di lunghi dsRNA da parte di un enzima della pamiglia delle RNA polimerasi III;
4.  tramite l'espressione in cellule da un siRNA plasmidiale o un vettore virale (?);
5. tramite l'espressione in cellule da un siRNA derivato da PCR (??).

Nel disegno di un siRNA funzionale vi sono parametri di basi che devono essere considerati:

+ la regione target deve essere *a valle del codone di inizio* della
traduzione, ad una distanza che varia dalle 50 alle 100bp;
+ l'mRNA target deve avere dal 5' al 3' una sequenza AA(N19)UU;
+ l'mRNA target deve avere un contenuto in GC del 30-70%;
+ devono essere evitate le regioni UTR (untraslated region) sia al 3' che al 5';
+ il filamento antisenso deve essere termodinamicamente instabile al 5' rispetto al 3', favorendone l'incorporazione nel RISC;
+ devono essere evitate regioni polimorfiche tranne nel silenziamento allele-specifico;
+ devono essere evitati più di 3 mismatch rispetto al target.


## Biogenesi dei miRNA

Alcuni miRNA derivano da sequenze non codificanti, altri sono
contenuti all'interno di regioni introniche di sequenze codificanti
spesso nello stesso senso, suggerendo una possibile trascrizione
insieme al gene ospite.

I miRNA vengono inizialmente trascritti dall'*RNA polimerasi II* a partire dal loro stesso promotore a **pri-miRNA (primary miRNA)**

I pri-miRNA sono sequenze a singolo filamento con struttura secondaria a forcina, e complementarietà interna alla sequenza non perfetta.
I pri-miRNA vengono processati da parte di una ribonucleasi di
classe III (RNAsi III), chiamata **Drosha**, in **pre-miRNA (precursor mi-RNA)**. I pre-miRNA sono sequenze a singolo filamento lunghe circa 70 nt, con una struttura secondaria a forcina e una complementarietà interna non perfetta.

I pre-miRNA vengono trasportati dal nucleo al citoplasma attraverso l'**Esportina 5** in cooperazione con **Ran-GTP**.

Nel citoplasma, ad opera di Dicer, i pre-miRNA vengono tagliati a miRNA maturi. Questi sono formati da sequenze di dsRNA lunghe circa 21-25 nt, prive della struttura a forcina che viene tagliata da Dicer. Questo taglio lascia 2 nt simmetrici liberi al 3' ed un monofosfato al 5' della stessa terminazione.

{img/miRNA}

## Gli RNAi

RNAi sono conservati tra le specie.

Le funzioni biologiche degli RNAi sono diverse, tra cui:

+ *regolazione dell'espressione genica* (tempi di sviluppo, specificità del tessuto, adattamento);
+ *difesa da patogeni* quali i virus a dsRNA.

Come possiamo utilizzare queste conoscenze per studiare i meccanismi delle malattie e curarle?

Gli RNAi possono essere utilizzati per diversi scopi:

+ per **indurre la sovraespressione di un determinato gene**. Questo meccanismo viene detto **"gain of function"** ed è un metodo efficace con cui identificare i geni che influenzano lo sviluppo di particolari strutture o tipi di cellule. Il gain of function induce un incremento dell'espressione del gene bersaglio, o un espressione "de novo" del gene, influendo sul fenotipo cellulare;
+ per **inserire nuovi geni** nel DNA ospite. La differenza tra organismi **knock-in** e organismi transgenici, è che nel knock-in il gene estraneo è inserito in un locus specifico nel genoma bersaglio tramite ricombinazione omologa. Negli organismi transgenici invece, il gene che si desidera integrare può finire ovunque nel genoma dell'organismo ospite;
+ per **identificare il ruolo di un determinato gene** attraverso il suo spegnimento tramite **"loss of function"**. La RNAi permette di svolgere studi di loss of function *senza eliminare fisicamente un gene* tramite un processo di **"knock-down**. Il processo di eliminazione fisica di un gene per impedirne l'espressione viene definito **knock-out**. I vantaggi di questa modalità consistono tra l'altro nella possibilità di ripristinare l'attività del gene silenziato attraverso l'utilizzo di sistemi di transgenesi condizionale.

Le possibili molecole sintetizzabili in vitro sono:

+ **siRNA** che una volta introdotti non vengono processati da Dicer e
vengono direttamente incorporati nel RISC;
+ **lunghe molecole di dsRNA** che invece devono essere processate
da Dicer;
+ **short hairpin RNA (shRNA)**, molecole di RNA di 50-70 nt che formano una struttura a forcina con perfetta complementarietà dei bracci e che tagliati da Dicer generano siRNA funzionali;
+ **miRNA-based hairpin RNA**, duplex di RNA a forcina con una non perfetta complementarietà tra i bracci. Emulano i pre-miRNA che fuoriescono dal nucleo e una volta processati da Dicer generaro i miRNA;


### Produzione di shRNA

Esistono diversi metodi per la produzione di shRNA:

+ **sintesi chimica di oligonucleotidi** di 50-70 nt, appaiati e ligati in un vettore. È un metodo relativamente semplice, anche se la
sintesi di un oligonucleotide così lungo è più soggetta ad errori;
+ **trascrizione ad opera dell’RNA polimerasi III** a partire da un
unico promotore (U6 o H1), di sequenze invertite codificanti per
uno shRNA a forcina. Questo sarà poi processato da Dicer, i cui
tagli genereranno siRNA funzionali per complessi RISC.

### RNAi in cellule di mammifero

Nei mammiferi si riscontrano molte più difficoltà nell'indurre l'RNAi perché, a seguito dell'introduzione di una molecola di dsRNA, si ha
l'attivazione di un sistema di **inibizione totale dell'espressione**, piuttosto che di un sistema sequenza-specifico.
Questo avviene poichè interagisce con le molecole di dsRNA una proteina kinasica (PKR) che scatena la risposta immunitaria dell'interferone, bloccando globalmente la trascrizione.
Utilizzando i siRNA, invece, si è riusciti ad indurre il silenziamento sequenza-specifico, senza scatenare la risposta interferonica.
Questa scoperta è molto utile al fine di poter progettare metodologie di somministrazione umana a scopo terapeutico.

In linea di principio, qualunque malattia causata dall'espressione di
forme aberranti di un gene (es. mutazioni), o dall'aumento dell'espressione di una o di un numero limitato di proteine, può essere trattata mediante **RNAi therapy**.
Anche patologie parassitarie (virus, batteri, protozoi) rappresentano un
potenziale bersaglio terapeutico.

{img/miRNA-therapy}

I vantaggi principali degli RNAi sulle piccole molecole e proteine  terapeutiche sono che tutti i bersagli, inclusi quelli che rispondo e non rispondono ai farmaci, extracellulari e intracellulari e alleli mutanti possono essere "mirati" con gli RNAi. Uno dei maggiori vantaggi delle tecnologie basate sul riconoscimento di sequenze è la possibilità di produrre farmaci precisamente "disegnati" per quasi ogni sequenza bersaglio (sia codificante che non codificante), indifferentemente dalla funzione del prodotto genico.

### Terapia basata sui siRNA

Lo scopo della terapia basata sui siRNA è quello di **attivare la degradazione** di un selettivo mRNA per un efficiente silenziamento genico.
La terapia con RNAi offre potenzialmente diversi vantaggi:
quali:

+ una diffusa applicabilità;
+ precisione terapeutica;
+ selettività;
+ assenza di effetti indesiderati;
+ relativa facilità di produzione;
+ bassi costi di produzione.

Possibili malattie alle quali potrebbe essere applicata la siRNA therapy sono: infezioni virali, cancro, malattie metaboliche, malattie genetiche, ecc...

È possibile raggiungere il pathway endogeno attraverso 2 vie:

+ tramite un *vettore virale* per esprimere shRNA;
+ tramite un *siRNA che mimi il prodotto di clivaggio di Dicer nel citoplasma* incorporandosi direttamente nel complesso RISC.

I siRNA sono più attraenti dal punto di vista terapeutico perchè entrano nel pathway dell'RNAi in modo consistente e prevedibile, e non interferiscono con la regolazione genica da parte dei miRNA endogeni.
Per tali motivi i siRNA sono più avanzati negli studi clinici e
preclinici della terapia con RNAi.

#### Selezione in vitro

Ci sono diversi step nell'identificazione di possibili siRNA candidati:

+ un *disegno bioinformatico*;
+ **studi in vitro** per determinare:
	1. l'*efficacia di silenziamento*;
	2. l'*assenza di effetti indesiderati*;
	3. l'introduzione di eventuali modificazioni chimiche per aumentare **stabilità** e **specificità**
+ *selezione delle tecniche* più adatte *per il trasferimento* in cellule/tessuti/organismi specifici da trattare.

Le 3 principali caratteristiche da tenere in considerzione nel disegno e nella selezione di un siRNA candidato sono:

+ **potenza**;
+ **speicficità**;
+ **stabilità**.

Sono da evitare o minimizzare 2 tipi di effetti:

+ il silenziamento di geni che mostrano omologia parziale con il siRNA;
+ lo sviluppo di una risposta immunitaria.

Oggi è possibile selezionare nell'arco di poche settimane/mesi siRNA candidati potenti, stabili e specifici in vitro e con effetti indesiderati mitigati.

La **potenza**. 
Un siRNA candidato nel silenziamento di un gene target è *potente* quando la sua attività si esplica a **basse concentrazioni** (solitamente nanomolari). 
siRNA potenti possono essere identificati mediante l'uso di algoritmi, o valutando tutte le possibili sequenze generabili da un mRNA, per poi selezionare quelle che inducono silenziamento efficiente a concentrazioni più basse. 
Sono più potenti siRNA di 27nt rispetto a 19nt ma sono più difficili da sintetizzare e hanno maggiore probabilità di attivare una risposta immunitaria.

La **specificità**. 
Un siRNA è *specifico* quando è in grado di indurre il **silenziamento solo di uno specifico mRNA**.
Esistono 2 problemi che limitano la specificità di un siRNA:

1. il riconoscimento e, quindi, **silenziamento di mRNA con
omologia parziale**;
2. lo sviluppo della **risposta immunitaria** per *attivazione della PKR*, ad opera di molecole di dsRNA lunghi più di 30nt, e per *attivazione del TLR (toll-like receptor)*, espresso sulle cellule dendritiche, con conseguente produzione di interferone e di citochine pro-infiammatorie. 
Sembra che le isole CpG del filamento antisenso attivino il TLR.

Il problema del silenziamento di mRNA con omologia
parziale può essere minimizzato attraverso:
		
+ un **disegno attento dei siRNA**;
+ una **modificazione chimica dei ribosi** nel filamento guida, e in particolare attraverso l'aggiunta di un gruppo metilico al gruppo OH in 2' del nt 2 (2'-O-Met).

La **stabilità**. 
Gli siRNA sono normalmente degradati nel plasma umano con un'emivita di pochi minuti. Per **aumentare l'emivita** e quindi la *stabilità* dei siRNA, si introducono diverse modificazioni chimiche:
+ l'aggiunta di un fosforotioato (P=S) al 3' protegge dalla
digestione da parte delle esonucleasi;
+ l'aggiunta del gruppo metile o di un atomo di Fluoro al 2' del ribosio (2'-O-Met o 2'-F) protegge dalla digestioni dalle endonucleasi.

Queste modificazioni sono necessarie perché è importante
che i siRNA raggiungano intatti i tessuti bersaglio.

Un'altra considerazione importante nel disegnare un siRNA a scopi terapeutici è trovare, se possibile, un target conservato tra le specie più usate per gli studi di efficacia e sicurezza, per costruire un solo farmaco candidato da usare dalle fasi di ricerca di base fino agli studi clinici. 
Perciò, l'approccio più prudente da seguire è quello di identificare diverse molecole candidate adatte a studi in vivo per poi selezionare quelle più potenti, specifiche, stabili e con minore attività immuno-stimolatoria.

#### Vie di somministrazione in vivo

Oggi esistono diverse metodologie di trasporto dei siRNA in vivo
quali:

+ naked siRNA;
+ coniugati;
+ liposomi/lipoplesso;
+ complessi con peptidi/proteine;
+ complessi con anticorpi

La sfida principale riguarda lo sviluppo di tecnologie di trasporto
direttamente nella cellula/tessuto bersaglio per diminuire la dose di efficacia richiesta, e diminuire gli effetti tossici e indesiderati legati ad una somministrazione sistemica.

I **naked siRNA**.
Consistono in una somministrazione di siRNA (modificato o meno) in
soluzione salina o in eccipienti semplici come il destrosio 5% (D5W).

La semplicità di formulazione e somministrazione direttamente nel tessuto bersaglio rende questa via l'approccio terapeutico più attrattivo.

I naked siRNA possono essere somministrati in diverse zone:

+ **nell'occhio**. 
L'iniezione intravitreale L’iniezione intravitreale di naked siRNA in soluzione salina
vs VEGF rallenta la neovasvolarizzazione oculare in modelli
animali di AMD (age-related macular degeneration).
• L’iniezione intravitreale di naked siRNA in soluzione salina
vs VEGFR1 riduce l’area di vascolarizzazione oculare nello
stesso modello animale.
• Partono clinical trials per testare siRNA vs VEGF in pazienti
affetti da AMD.di naked siRNA in soluzione salina **vs VEGF** *rallenta la neovascolarizzazione oculare* in modelli animali di AMD (age-related macular degeneration).

L'iniezione intravitreale di naked siRNA in soluzione salina **vs VEGFR1** *riduce larea di vascolarizzazione oculare* nello stesso modello animale.

Partono clinical trials per testare siRNA vs VEGF in pazienti
affetti da AMD;

+ **nel polmone**.
L'instillazione intranasale di naked siRNA in soluzione salina **vs
geni di RSV (respiratory syncytial virus)** e del **virus della parainfluenza**, due delle principali cause di ospedalizzazione pediatrica negli USA oggi, ne riduce lo sviluppo e quindi i sintomi patologici quali: produzione di leucotrieni, infiammazione polmonare e stress respiratorio.

La somministrazione intranasale di naked **siRNA in D5W vs i geni del CoronaVirus in modelli animali di SARS (severe acute respiratory syndrome)**, ne inibisce la replicazione virale e ne riduce gli effetti patologici.

La somministrazione intranasale di naked siRNA **vs la eme-ossigenasi1 (HMOX1)**, risulta in un aumento dell'apoptosi dopo riperfusione a seguito di ischemia, dimostrando che in questo caso l'induzione di tale gene è **protettivo**;

+ **nel SNC**. 
La somministrazione di naked siRNA in soluzione salina intracerebrovascolare, intratecale o intraparenchimale, causa il silenziamento di specifici mRNA target neuronali in più regioni del SNC e periferico.
Poiché è richiesta una dose maggiore e poiché l'assunzione dei siRNA non è omogenea, sembra essere favorita la somministrazione di coniugati lipidici.

Gli **siRNA coniugati**.
Consistono nella coniugazione covalente dei siRNA a molecole bersaglio quali:

+ molecole lipofile;
+ proteine;
+ peptidi;
+ aptameri.

Le molecole vengono, generalmente, coniugate al 5' o al 3' del filamento senso senza distruggere l'attività di quello antisenso.

+ **Coniugazione con colesterolo**.

L'iniezione intravena di **siRNA vs l’APOB** il cui filamento senso è coniugato al 5' con una molecola di colesterolo, causa una riduzione del suo mRNA nel fegato e nel digiuno, una riduzione della proteina nel plasma e, quindi, una riduzione del colesterolo sierico.

+ **Conigazione con liposomi e lipoplessi**.

I **liposomi** sono vescicole costituite da un compartimento acquoso racchiuso in un doppio strato fosfolipidico che, fondendosi con la membrana delle cellule, permette il trasporto in esse del materiale contenuto nel compartimento acquoso.

Farmaci polari possono essere incorporati nel compartimento acquoso ed essere, quindi, veicolati nelle cellule tramite i liposomi.
In questo modo si migliorano le caratteristiche farmaco-cinetiche del farmaco e se ne riduce la tossicità.

I **lipolessi** sono costituiti da lipidi che complessano con gli acidi nucleici a formare particelle amorfe: solitamente si formano miscelando siRNA con alcuni agenti di trasfezione come la lipofectamina e il transit-TKO.

Sia i liposomi che i lipoplessi sono molto usati, sia in vivo che in vitro, per il trasferimento di siRNA.
Sono stati descritti diversi successi sia di somministrazione locale che sistemica con entrambi.

La **somministrazione sistemica** consiste in una *somministrazione intravena di lipoplessi* con **siRNA vs l’APOB (apolipotroteina B)** ne riduce notevolmente i livelli di mRNA e, quindi, di colesterolo, sia in modelli murini che in primati non umani.

La somministrazione intravena di lipoplessi cationici contenenti **siRNA vs il TNF**, ne riducono la produzione a livello delle giunture del ginocchio in modelli animali di artrite remautoide.

La somministrazione intravena di liposomi contenenti **siRNA vs
la CAVEOLINA-1** ne riduce l'espressione di circa il 90% nell'endotelio polmonare di topo e risulta, quindi, in un aumento della permeabilità vascolare.

La **somministrazione locale** consiste nella *somministrazione subretinale di lipoplessi* in Transit-TKO con **siRNA vs VEGF**, riduce la neovascolarizzazione coroidale in modelli animali di AMD.

La somministrazione subcongiuntivale di lipoplessi in Transit-TKO con **siRNA vs TGF$\beta$R2**, sopprime l'infiammazione e la fibrosi oculare in modelli animali.

L'*iniezione intracranica* di liposomi contenenti **siRNA vs geni virali**, protegge il topo dal virus dell'encefalite giapponese.

L'*iniezione intratumorale* di lipoplessi con **siRNA vs i geni E6-E7 del PV** causa una inibizione della crescita tumorale e la soppressione dell'espressione dei geni virali.

+ **Coniugazione con peptidi/polimeri**

I siRNA possono essere complessati con peptidi e polimeri cationici attraverso interazioni ioniche con i loro fosfati carichi negativamente, a formare nanoparticelle stabili.

Importante è prevenire l'aggregazione e controllare le dimensioni delle particelle, solitamente tramite l'incorporazione di molecole come il PEG (polietilen glicole) che le stabilizzano e ne migliorano le proprietà farmacocinetiche.

All'interno di queste particelle possono essere introdotte altre
molecole quali *trasferrina*, *folati*, *mannosio*, *galattosio*, *peptide RGD (Arg-Gly-Asp)* che migliorano e accelerano la specificità di trasporto del siRNA solo vs le cellule che ne esprimono i recettori.

Un polimero che si può complessare ai siRNA è il **PEI (polietilen-immina)**.
Questo è un polimero sintetico, lineare o ramificato, con elevata
densità di cariche cationiche. Il PEI interagisce elettrostaticamente con la superficie delle cellule, viene poi endocitato e, infine, disgrega gli endosomi in quanto causa un aumento del flusso protonico e di acqua che li disgrega, permettendo così il rilascio del siRNA nel
citoplasma.

Complessi con PEI di siRNA vs pleiotropina, VEGF e HER2 (human epidermal growth factor receptor 2) hanno attività antitumorale.
Lo svantaggio risiede nell'estrema tossicità associata ad elevate dosi di PEI.

Residui di istidina e poli lisina sembrano avere efficacia in vitro simile al PEI.

+ **Complessi con anticorpi**

Gli anticorpi possono essere usati per trasportare siRNA in specifiche cellule bersaglio.

#### Clinical trials

Ci sono 3 clinical trials in fase di studio:

1. **siRNA CAND5 vs tutte le isoforme del VEGF-A** ha completato la fase 2 dei clinical trials in pazienti con una forma progressiva grave di AMD.
Vantaggi:

	+ facilità di somministrazione direttamente sul tessuto
bersaglio;
	+ ambiente oculare relativamente libero da nucleasi;

2. **siRNA 0-27 vs il VEGFR1** ha completato la fase 1 in assenza di tossicità in pazienti affetti da edema maculare diabetico;
3. **siRNA ALN-RSV01 vs il gene del nucleocapside di RSV** ha completato la fase 1 in assenza di tossicità in 100 volontari sani.
Vantaggi:

	+ facilità di trasporto direttamente nel tessuto bersaglio (cellule endoteliali polmonari);
	+ ambiente polmonare relativamente povero di nucleasi;
	+ la somministrazione per inalazione non è invasiva;
	+ assenza di metabolismo di primo passaggio che comporta la riduzione della dose necessaria e degli effetti avversi sistemici.


La sfida principale nell'usare RNAi a scopi terapeutici rimane quella di superare una serie di barriere che limitano l'efficienza di trasporto dei siRNA all'interno delle cellule/tessuti bersaglio, quali:

+ il raggiungimento delle adeguate proprietà farmacocinetiche per aumentare l'esposizione del farmaco alle cellule bersaglio;
+ il raggiungimento di meccanismi che promuovano l'assunzione cellulare e il rilascio del farmaco nel citoplasma;
+ l'instabilità nel siero;
+ l'eliminazione tramite le urine;
+ la distribuzione non specifica.

È inoltre, necessaria l'introduzione di **sistemi REPORTER** sia esogeni che endogeni per identificare l'effettivo trasporto del farmaco all'interno delle cellule. È fondamentale, infine, rispettare i parametri di efficacia e sicurezza.

I limiti nell'utilizzo di terapie basate sull'RNA interference sono:

+ gli elevati dosaggi richiesti;
+ la necessità di ripetere i trattamenti;
+ i costi dei farmaci a siRNA;
+ la stabilità nell'organismo;
+ gli effetti "off-target", ovvero il rischio di reprimere altri geni.

Gli RNAi ci permettono di investigare le funzioni dei vari geni spegnendoli in maniera selettiva.









