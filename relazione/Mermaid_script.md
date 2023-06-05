graph TD \
A[ricerca delle fonti e flusso operativo] \
A --> B(Google Trends) \
A --> C(ChatGPT) \
A --> D(altri siti internet) \
E[prima stesura con ChatGPT] \
B --> E \
C --> E \
D --> E \
E --> F[revisione dei contenuti e accorgimenti tecnici] \
F --> G(nuove stesure con ChatGPT prendendo come esempi i competitor sul mercato) \
F --> H(stesura testo in rima) \
F --> I(Introduzione di un orso polare come protagonista della storia) \
J{nuove revisioni} \
G --> J \
J --> |prodotto non soddisfacente| J \
H --> h(per favorire una lettura più scorrevole) \
I --> i(introdotto per favorire empatizazzione verso il tema trattato) \
J --> |prodottto soddisfacente|K{elementi grafici generati da Gencraft} \
K --> |prodottto soddisfacente|k(utilizzo di Canva) \
K --> |prodotto non soddisfacente|K \
k --> l(implementazione elementi grafici) \
k --> m(impaginazione e modifica di font e grandezza dei caratteri) \
n(stesura su Visual Studio Code in linguaggio markdown) \
l --> n \
m --> n \
n --> o[trasformazione dei formati tramite pandoc] \
L(Trasformazione dei formati) \
L --> N(epub) \
L --> O(html) \
P(per favorire distribuzione digitale) \
N-->P \
O-->P \
Q[Definizione dello stile grafico] --> R(regole di impaginazione standard) \
Q --> S(presenza elementi grafici avanzati) \
S--> T(mantenendo rispetto di accessibilità)
