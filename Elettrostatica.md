# Forza elettrica
$$\begin{flalign}\vec{F}=K_{e}\cdot \frac{q_{1}\cdot q_{2}}{r^{2}}\cdot \hat{u_{r}}=\frac{1}{4\pi\varepsilon_{0}}\cdot \frac{q_{1}\cdot q_{2}}{r^{2}}\cdot \hat{u_{r}} &&\end{flalign}$$
Se $q_{1}$ e $q_{2}$ hanno lo stesso segno la forza ha segno positivo e i due corpi si respingono, altrimenti si attraggono
$K_{e}=\pu{ 9\cdot10^{9} Nm^{2}/C^{2}}$
La costante dielettrica $\varepsilon_{0}=\pu{ 8,854\cdot10^{-12} C^{2}/Nm^{2} }$ descrive la resistenza del materiale al campo elettrico, in questo caso il vuoto
L'attrazione gravitazionale tra due particelle è insignificante rispetto a quella elettrica, alcuni numeri:
$m_{e}=\pu{ 9,1093\cdot10^{-31} Kg }$, $m_{p}=\pu{ 1,6726\cdot10^{-27} Kg }$, $q_{p}=-q_{e}=\pu{ 1,6022 C }$

# Campo elettrico
$$\begin{flalign}\vec{E}=K_{e}\cdot \frac{q}{r^{2}}\cdot \hat{u_{r}}=\frac{1}{4\pi\varepsilon_{0}}\cdot \frac{q}{r^{2}}\cdot \hat{u_{r}} &&\end{flalign}$$
Esprime la potenzialità di forza elettrica in un punto, infatti $\vec{E}\cdot q_{2}=\vec{F}$

# Flusso elettrico
La superficie della sfera equivale a $S=4\pi r^{2}$
Il flusso elettrico è dato da
$$\begin{flalign}\Phi_{E}=E\cdot S=\frac{1}{4\pi\varepsilon_{0}}\cdot \frac{q}{r^{2}}\cdot4\pi r^{2}=\frac{q}{\varepsilon_{0}} &&\end{flalign}$$
E vale su tutte le superfici chiuse indipendentemente dalla posizione della carica

### Campo elettrico di un filo carico
Per un filo disposto sull'asse delle $y$ da $a$ a $-a$ di carica $Q$ rispetto ad un punto $P(x_{0},0)$
Il filo ha una densità di carica
$$\begin{flalign}\lambda=\frac{Q}{2a} &&\end{flalign}$$
per cui $dq=\lambda \cdot dy$
Ogni punto del filo $R(0,y_{0})$ crea un campo elettrico $d\vec{E}$ verso $P$ la cui componente verticale è compensata da $R'(0,-y_{0})$, quella orizzontale è
$$\begin{flalign}dE_{x}=\frac{1}{4\pi\varepsilon_{0}}\cdot \frac{dq}{\left(\sqrt{y^{2}+x_{0}^{2}}\right)^{2}}\cdot \cos(\theta)=\frac{1}{4\pi\varepsilon_{0}} \cdot \frac{\lambda\cdot dy}{y^{2}+x_{0}^{2}}\cdot \cos(\theta) &&\end{flalign}$$
dove $\theta$ è l'angolo formato con l'orizzontale dal segmento $\overrightarrow{RP}$ lungo $\rho$
$$\begin{flalign} \frac{x_{0}}{\rho}=\cos(\theta)\implies \rho=\frac{x_{0}}{\cos(\theta)}=\sqrt{y^{2}+x_{0}^{2}} &&\end{flalign}$$
<div class="page-break" style="page-break-before: always;"></div>

$$\begin{flalign}y=x_{0}\cdot \tan(\theta)\implies\theta=\arctan\left( \frac{y}{x_{0}} \right) &&\end{flalign}$$
$$\begin{flalign}dy=\frac{x_{0}}{\cos ^{2}(\theta)}d\theta &&\end{flalign}$$
Quindi il campo elettrico è l'integrale
$$\begin{flalign}E_{x}&=\int_{-a}^{a} dE_{x}=\int_{-a}^{a} \frac{1}{4\pi\varepsilon_{0}}\cdot \frac{\lambda\cdot dy}{y^{2}+x_{0}^{2}}\cdot \cos(\theta)\\
&=\int_{-\theta_{0}}^{\theta_{0}} \frac{1}{4\pi\varepsilon_{0}}\cdot \frac{\lambda\cdot x_{0}}{\cos ^{2}(\theta)}\cdot d\theta\cdot\left( \frac{\cos(\theta)}{x_{0}} \right)^{2}\cdot \cos(\theta)\\
&=\frac{\lambda}{4\pi\varepsilon_{0}x_{0}}\cdot[\sin(\theta)]_{-\theta_{0}}^{\theta_{0}}=E
&&\end{flalign}$$
Per un filo infinito:
$$\begin{flalign}E_{\infty}=\frac{\lambda}{2\pi\varepsilon_{0}x_{0}} &&\end{flalign}$$

Utilizzando il flusso per il campo elettrico di un filo carico infinito:
Prendendo un cilindro di altezza $h$ e raggio $x_{0}$, la carica elettrica del filo contenuto è $Q=\lambda\cdot h$
Il flusso si può ricavare sia moltiplicando il campo elettrico per la superficie con cui interagisce in modo ortogonale sia attraverso la definizione
$$\begin{flalign}\Phi_{E}=E\cdot2\pi x_{0}h=\frac{\lambda\cdot h}{\varepsilon_{0}} &&\end{flalign}$$
Quindi
$$\begin{flalign}E=\frac{\lambda}{2\pi \varepsilon_{0}x_{0}} &&\end{flalign}$$

### Campo elettrico di un disco carico
Si utilizzano le coordinate polari per semplicità
Se il raggio è $R$ la densità di carica è
$$\begin{flalign}\sigma=\frac{Q}{S}=\frac{Q}{\pi R^{2}} &&\end{flalign}$$
Si divide il disco in superfici infinitesimali  di area $dS=dr\cdot r\cdot d\theta$, come se fosse l'area di un rettangolo
Infatti
$$\begin{flalign}S&=\int_{0}^{R}\int_{0}^{2\pi}r\,d\theta\,dr=\int_{0}^{R}r\int_{0}^{2\pi}d\theta\,dr=\int_{0}^{R}r\cdot[\theta]_{0}^{2\pi}\,dr=\int_{0}^{R}2\pi r\,dr\\
&=2\pi\cdot\left[ \frac{r^{2}}{2} \right]_{0}^{R}=\pi R^{2}
&&\end{flalign}$$
Centrando il disco nell'origine, sul piano $x=0$, $\alpha$ è l'angolo formato rispetto all'asse $x$ da segmento che congiunge $R(0,r\cos(\theta),r\sin(\theta))$ a $P(x_{0},0,0)$
$$\begin{flalign}\cos(\alpha)=\frac{x_{0}}{\sqrt{r^{2}+x_{0}^{2}}} &&\end{flalign}$$
<div class="page-break" style="page-break-before: always;"></div>

$$\begin{flalign}dE_{x}=\frac{1}{4\pi\varepsilon_{0}}\cdot \frac{\sigma\cdot d\theta\cdot r\cdot dr}{\left(\sqrt{r^{2}+x_{0}^{2}}\right)^{2}}\cdot \cos(\alpha)=\frac{1}{4\pi\varepsilon_{0}}\cdot \frac{\sigma\cdot d\theta\cdot r\cdot dr}{(r^{2}+x_{0}^{2})^{3/2}}\cdot x_{0} &&\end{flalign}$$
$$\begin{flalign}E_{x}&=\int_{0}^{R}\int_{0}^{2\pi}dE_{x}=\frac{\sigma\cdot x_{0}}{4\pi\varepsilon_{0}}\int_{0}^{2\pi}d\theta \int_{0}^{R} \frac{r}{(r^{2}+x_{0}^{2})^{3/2}}\,dr=\frac{\sigma\cdot x_{0}}{4\pi\varepsilon_{0}}\cdot2\pi \int_{0}^{R} \frac{r}{(r^{2}+x_{0}^{2})^{3/2}}\,dr\\
&=\frac{\sigma\cdot x_{0}}{2\varepsilon_{0}}\cdot\left[ -\frac{1}{\sqrt{r^{2}+x_{0}^{2}}} \right]_{0}^{R}=\frac{\sigma\cdot x_{0}}{2\varepsilon_{0}}\cdot\left( \frac{1}{x_{0}}-\frac{1}{\sqrt{R^{2}+x_{0}^{2}}} \right)=E
&&\end{flalign}$$
Per una superficie infinita
$$\begin{flalign}E_{\infty}=\frac{\sigma\cdot x_{0}}{2\varepsilon_{0}}\cdot \frac{1}{x_{0}}=\frac{\sigma}{2\varepsilon_{0}} &&\end{flalign}$$

Utilizzando il flusso per il campo elettrico di una superficie infinita:
Prendendo un cilindro di altezza $2h$, che interseca ortogonalmente il piano $x=0$ ad altezza $h$, il cui asse passa per $P(x_{0},0,0)$ e $P'(-x_{0},0,0)$
$$\begin{flalign}\Phi_{E}=E\cdot2S=\frac{Q}{\varepsilon_{0}}=\frac{\sigma \cdot S}{\varepsilon_{0}} &&\end{flalign}$$
Quindi
$$\begin{flalign}E=\frac{\sigma\cdot S}{\varepsilon_{0}}\cdot \frac{1}{2S}=\frac{\sigma}{2\varepsilon_{0}} &&\end{flalign}$$

### Campo elettrico di una sfera carica
Per una sfera di raggio $R$ rispetto ad una particella a distanza $r$ dal centro della sfera
Se $r\geq R$
$$\begin{flalign}\Phi_{E}=E\cdot S=E\cdot4\pi r^{2}=\frac{Q}{\varepsilon_{0}} &&\end{flalign}$$
$$\begin{flalign}E=\frac{Q}{4\pi\varepsilon_{0}r^{2}} &&\end{flalign}$$
Altrimenti
$$\begin{flalign}\rho=\frac{Q}{V}=\frac{Q}{\frac{4}{3}\pi R^{3}} &&\end{flalign}$$
$$\begin{flalign}Q'=\rho\cdot \frac{4}{3}\pi r^{3}=\frac{Q\cdot r^{3}}{R^{3}} &&\end{flalign}$$
$$\begin{flalign}E'=\frac{Q'}{4\pi\varepsilon_{0}r^{2}}=\frac{Q\cdot r}{4\pi\varepsilon_{0}\cdot R^{3}} &&\end{flalign}$$
