# Reazione a catena della polimerasi (PCR)

La tecnica della PCR fu ideata nel 1983 da Kar B. Mullis.
Questa tenica permette di selezionare e amplificare, da una preparazione eterogenea di DNA, un particolare tratto che ci interessa, producendone un grandissimo numero di copie (può amplificare un tratto di DNA per più di un milione di volte).

Il processo di PCR prevede un certo numero di cicli (30-35) ed ogbu ciclo cinsiste di 3 passaggi:

1. **denaturazione** del DNA, avviene alla temperatura di 95°. Il DNA stampo viene denaturato, i due filamenti si separano;
2. **appaiamento**, avviene alla temperatura di 55° circa. In questo passaggio i primer si appaiano con il DNA stampo.
3. **sintesi**, avviene alla temperatura di 72°.

La PCR consiste sostanzialmente in una replicazione in viste di un frammento di DNA ottenuta mediante una DNA polimerasi e 2 oligonucleotidi lunghi 20-30 nt che fungono da inneschi (**primer**) per la replicazione e che sono responsabili della specificità dell'amplificazione.

Gli elementi necessari per la PCR sono:

+ **2 oligonucleotidi** complementari alle 2 regioni che si trovano sui filamenti opposti del DNA stampo, ai lati della regione che si vuole amplificare;
+ un **DNA stampo** che contenga la regione da amplificare;
+ una **polimerasi termostabile** (non deve denaturarsi se portata a 95°);
+ i 4 deossinucleotidi trifosfati.

Il DNA di partenza viene denaturato e poi ibridato con i 2 inneschi che vanno a legarsi ciascuno su un filamento a un estremo della regione da amplificare.
Utilizzando i nucleosidi trifosfato che sono aggiunti alla miscela, la DNA polimerasi allunga gli inneschi in direzione 5' $\rightarrow$ 3'.

I primi tentativi vennero fatti utilizzando DNA polimerasi I di E.coli, che però veniva inattivata alla temperatura di denaturazione del DNA.

Mullis introdusse l'utilizzo di polimerasi estratte da organismi termofili per effettuare il protocollo PCR.
In questo modo non era più necessario ripreparare la miscela di amplificazione alla fine di ogni ciclo.

La polimerasi termostabile maggiormente usata è quella di *Thermophilus aquaticus*, la **Taq polimerasi**.

Tutti questi passaggi vengono effettuati in appositi strumenti che sono, in sostanza, dei piccoli termostati in cui è possibile programmare in maniera opportuna innalzamenti e abbassamenti della temperatura.

Un esempio di ciclo di amplificazine è:

1. **denaturazione**: 30 sec a 95°C per denaturare il DNA;
2. **associazione** (annealing): 30 sec a 40°-60°C per favorire làassociaizone specifica degli inneschi;
3. **sintesi**: 2 min a 72°C, che è la temperatura ottimale per la Taq pol.


Esistono attualmente in commercio un gran numero di DNA polimerasi
termostabili con caratteristiche diverse:

La *Taq* è priva di attività esonucleasi 3' $\rightarrow$ 5' (correzione bozze) ed incorpora nucleotidi sbagliati con la frequenza piuttosto alta di 1 ogni (circa) 10 Kb. 
Nello stesso tempo però, è sufficientemente processiva per amplificare senza problemi DNA stampo lunghi 3-5 Kb.

Caratteristiche della Taq polimerasi:
+ attività **DNA polimerasica** 5' $\rightarrow$ 3';
+ attività **esonucleasi** 5' $\rightarrow$ 3';
+ attività di **Terminal transferasi** (debole).

Viceversa, gli enzimi con attività esonucleasica 3' $\rightarrow$ 5' come Pwo e Pfu sono molto più fedeli (1-3 errori ogni 1000 Kb), non presentano attività di terminal transferasi, ma hanno una bassa processività.

Enzimi come la *Taq* vanno bene per la maggior parte delle applicaizoni in PCR.

Enzimi con attività esonucleasica 3' $\rightarrow$ 5' come *Pfu* invece, sono necessari quando è molto importante amplificare in modo fedele il DNA stampo. 

Esistono pure in commercio muschele che sommano le proprietà più vantaggiose di entrambi gli enzimi.

Esistono delle "Golden Rules" per disegnare delle buone coppie di primer:

1. la lunghezza del primer deve essere compresa tra **18 e 22 paia di basi**;
2. se possibile, il primer deve avere una sequenza che contenga una **percentuale di GC vicina al 50-60%**;
3. la temperatura di annealing deve essere compresa tra 50°C e 65°C, o comunque non deve mai essere troppo bassa (per evitare problemi di aspecificità);
4. il primer non deve contenere lunghi tratti di nucleotidi ripetuti (es. GGGGGG);
5. la temperatura di annealing teorica (T$_a$) del **Primer Forward** deve essere la stessa di quella del **Primer Revers** o, almeno, molto simile. I due primer utilizzati per la PCR sono definiti reverse e forward, a seconda che siano complementari al filamento 5' $\rightarrow$ 3' o a quello inverso 3' $\rightarrow$ 5'.
6. si devono evitare i tratti che potrebbero dare "self-annealing" (riassociazione).

Come si possono disegnano le coppie di primer?

La probabilità associata indica, per una data lunghezza di un primer, la probabilità di riscontrare casualmente nel campione di DNA una sequenza identica:

**P.A. = 4$^n$**

Dove:

+ **4** è il numero dei diversi nucleotidi del DNA (A, G, C, T);
+ **n** è la lunghezza dell'oligonucleotide.

Ad esempio, per un oligonucleotide di 16 basi, la probabilità di trovare una identica sequenza nel campione di DNA è inferiore a 1 su 4 miliardi, un numero più grande del numero di basi che compone l'intero genoma umano.

Calcolare la **temperatura di “annealing”** di un oligonucleotide.

Per oligonucleotidi corti (meno di 20 bp) vale la regola empirica:

**T$_a$ = 2 (A+T) + 4 (G+C)**

{img/temperatura-annealing}

La PCR è applicabile in diverse occasioni:

+ in **medicina forense e antropologia** per l'identificazione personale di tracce biologiche, l'identificazione personale di cadaveri non altrimenti riconoscibili, ecc...;
+ **analisi degli alimenti** (identificazione organismi OGM, contaminazioni batteriche, ecc...);
+ **genetica medica** (screening malattie ereditarie, diagnosi prenatale, ecc...);
+ **biologia molecolare** (clonaggio e mutagenesi sito specifica, ecc...).

Uno degli svantaggi di questo metodo è che bisogna avere qualche informazione sulla sequenza del pezzo di DNA che si vuole amplificare per sintetizzare primer specifici appropriati su entrambe le estremità.

**Esempio**

Voglio amplificare la seguente sequenza

{img/sequenza}

Per prima cosa disegno i 2 oligonucleotidi complementari alle 2 regioni che si trovano ai lati della regione che voglio amplificare.
In questo caso il Primer Forward (5' $\rightarrow$ 3') è:
**5'ATG GAG ACT ACC AAT GGA ACG3'**

Dopodichè individuo la sequenza al 3' su cui disegno il Primer Reverse, in questo caso: **5'AAC CGT GTG TCT ATG ATC TAA3'**

Il Primer Revers è però antisenso, ovvero si trova sul filamento complementare (direzione 3' $\rightarrow$ 5'). Risulata essere quindi:
**3'TTG GCA CAC AGA TAC TAG ATT5'**

Siccome però, per convenzione, tutti gli oligonucleotidi vengono scritti in direzione 5' $\rightarrow$ 3', bisogna disegnare la sequenza "reverse": **5'TTA GAT CAT AGA CAC ACG GTT3'**

## La Real-Time PCR

Questa consiste in una reazione PCR che può essere *seguita in tempo reale*, e la quantità di DNA sintetizzata può essere misurata ad ogni ciclo PCR.

La differenza tra questo tipo di PCR e quello analizzato precedentemente è che la PCR classica misura il DNA end-point, ovvero solo una volta che questo ha saturato la soluzione, mentre la Real-Time PRC misura il DNA alla fine di ogni ciclo di amplificazione.

Nella Real-Time PCR la crescite presenta 3 "momenti":

1. un primo momento di crescita esponenziale (limitata nel tempo);
2. una crescita lineare;
3. un plateau (non è correlato alla quantità iniziale di DNA presente).

Il processo di duplicazione non procede "all'infinito", esso è limitato dalla quantità dei primers, dall'attività della Taq pol e dal reannialing dei filamenti.

Queste fasi possono essere individuate mettendo in relazione su un grafico il numero di cicli effettuati (x) e il log[DNA] (y).

Per individuare il prodotto di PCR bisogna utilizzare i dati ottenuti durante la fase esponenziale (prodotto PCR proporzionale al template iniziale).

Questo è reso possibile mediante il rilevamento di una fluorescenza proporzionale al prodotto di PCR.

La fluorescenza, durante ogni ciclo di amplificazione può essere rilevata utilizzando uno strumento quantitativo che segue la cinetica della reazione di PCR.

Perchè Real-Time?
Perchè misura l'amplificazione in tempo reale durante la fase esponenziale della PCR, quando cioè l'efficienza di amplificazione è influenzata minimamente dalle variabili di reazione, permettendo di ottenere risultati molto più accurati rispetto alla PCR tradizionale "endpoint”.

I componenti necessari per la reazione di Real-Time PCR sono:

+ DNA target;
+ DNA polimerasi;
+ due oligonucleotidi;
+ dNTPs.
+ sonda (probe) fluorescente

### Chimiche fluorescenti per PCR Real-Time

La fluorescenza si genera durante la PCR per effetto di diverse possibili reazioni chimiche.

Le chimiche principali sono basate:

+ sul legame di **coloranti fluorescenti** che si intercalano in modo aspecifico nella doppia elica di DNA (*SYBR Green*);
+ sull'**ibridazione di sonde** specifiche per il frammento di interesse **marcate con molecole fluorescenti** (*Dual-labeled* come le *sonde TaqMan*, Molecular beacons, Scorpion, e le sonde FRET = Fluorescence Resonance Energy Transfer).

#### SYBR Green

Questo metodo uhtilizza una molecola fluorescente non specifica che si lega al solco minore del DNA.

Per questa colorazione si possono utilizzare primers in uso in qualitativa. Non è costosa e non-specifica.

La molecola fluorescente si lega random a tutte le doppie eliche,
includendo i dimeri di primers; per questo motivo è necessario ottimizzare la metodica per evitare la formazione di prodotti aspecifici.


All'inizio del processo di amplificazione, la miscela di reazione contiene DNA denaturato, primers e la molecola fluorescente.

{img/SBRY1}

Dopo l'anneling dei primer si legano poche molecole fluorescenti alla doppia elica.
Durante l'elongazione si verica un aumento di fluorescenza che corrisponde all'aumento del numero di copie dell'**amplicone** (un amplicone è un pezzo di DNA o RNA che è la sorgente e/o il prodotto di eventi di amplificazione o di replicazione).

#### Sonde TaqMan

Le sonde di tipo TaqMan sono formate da un oligonucleotide che, come i primers della PCR, viene disegnato per essere complementare alla sequenza bersaglio da amplificare. 
La sonda è disegnata in modo da ibridarsi all'interno del frammento
amplificato nella reazione di PCR. 

Presenta all'estremità 5' un **fluoroforo** ad alta energia che emette fluorescenza detto **"Reporter" (R)**, ed all'estremità 3' una molecola a bassa energia che spegne la fluorescenza del reporter detto **"Quencher" (Q)**.

Se R e Q si trovano vicini, Q spegne l'effetto di R perchè i fotoni di R vengono assorbiti da Q.
L'aumento di fluorescenza di R è direttamente proporzionale al numero di ampliconi generati.

#### Sonde FRET (Fluorescence Resonance Energy Transfer)

Questo genere di sonde sono simili alle sonde TaqMan perché si legano al DNA bersaglio e vengono idrolizzate.
Ci sono però due sonde, ognuna marcata con un solo fluorocromo (accettore e donatore).

Quando le sonde non sono legate alle sequenze target il segnale fluorescente proveniente dall'accettore non è rilevato.

Durante lo step di annealing PCR, entrambe le sonde FRET ibridizzano alle sequenze target: ciò avvicina il fluoroforo donatore all'accettore
permettendo il trasferimento di energia tra i due fluorofori e la produzione di un segnale fluorescente da parte dell'accettore che viene
rilevato.

#### Molecular Beacons

I "molecular beacons" contengono un fluoroforo e un quencher non fluorescente alle estremità opposte di un oligonucleotide. 
Le estremità oppeste di questo oligonucleotide sono disegnate in modo da essere complementari tra loro e formare una **struttura stem-loop**

Nella struttura stem-loop il fluoroforo e il quencher si trovano vicini, e la loro vicinanza impedisce l'emissione di fluorescenza.

Il loop è complementare ad una sequenza all'interno del prodotto amplificato.

Durante lo step di annealing PCR, la sonda ibridizza alla sua sequenza target; ciò separa il colorante fluorescente dal reporter, producendo un segnale fluorescente.

La quantità di fluorescenza prodotta ad ogni ciclo, o dopo la PCR, dipende dalla quantità di prodotto specifico in quel dato momento.

A differenza delle sonde TaqMan, le molecular beacons non vengono distrutte durante la reazione di amplificaizone per cui possono reibridizzarsi durante il successivo ciclo.

{img/probes}

Se raccogliamo in un grafico i risultati ottenuti tramite la nostra R-T PCR vedremo che, per ogni campione, si ottiene una curva di amplificazione il cui **Threshold Cycle (C$_T$)** è inversamente proporzionale alla quantità di template iniziale.

{img/diagramma-RT-PCR}

Dopo ogni rilevamento, i segnli di fluorescenza, sono processati da un software e la cinetica di formazione dell'amplificato è visualizzata graficamente come incremento dei segnali di fluorescenza in ordinata ($\Delta$Rn) per cicli di reazone in ascissa.

Il **ciclo threshol (C$_T$)** è il ciclo della reazione di amplificaizone nelquali il segnale di fluorescenza supera il valore di threshold.

Il **threshold** rappresenta quela valore di fluorescenza pari a 10 volte la ds della fluorescenza registrata nei primi cicli di amplificazione (background).

La quantificazione della fluorescenza può essere:

+ **quantificazione assoluta**, tramite l'uso di DNA a concentrazione nota (utilizzo di una *standard curve*);
+ **quantificaizone relativa**. Questa necessita di controlli endogeni tramite *geni housekeeping* (o reference interni). Non viene utilizzata una standar curve, ma la quantificazione viene effettuata paragonando i C$_T$.
I geni housekeeping sono comunemente:
	+ ubiquitari;
	+ espressi in maniera costitutiva;
	+ non risentono dei trattamenti sperimentali;
	+ mantengono la loro espressione costante nei diversi tipi cellulari.


Nella **quantificazione assoluta** si ha la necessita di utilizzare una standard curve. 
Per costruirla è necessario produrre almeno 5 diluizione dello stesso standar. I campioni da determinare vengono affiancati agli standar ed ai controlli negativi fatto con H$_2$O.

È necessario produrre 3 repliche sia per ogni campione sia per gli standard per aumentare l'affidabilità del risultato.

Per ogni esperimento in quantificazione relativa è necessario:

+ un **target**, ovvero la sequenza di DNA da analizzare;
+ un **calibratore**, ovvero il campione da usare come riferimento per l'analisi comparativa;
+ un **controllo endogeno**, ovvero un gene espresso in maniera costitutiva in tutti i campioni analizzati necessario per normalizzare i dati rispetto alla quantità di DNA caricato e a variazioni di efficienza della reazione.

Per analizzare i dati ottenuti con la quantitativa relativa è necessario:

1. normalizzare il target tramite un controllo endogeno (r) espresso costitutivamente ($\Delta$C$_T$);
2. comparare ciascun $\Delta$C$_T$ così ottenuto con il $\Delta$C$_T$ di un calibratore (cb, $\Delta$$\Delta$C$_T$)
3. inserire i dati nella seguente formula:

{img/formula1}

Il valore così ottenuto permette di determinare la concentrazione relativa del target.

Il primo step consiste nella normalizzazione tramite un controllo endogeno (HK)

{img/formula2}

Il secondo consiste nella normalizzazione tramite il calibratore

{img/formula3}

Infine si applica la formula

{img/formula4}

**Esempio**

{img/esempio}





























