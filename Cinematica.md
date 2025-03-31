# Primo principio di Newton
Principio di inerzia: un corpo su cui non è applicata alcuna forza si muove a velocità costante

# Secondo principio di Newton
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
<div class="page-break" style="page-break-before: always;"></div>

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

# Vettori
$\vec{r}=x\cdot \vec{i}+y\cdot \vec{j}$
$$\begin{flalign}\vec{v}=\lim_{ \Delta t \to 0 } \frac{\vec{\Delta r}}{\Delta t}=\lim_{ \Delta t \to 0 } \frac{\Delta x}{\Delta t}\vec{i}+\lim_{ \Delta t \to 0 } \frac{\Delta y}{\Delta t}\vec{j}=\frac{dx}{dt}\vec{i}+\frac{dy}{dt}\vec{j} &&\end{flalign}$$
$$\begin{flalign}\vec{a}=\frac{d^{2}x}{dt^{2}}\vec{i}+\frac{d^{2}y}{dt^{2}}\vec{j} &&\end{flalign}$$

$$\begin{flalign}\vec{F}=G\cdot \frac{m_{1}\cdot m_{2}}{r^{2}}\hat{r} &&\end{flalign}$$

# Forza elastica
Le caratteristiche di una molla sono:
- lunghezza caratteristica/a riposo $l_{c}$
- costante elastica $k$
La forza esercitata dalla molla si ottiene con
$\vec{F_{e}}=-k \cdot\vec{\Delta x}$
$F_{e}=m\cdot a$
$-k\cdot\Delta x=m\cdot a$
Dove $\Delta x=|l_{c}-x|$, centrando il sistema in $l_{c}$ si ottiene $\Delta x=|x|$
<div class="page-break" style="page-break-before: always;"></div>

# Attrito radente
L'attrito è una forza che si oppone al movimento di un oggetto appoggiato su una superficie. Se l'attrito statico è maggiore o uguale alla forza applicata l'oggetto rimane fermo, altrimenti il caso diventa dinamico. Se l'attrito dinamico diventa maggiore della forza applicata l'oggetto si ferma.
L'attrito è direttamente proporzionale alla reazione normale del piano, moltiplicata per un coefficiente. Il coefficiente di attrito statico è sempre maggiore di quello dinamico.
$\vec{F_{AS}}=\vec{N}\cdot \mu_{S}$
$\vec{F_{AD}}=\vec{N}\cdot \mu_{D}$

# Moto circolare uniforme
Per semplicità si utilizzano le coordinate polari al posto di quelle cartesiane
Mentre i versori direzionali $\vec{i},\vec{j}$ degli assi $x,y$ sono fissi, $\vec{u_{r}},\vec{u_{\theta}}$ cambiano direzione
$\vec{R}=r\vec{u_{r}}=r\cos(\theta)\vec{i}+r\sin(\theta)\vec{j}$
La frequenza $f$ rappresenta il numero di rotazioni nell'unità di tempo, il periodo $T$ rappresenta il tempo impiegato per eseguire una rotazione
$f=\frac{1}{T}$
La velocità angolare corrisponde alla variazione dell'angolo nel tempo
$$\begin{flalign} \frac{d\theta}{dt}=\omega=2\pi\cdot f &&\end{flalign}$$
La variazione della direzione parallela nel tempo corrisponde alla variazione dell'angolo moltiplicata per la direzione normale
$$\begin{flalign} \frac{d\vec{u_{r}}}{dt}=\frac{d\theta}{dt}\vec{u_{\theta}} &&\end{flalign}$$
La velocità tangenziale dipende da quella angolare e dal raggio e corrisponde alla variazione dell'angolo nel tempo
La velocità tangenziale è la variazione della posizione nel tempo
$$\begin{flalign}\vec{v_{t}}=\frac{d(r\vec{u_{r}})}{dt}=\frac{dr}{dt}\vec{u_{r}}+\frac{d\vec{u_{r}}}{dt}r=\frac{dr}{dt}\vec{u_{r}}+\frac{d\theta}{dt}\vec{u_{r}}r=\frac{dr}{dt}\vec{u_{r}}+\omega \cdot r\cdot \vec{u_{r}}=\omega\cdot r\cdot \vec{u_{r}} &&\end{flalign}$$
poiché il raggio è costante, in modulo: $v_{t}=r\cdot\omega$
Derivando si ottiene
$$\begin{flalign}\vec{a_{c}}=\frac{d\vec{u}}{dt}=\frac{d^{2}r}{dt^{2}}\vec{u_{r}}+\frac{dr}{dt}\vec{u_{\theta}}+\frac{dr}{dt}\cdot \frac{d\theta}{dt}\vec{u_{\theta}}+r \frac{d^{2}\theta}{dt^{2}}\vec{u_{\theta}}+r \frac{d\theta}{dt}\cdot \frac{d\vec{u_{\theta}}}{dt} &&\end{flalign}$$
I primi tre termini si annullano poiché il raggio è costante, il quarto anche perché l'angolo varia in modo costante, quindi rimane
$$\begin{flalign}\vec{a_{c}}=r \frac{d\theta}{dt}\cdot \frac{d\vec{u_{\theta}}}{dt}=-r \left( \frac{d\theta}{dt} \right)^{2}\vec{u_{r}}=-r\cdot\omega\cdot \vec{u_{r}} &&\end{flalign}$$
L'accelerazione centripeta in modulo pertanto si calcola come: $a_{c}=r\cdot\omega^{2}$

<div class="page-break" style="page-break-before: always;"></div>

# Moto circolare uniformemente accelerato
La velocità angolare $\omega$ cambia secondo un'accelerazione $\alpha$, pertanto c'è un'accelerazione tangenziale $a_{t}$ costante, mentre quella centripeta $a_{c}$ varia poiché dipende dalla velocità tangenziale
Il comportamento è analogo a quello del moto rettilineo uniformemente accelerato:
$\omega=\omega_{0}+\alpha t$
$\theta=\theta_{0}+\omega_{0}t+\frac{1}{2}\alpha t^{2}$
Come per quello uniforme vale $v_{t}=r\cdot\omega$
Inoltre $a_{t}=r\cdot\alpha$
E' importante tenere a mente che periodo e frequenza non sono più costanti, quindi non è possibile utilizzarli per calcolare la velocità angolare
