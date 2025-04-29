# Forza elettrica
$$\begin{flalign}\vec{F}=K_{e}\cdot \frac{q_{1}\cdot q_{2}}{r^{2}}\cdot \hat{u_{r}}=\frac{1}{4\pi\varepsilon_{0}}\cdot \frac{q_{1}\cdot q_{2}}{r^{2}}\cdot \hat{u_{r}} &&\end{flalign}$$
Se $q_{1}$ e $q_{2}$ hanno lo stesso segno la forza ha segno positivo e i due corpi si respingono, altrimenti si attraggono
$K_{e}=\pu{ 9\cdot10^{9} Nm^{2}/C^{2}}$, $\varepsilon_{0}=\pu{ 8,854\cdot10^{-12} C^{2}/Nm^{2} }$
L'attrazione gravitazionale tra due particelle è insignificante rispetto a quella elettrica, alcuni numeri:
$m_{e}=\pu{ 9,1093\cdot10^{-31} Kg }$, $m_{p}=\pu{ 1,6726\cdot10^{-27} Kg }$, $q_{p}=-q_{e}=\pu{ 1,6022 C }$

# Campo elettrico
$$\begin{flalign}\vec{E}=K_{e}\cdot \frac{q}{r^{2}}\cdot \hat{u_{r}}=\frac{1}{4\pi\varepsilon_{0}}\cdot \frac{q}{r^{2}}\cdot \hat{u_{r}} &&\end{flalign}$$
Esprime la potenzialità di forza elettrica in un punto, infatti $\vec{E}\cdot q_{2}=\vec{F}$

### Campo elettrico di un filo carico
Per un filo disposto sull'asse delle $y$ da $a$ a $-a$ di carica $Q$ rispetto ad un punto $P(x_{0},0)$
Il filo ha una densità di carica
$$\begin{flalign}\lambda=\frac{Q}{2a} &&\end{flalign}$$
per cui $dq=\lambda \cdot dy$
Ogni punto del filo $R(0,y_{0})$ crea un campo elettrico $d\vec{E}$ verso $P$ la cui componente verticale è compensata da $R'(0,-y_{0})$, quella orizzontale è
$$\begin{flalign}dE_{x}=\frac{1}{4\pi\varepsilon_{0}}\cdot \frac{dq}{\left(\sqrt{y^{2}+x_{0}^{2}}\right)^{2}}\cdot \cos(\theta)=\frac{1}{4\pi\varepsilon_{0}} \cdot \frac{\lambda\cdot dy}{y^{2}+x_{0}^{2}}\cdot \cos(\theta) &&\end{flalign}$$
dove $\theta$ è l'angolo formato con l'orizzontale dal segmento $\overrightarrow{RP}$ lungo $\rho$
$$\begin{flalign} \frac{x_{0}}{\rho}=\cos(\theta)\implies \rho=\frac{x_{0}}{\cos(\theta)}=\sqrt{y^{2}+x_{0}^{2}} &&\end{flalign}$$
$$\begin{flalign}y=x_{0}\cdot \tan(\theta)\implies\theta=\arctan\left( \frac{y}{x_{0}} \right) &&\end{flalign}$$
$$\begin{flalign}dy=\frac{x_{0}}{\cos ^{2}(\theta)}d\theta &&\end{flalign}$$
Quindi il campo elettrico è l'integrale
$$\begin{flalign}E_{x}&=\int_{-a}^{a} dE_{x}=\int_{-a}^{a} \frac{1}{4\pi\varepsilon_{0}}\cdot \frac{\lambda\cdot dy}{y^{2}+x_{0}^{2}}\cdot \cos(\theta)\\
&=\int_{-\theta_{0}}^{\theta_{0}} \frac{1}{4\pi\varepsilon_{0}}\cdot \frac{\lambda\cdot x_{0}}{\cos ^{2}(\theta)}\cdot d\theta\cdot\left( \frac{\cos(\theta)}{x_{0}} \right)^{2}\cdot \cos(\theta)\\
&=\frac{\lambda}{4\pi\varepsilon_{0}x_{0}}\cdot[\sin(\theta)]_{-\theta_{0}}^{\theta_{0}}
&&\end{flalign}$$

# Flusso elettrico
La superficie della sfera equivale a $S=4\pi r^{2}$
Il flusso elettrico è dato da
$$\begin{flalign}\Phi_{E}=E\cdot S=\frac{1}{4\pi\varepsilon_{0}}\cdot \frac{q}{r^{2}}\cdot4\pi r^{2}=\frac{q}{\varepsilon_{0}} &&\end{flalign}$$
E vale su tutte le superfici chiuse indipendentemente dalla posizione della carica
