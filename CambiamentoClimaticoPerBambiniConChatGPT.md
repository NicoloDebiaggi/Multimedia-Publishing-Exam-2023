
`` Università degli Studi di Milano ``
`` Corso di Editoria Digitale`` 
`` Anno Accademico 2022/2023``
`` Nicolò Debiaggi 908971`` 

# Titolo Progetto d'Esame
Il cambiamento climatico per bambini con ChatGPT

## Introduzione

Il progetto consiste nella generazione di un testo per bambini che ha come argomento un topic di tendenza, il tema del cambiamento climatico in questo caso, utilizzando ChatGPT.

L'obiettivo principale consiste nel testare i servizi di ChatGPT per provare  a definire un workflow di generazione semi automatica di testo. 
Le tecnologie usate sono Google Trends e altri siti di trend topics per individuare un argomento di tendenza, visualCode  per scrivere il modello in Markdown, Pandoc per convertire in formato epub e html.

## Obiettivi 

L'obiettivo del lavoro è testa la capacità di un'intelligenza artificiale, ChatGPT, nella generazione semiautomatica di un testo indirizzato a un pubblico di bambini ma che, allo stesso tempo, possa avere una qualità di testo pari almeno a quella presente sul rispettivo mercato.

## Processo di produzione

Descrivere le attività sviluppate all'interno del progetto per realizzare il prodotto.
> Nel farlo è utile riferirsi alle possibili attività elencate nella lezione 5, slide 4-7. 

Inanzitutto ho ricercato i punti chiave del cambiamento climatico su vari siti internet e ho chiesto anche a ChatGPT stessa di fornirmi diverse idee per quanto riguardasse questa analisi del tema.
Quindi ho cercato la presenza di possibili competitor e ne ho trovati diversi a partire da quelli che richiamano la figura di Greta Thunberg ad altri che utilizzano gli animali come principali protagonisti. Essendo un libro per bambini il target era già definito in partenza quindi il pubblico sarà stato dai 9 anni a salire.

Per quanto riguarda un'ipotetica distribuzione non serve fare affidamento su delle grandi case editrici in quanto amazon fornisce la possibilità di auto pubblicare il proprio libro mantenendo i costi a zero.

La presenza di altri libri su questo tema implica un impoverimento dell'originalità in quanto a cosa dire ma non per la forma in cui lo si può raccontare, che essa sia tramite una fiaba, una favola o un'intervista. Il modello di business richiama quello della distribuzione essendo gratuita la pubblicazione tramite Amazon starà al reparto visivo del libro a fare da marketing per sè stesso, ad esempio si potrebbe puntare su colori un po' più sgargianti per attirare l'attenzione e all'introduzione in copertina di un animale simbolo come ad esempio l'orso polare che appunto va a richiamare il tema dello scioglimento dei ghiacciai che è legato al cambiamento climatico.

Essendo generato da un'IA il problema dell'identificazione delle fonti verrà risolto molto facilmente essendo essa stessa la fonte. Per quanto riguarda diritti e aspetti legali la possibilità di lucrare da questo libro andrà verificati nei termini e condizioni d'uso di ChatGPT.

Una volta individuati i punti da discutere, verrà chiesto a ChatGPT di stendere una prima bozza e, successivamente, di portarla a un livello di scrittura simile a quello dei competitor. Questo verrà ripetuto per ogni punto. 

Essendo un libro per bambini si potrebbero introdurre immagini all'interno del libro per alleviare l'attenzione del lettore, ritornando all'orso polare, potrebbero esserci raffigurazioni grafiche di animali in determinati contesti.

Una volta soddisfatti con la stesura di ogni paragrafo si potranno unire insieme per un'ultima bozza per una revisione finale e, se necessario, ci sarà implementazione di nuovi contenuti.

Per quanto riguarda lo stile grafico e le regole di impaginazione verranno usate quelle standard senza la definizione di elementi grafici avanzati ma rispettando i requisiti di accessibilità. 

Per la creazione del formato di distribuzione si potrà convertire il documento in epub e html in modo da poterlo fornire anche digitalmente.

Una volta terminate le ultime revisioni, la definizione dei metadati descrittivi e la definizione di documentazione e del materiale di supporto si potrà passare alla promozione del libro.

Per quanto riguarda il marketing si potrebbe lanciare una campagna social che permetterebbe di raggiungere un pubblico maggiore e un target di età specifico (bambini e genitori) ma che riesce comunque a mantenere bassi i costi di pubblicità, magari spingendo sul fatto che ChatGPT sia una parte importante nella realizzazione di questo libro per cercare di rendere virale la notizia. Una volta effettuato il lancio non ci rimarrà che aspettare e raccogliere i dati, lato vendite e interazioni social, per confrontarli con la campagna marketing per poter fare una revisione degli obiettivi comunicativi e dei contenuti.

## Gestione documentale

Per descrivere il *flusso di gestione documentale* ho utilizzato il linguaggio Mermaid suddividendo il grafo in tre alberi principali: ricerca delle fonti e flusso operativo, trasformazione dei formati e definizione dello stile grafico.

graph TD
A[ricerca delle fonti]
A --> B(Google Trends)
A --> C(ChatGPT)
A --> D(altri siti internet)
E[prima stesura con ChatGPT]
B --> E
C --> E
D --> E
E --> F[revisione dei contenuti e accorgimenti tecnici]
F --> G(nuove stesure con ChatGPT prendendo come esempi i competitor sul mercato)
F --> H(stesura testo in rima)
F --> I(Introduzione di un orso polare come protagonista della storia)
J{nuove revisioni}
G --> J
J --> |prodotto non soddisfacente| G
H --> h(per favorire una lettura più scorrevole)
I --> i(introdotto per favorire empatizazzione verso il tema trattato)
J --> |prodottto soddisfacente|K[prodotto finale]
 L(Trasformazione dei formati)
L --> N(epub)
L --> O(html)
P(per favorire distribuzione digitale)
N-->P
O-->P
Q[Definizione dello stile grafico] --> R(regole di impaginazione standard)
Q --> S(assenza elementi grafici avanzati)
S--> T(mantenendo rispetto di accessibilità)

## Tecnologie adottate

Le tecnologie adottate sono Markdown e ePub (tramite conversione con pandoc del documento in formato markdown). L'utilizzo di Markdown ha abbattuto molto i tempi di gestione documentale essendo un linguaggio di formattazione di testo molto intuitivo e rapido da utilizzare. La tecnologia ePub ha invece supportato la diffusione digitale del testo e quindi ha permesso di raggiungere un pubblico più ampio portando un aumento di qualità nella versione digitale del documento.

Inoltre è presente una [repository github](https://github.com/NicoloDebiaggi/Esame-editoria-digitale) con tutti i documenti nei vari formati e gli script utilizzati all'interno della relazione.

## Conclusioni

Il risultato ottenuto è il libro per bambini "Sammy saves the snow" che parla di un orso polare che si ritrova ad affrontare e superare il tema dello scioglimento dei ghiacciai e introduce l'argomento delle fonti di energia rinnovabili. Per ottenere un risultato soddisfacente ci sono volute diverse revisioni ma ciò ha permesso di raggiungere gli obiettivi prefissati. La più grande limitazione è l'assenza di immagini in quanto ChatGPT è in grado di generare solo la parte testuale e non quella grafica.

## Bibliografia e sitografia

ChatGPT
Google Trends
un.org
nasa.gov
wikipedia.org
bbc.com
