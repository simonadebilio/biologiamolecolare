# Reazione a catena della polimerasi (PCR)

La tecnica della PCR fu ideata nel 1983 da Kar B. Mullis.
Questa tenica permette di selezionare e amplificare, da una preparazione eterogenea di DNA, un particolare tratto che ci interessa, producendone un grandissimo numero di copie (può amplificare un tratto di DNA per più di un milione di volte).

Il processo di PCR prevede un certo numero di cicli (30-35) ed ogbu ciclo cinsiste di 3 passaggi:

1. **denaturazione** del DNA, avviene alla temperatura di 95°. Il DNA stampo viene denaturato, i due filamenti si separano;
2. **appaiamento**, avviene alla temperatura di 55° circa. In questo passaggio i primer si appaiano con il DNA stampo.
3. **sintesi**, avviene alla temperatura di 72°.

La PCR consiste sostanzialmente in una replicazione in viste di un frammento di DNA ottenuta mediante una DNA polimerasi e 2 oligonucleotidi lunghi 20-30 nt che fungono da inneschi (**primer**) per la replicazione e che sono responsabili della specificità dell'amplificazione.

Gli elementi necessari per la PCR sono:

+ **2 oligonucleotidi** complementari alle 2 regioni che si torvano sui filamenti opposti del DNA stampo, ai lati della regione che si vuole amplificare;
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

T$_a$ = 2 (A+T) + 4 (G+C)

{img/temperatura-annealing}




























