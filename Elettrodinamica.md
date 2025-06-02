# Serie e parallelo
Due componenti si dicono in serie se vengono attraversati dalla stessa corrente
Due componenti si dicono in parallelo se hanno ai loro capi lo stesso potenziale

# Cortocircuito e circuito aperto
Un cortocircuito corrisponde ad un tratto con resistenza nulla e corrente potenzialmente infinita
Un circuito aperto corrisponde ad un tratto con resistenza infinita e corrente nulla

# Resistenze
### Serie
$$\begin{flalign}R_{\mathrm{eq}}=\sum_{i=1}^{n}R_{i} &&\end{flalign}$$
### Parallelo
$$\begin{flalign}R_{\mathrm{eq}}=\frac{1}{\sum_{i=1}^{n} \frac{1}{R_{i}}} &&\end{flalign}$$
## Caduta di potenziale
Le resistenze attraversate da una corrente causano una caduta di potenziale trasformando parte dell'energia in calore tramite l'effetto Joule
$\Delta V=R\cdot I$

# Condensatori
Il condensatore quando scarico si comporta come un cortocircuito, mentre quando è carico come un circuito aperto
### Serie
$$\begin{flalign}C_{\mathrm{eq}}=\frac{1}{\sum_{i=1}^{n} \frac{1}{C_{i}}} &&\end{flalign}$$
### Parallelo
$$\begin{flalign}C_{\mathrm{eq}}=\sum_{i=1}^{n}C_{i} &&\end{flalign}$$
<div class="page-break" style="page-break-before: always;"></div>

### Carica e scarica
L'unità di tempo è
$\tau=R_{\mathrm{eq}}\cdot C$
dove $R_{\mathrm{eq}}$ è la resistenza equivalente vista dal condensatore cortocircuitando i generatori
La carica del condensatore in carica al tempo $t$ è data da
$$\begin{flalign}Q(t)=C\cdot \Delta V(t)=C\cdot V_{S}\cdot(1-e^{-t/\tau}) &&\end{flalign}$$
quindi
$$\begin{flalign}\Delta V(t)=V_{S}\cdot(1-e^{-t/\tau}) &&\end{flalign}$$
Inoltre
$$\begin{flalign}I(t)=\frac{V_{S}}{R}e^{-t/\tau} &&\end{flalign}$$
$$\begin{flalign}dE=\Delta V\,dQ=\frac{Q}{C}\,dQ &&\end{flalign}$$
In carica $\lim_{ t \to +\infty }\Delta V(t)=V_{S}$, in scarica $\lim_{ t \to +\infty }\Delta V(t)=0$

# Legge delle maglie
Una maglia è un percorso chiuso semplice
La differenza di potenziale creata dai generatori (supply) viene completamente "utilizzata" dal carico (load) (ovvero principalmente resistenze ma anche condensatori, induttori, ...)
$$\begin{flalign}\sum_{i=1}^{m}V_{Si}=\sum_{j=1}^{n}V_{Lj} &&\end{flalign}$$

# Legge dei nodi
La somma delle correnti entranti (in) in un nodo è uguale alla somma delle correnti uscenti (out)
$$\begin{flalign}\sum_{i=1}^{m}I_{Ii}=\sum_{j=1}^{n}I_{Oj} &&\end{flalign}$$

# Potenza
La potenza dissipata da un componente (anche equivalente) è
$P=V\cdot I$
Per le resistenze anche
$$\begin{flalign}P=R\cdot I^{2}=\frac{V^{2}}{R} &&\end{flalign}$$
