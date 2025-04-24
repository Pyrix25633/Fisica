# Lavoro
Il lavoro è la somma infinitesima delle forze in uno spostamento da $\vec{r_{1}}$ a $\vec{r_{2}}$ ovvero
$$\begin{flalign} W=\int_{\vec{r_{1}}}^{\vec{r_{2}}} \vec{F}\,d\vec{r} &&\end{flalign}$$
Per il secondo principio di Newton
$$\begin{flalign}\vec{F}\cdot d\vec{r}=m\cdot \vec{a}\cdot d\vec{r}=m\cdot \frac{d\vec{v}}{dt}\cdot d\vec{r}=m\cdot d\vec{v}\cdot \frac{d\vec{r}}{dt}=m\cdot d\vec{v}\cdot \vec{v} &&\end{flalign}$$
Pertanto
$$\begin{flalign}W=\int_{v_{1}}^{v_{2}} \frac{m\cdot \vec{v}\cdot d(v)}{2}=\frac{m}{2}(v_{2}^{2}-v_{1}^{2})=E_{k2}-E_{k1}=E_{p1}-E_{p2} &&\end{flalign}$$
E corrisponde alla differenza delle energie cinetiche e l'opposto della differenza delle energie potenziali nei due punti

### Lavoro di una forza costante e forza conservativa
$$\begin{flalign}W=-(\vec{F}\cdot \vec{r_{2}}-\vec{F}\cdot \vec{r_{1}})=\vec{F}(\vec{r_{1}}-\vec{r_{2}}) &&\end{flalign}$$
Dove la forza può essere la forza peso, elastica, di attrito, ...
Si può notare che il lavoro non dipende in alcun modo dal percorso, ciò significa che la forza è conservativa
Di conseguenza lungo un percorso chiuso il lavoro è nullo
$$\begin{flalign}\oint \vec{F}\,d\vec{r}=0 &&\end{flalign}$$

# Energia cinetica
La differenza di energia cinetica corrisponde al lavoro, per quanto trovato sopra
$$\begin{flalign}E_{k}=\frac{mv^{2}}{2} &&\end{flalign}$$
# Energia potenziale
Sempre per quanto visto sopra $W=-\Delta E_{p}$
Per una forza costante vale sempre $E_{p}=\vec{F}\cdot \vec{r}$, come nel caso della forza peso $E_{p}=m\cdot \vec{g}\cdot \vec{r}$
Per la forza elastica invece bisogna svolgere l'integrale e $E_{p}=\frac{k}{2}r^{2}$

# Energia meccanica
Se agiscono solo forze conservative vale $W=\Delta E_{k}=-\Delta E_{p}$ e l'energia meccanica $E_{m}=E_{k}+E_{p}$ di un punto materiale si conserva ed è costante
<div class="page-break" style="page-break-before: always;"></div>

# Quantità di moto
La quantità di moto è definita come il prodotto della velocità per la massa
$\vec{p}=m\cdot \vec{v}$
Pertanto la forza è la variazione della quantità di moto nel tempo
$$\begin{flalign}\vec{F}=m\cdot \vec{a}=m\cdot \frac{d\vec{v}}{dt}=\frac{d\vec{p}}{dt} &&\end{flalign}$$
La quantità di moto totale è la somma delle quantità di moto $\sum_{i}\vec{p_{i}}$
La somma di tutte le forze è uguale alla somma delle derivate delle quantità di moto
$$\begin{flalign}\sum_{i}\vec{F_{i}}=\sum_{i} \frac{d\vec{p_{i}}}{dt}=\frac{d}{dt}\sum_{i}\vec{p_{i}} &&\end{flalign}$$

# Impulso
L'impulso cambia la quantità di moto nel tempo
$$\begin{flalign}J=\int_{t_{0}}^{t_{1}} \vec{F}\,dt=\int_{t_{0}}^{t_{1}} m\,d\vec{v} = \vec{p_{1}}-\vec{p_{0}} &&\end{flalign}$$

# Urti elastici
Nella teoria degli urti la somma delle forze esterne è nulla e quindi irrilevante, inoltre ogni forza interna ha la sua forza di reazione e quindi è nulla
$$\begin{flalign} \sum_{k}\vec{F_{ki}} + \sum_{j}\vec{F_{je}}=0+0=\frac{d}{dt}\sum_{i}\vec{p_{i}}=0 &&\end{flalign}$$
Perciò la derivata della quantità di moto è nulla e la quantità di moto è costante, si preserva nel sistema
Si può costruire un sistema contenente le equazioni della preservazione della quantità di moto e dell'energia cinetica, in una dimensione
$$\begin{flalign}\begin{cases}
p_{0A}+p_{0B}=m_{A}\cdot v_{0A}+m_{B}\cdot v_{0A}=m_{A}\cdot v_{1A}+m_{B}\cdot v_{1B}=p_{1A}+p_{1B} \\
E_{k0A}+E_{k0B}=\frac{1}{2}m_{A}v_{0A}^{2}+\frac{1}{2}m_{B}v_{0B}^{2}=\frac{1}{2}m_{A}v_{1A}^{2}+\frac{1}{2}m_{B}v_{1B}^{2}=E_{k1A}+E_{k1B}
\end{cases}&&\end{flalign}$$

### Urti elastici tra oggetti con la stessa massa
Nelle equazioni precedenti si può dividere per la massa in quanto $m_{A}=m_{B}$ ottenendo
$$\begin{flalign}\begin{cases}
v_{0A}-v_{1A}=v_{0B}-v_{1B} \\
v_{0A}+v_{1A}=v_{0B}+v_{1B} \\
\end{cases} &&\end{flalign}$$
Quindi $v_{0A}=v_{1B}$ e $v_{1A}=v_{0B}$

# Potenza
La potenza è il lavoro sull'unità di tempo ovvero
$$\begin{flalign}P=\frac{dW}{dt}=\vec{F}\cdot \frac{d\vec{r}}{dt}=\vec{F}\cdot \vec{v} &&\end{flalign}$$
<div class="page-break" style="page-break-before: always;"></div>

# Momento meccanico
Il momento meccanico è definito come il prodotto vettoriale tra la forza e la posizione di applicazione
$\vec{M}=\vec{r}\times \vec{F}$
In modulo $M=r\cdot F\cdot \sin(\theta)$
Per i corpi in rotazione, con punto di riferimento nel centro di rotazione vale anche
$\vec{M}=I\cdot\vec{\alpha}$
dove $I=c\cdot m\cdot r^{2}$ è il momento di inerzia e varia a seconda della forma dell'oggetto:
- per un disco di massa uniforme $c=\frac{1}{2}$
- per un anello di massa concentrata verso l'esterno $c=1$

Inoltre per il teorema di Huggens-Steiner $I=I_{B}+d^{2}\cdot m$, con $I_{B}$ momento di inerzia nel baricentro e $d$ la distanza dal baricentro

# Momento angolare
Il momento angolare è il prodotto vettoriale la tra quantità di moto e la posizione di applicazione
$\vec{L}=\vec{r}\times \vec{p}$
In modo simile al lavoro vale
$$\begin{flalign}\sum_{i}\vec{M_{i}}=\frac{d}{dt}\sum_{i}\vec{L_{i}} &&\end{flalign}$$
Il tempo di svolgimento è infinitesimo, quindi la somma dei momenti meccanici si può approssimare a $0$, pertanto la somma dei momenti angolari è costante 