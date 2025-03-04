# Primo principio di Newton
Principio di inerzia: un corpo su cui non è applicata alcuna forza si muove a velocità costante

# Secondo principio di Newton
### Esperimento
Luogo: lago ghiacciato, attrito trascurabile
Materiali: cubo con una determinata massa, molla, cordella metrica, cronometro
Svolgimento:
Dal secondo $0$ si spinge con forza costante (misurabile attraverso la compressione della molla) il cubo fino al secondo $5$ e si effettuano misurazioni dello spazio percorso
Misurazioni:

| $t$  | $x$  |
| ---- | ---- |
| $-1$ | $0$  |
| $0$  | $0$  |
| $1$  | $1$  |
| $2$  | $4$  |
| $3$  | $9$  |
| $4$  | $16$ |
| $5$  | $25$ |
| $6$  | $35$ |
| $7$  | $45$ |
| $8$  | $55$ |
Conclusione:
Si nota che durante la spinta si verifica la formula $x=ct^{2}$, con $c=\pu{ 1m/s2 }$, mentre finita la spinta la velocità rimane costante, come prima della spinta

### Velocità, spazio, accelerazione
La velocità media si calcola come segue
$$\begin{flalign} v_{m}=\frac{\Delta x}{\Delta t}&&\end{flalign}$$
Mentre la velocità istantanea si calcola con il limite
$$\begin{flalign}v=\lim_{ \Delta t \to 0 } \frac{\Delta x}{\Delta t}=\frac{dx}{dt} &&\end{flalign}$$
Consegue che
$$\begin{flalign}x=\int v\,dt=\int \frac{dx}{dt}\,dt=\int dx &&\end{flalign}$$
$$\begin{flalign}v=\mathrm{D}[c\cdot t^{2}]=2c\cdot t &&\end{flalign}$$
Quindi l'accelerazione è data da
$$\begin{flalign}a=\frac{dv}{dt}=\mathrm{D}[2c\cdot t]=2c &&\end{flalign}$$
Integrando si ottiene
$$\begin{flalign}v=at+v_{0} &&\end{flalign}$$
Integrando ancora
$$\begin{flalign}x=\frac{a}{2}t^{2}+v_{0}t+x_{0} &&\end{flalign}$$
### Accelerazione in relazione allo spazio
$a\cdot v\cdot dt=a\cdot dx=v\cdot dv$
Integrando
$$\begin{flalign}\int_{x_{0}}^{x_{1}} a\,dx=\int_{v_{0}}^{v_{1}} v\,dv &&\end{flalign}$$
si ottiene
$$\begin{flalign}a\cdot(x_{1}-x_{0})=\frac{v_{1}^{2}-v_{0}^{2}}{2} &&\end{flalign}$$

### Forza e massa
La forza applicata è equivalente al prodotto della massa per l'accelerazione
$$\begin{flalign}F=m\cdot a &&\end{flalign}$$
$\pu{ 1N }$ è la forza necessaria per accelerare $\pu{ 1kg }$ di $\pu{ 1m/s2 }$

# Terzo principio di Newton
Azione e reazione: ad una forza corrisponde una forza di reazione uguale e contraria applicata ad un altro corpo

# Forza di gravità
La forza di gravità è un'attrazione radiale tra due corpi aventi massa

Legge di gravitazione universale: $$\begin{flalign}F=G\cdot \frac{m_{1}\cdot m_{2}}{d^{2}} &&\end{flalign}$$
$m_{1},m_{2}$: masse dei corpi
$d$: distanza
$G$: costante di gravitazione universale

Il campo gravitazionale sulla superficie terrestre è $g=G\frac{m_{T}}{r_{T}^{2}}=\pu{ 9.81 m/s2 }$