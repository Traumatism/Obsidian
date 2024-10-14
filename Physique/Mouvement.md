# 1. Mouvements

- $\langle\vec{u},\vec{v}\rangle=\vec{u}\cdot\vec{v}\triangleq\lVert\vec{u}\rVert\cdot\lVert\vec{v}\rVert\cdot\cos(\vec{u},\vec{v})$
- $\forall{i}(\lVert\overrightarrow{e_i}\rVert=1)$
- $\frac{\mathrm{d}y}{\mathrm{d}t}\triangleq\dot{y}$
- $\frac{\mathrm{d^2}y}{\mathrm{d}t^2}\triangleq\ddot{y}$
## 1.1. Coordonnées cartésiennes

## 1.2. Coordonnées cylindriques

- $\overrightarrow{OM}=r\overrightarrow{e_r}+z\overrightarrow{e_z}$
- $\vec{v}=\dot{r}\overrightarrow{e_{r}}+ r\dot{\theta}\overrightarrow{e_{\theta}}+\dot{z}\overrightarrow{e_z}$
- $\vec{a}=(\ddot{r}-r\dot{\theta}^{2})\overrightarrow{e_{r}}+(2\dot{r}\dot{\theta}+r\ddot{\theta})\overrightarrow{e_{\theta}}+\ddot{z}\overrightarrow{e_z}$
## 1.3. Coordonnées sphériques

- $\overrightarrow{OM}=r\overrightarrow{e_r}$
- $\vec{v}=\dot{r}\overrightarrow{e_{r}}+ r\dot{\theta}\overrightarrow{e_{\theta}}+rsin(\theta)\dot{\varphi}\overrightarrow{e_\varphi}$
- $\vec{a}=\dot{\vec{v}}$
## 1.4. Coordonnées polaires

- $\overrightarrow{OM}=r\overrightarrow{e_r}$
- $\vec{v}=\dot{r}\overrightarrow{e_{r}}+ r\dot{\theta}\overrightarrow{e_{\theta}}$
- $\vec{a}=(\ddot{r}-r\dot{\theta}^{2})\overrightarrow{e_{r}}+(2\dot{r}\dot{\theta}+r\ddot{\theta})\overrightarrow{e_{\theta}}$

## 1.5. Mouvements particuliers

# 2. Dynamique

## 2.1. Interactions et forces

Champ gravitationnel $$\vec{g}(A)\triangleq-G\frac{m}{r^2}\overrightarrow{e_r}$$
Force gravitationnelle: $$\overrightarrow{F}(A)\triangleq{m_A}\cdot\vec{g}(A)=-G\frac{m_{A}m}{r^2}\overrightarrow{e_r}$$

Champ électrique: $$\overrightarrow{E}(A)\triangleq\frac{q\overrightarrow{e_r}}{4\pi\varepsilon_0\cdot{r^2}}$$
Force électro-statique (_Loi de Coulomb_): $$\overrightarrow{F}(A)\triangleq{q_A}\cdot\overrightarrow{E}(A)=\frac{q_{A}q\overrightarrow{e_r}}{4\pi\varepsilon_0\cdot{r^2}}$$

Forces de frottement:
- Visqueux: $$\vec{f}\triangleq-\alpha\vec{v}$$
- Turbulents: $$\vec{f}\triangleq-{C_x}\frac{\rho{S}}{2}v\vec{v}$$

Force de rappel d'un ressort (_Loi de Hooke_): $$\overrightarrow{F}\triangleq-k(l-l_0)\overrightarrow{e_x}$$

Poussée d'Archimède: $$\overrightarrow{\Pi}\triangleq-\rho{V}\vec{g}$$
## 2.2. Masse et quantité de mouvement

Centre de masse $G$: $$\sum{m_i\overrightarrow{GP_i}}=\vec{0} \iff \overrightarrow{OG}\triangleq\frac{1}{m}\sum{m_i\overrightarrow{OP_i}}$$
Quantité de mouvement: $$\vec{p}\triangleq m\vec{v}$$

## 2.3. Principes fondamentaux de la dynamique

### 2.3.1. Lois de Newton

#### 2.3.1.a. Principe d'inertie _(Première loi de Newton)_

Système en mouvement rectiligne uniforme $\iff\sum{\overrightarrow{F}}=\vec{0}$
#### 2.3.1.b. Principe fondamental de la dynamique _(Seconde loi de Newton)_

$$\dot{p}=\sum{\overrightarrow{F}}$$
$$\implies\dot{m}\vec{v}+m\dot{\vec{v}}=\sum{\overrightarrow{F}}$$


Pour une masse constante: $$m\vec{a}=\sum{\overrightarrow{F}}$$

#### 2.3.1.c. Principe d'action/réaction _(Troisième loi de Newton)_

$$\overrightarrow{F_{A/B}}=-\overrightarrow{F_{B/A}}$$

### 2.3.2. Trajectoire balistique

Référentiel: Terrestre
Système: Objet de masse m
Bilan: $\overrightarrow{P}$

La seconde loi de Newton donne: $$m\vec{a}=\overrightarrow{P} \implies \vec{a}=\vec{g}=-g\overrightarrow{e_z}$$
$$\xRightarrow{\int} \vec{v}=(v_0\cos\alpha)\overrightarrow{e_x}+(-gt+v_0\sin\alpha)\overrightarrow{e_z}$$
$$\xRightarrow{\int} \overrightarrow{OM}=(v_0{t}\cos\alpha)\overrightarrow{e_x}+(-\frac{1}{2}gt^2+v_0{t}\sin\alpha)\overrightarrow{e_z}$$

### 2.3.3. Chute dans un fluide

### 2.3.4. Système masse-ressort

Référentiel: Terrestre
Système: Objet de masse m
Bilan: $\overrightarrow{P}$, $\overrightarrow{N}$, $\overrightarrow{F}$

La seconde loi de Newton donne: $$m\vec{a}=\overrightarrow{P}+\overrightarrow{N}+\overrightarrow{F}$$
Après avoir projeté sur $\overrightarrow{e_x}$: $$m\ddot{x}=-k(x-l_0)$$

On pose $X:=x-l_0$

On a alors: $$\ddot{X}+\omega_{0}^{2}X=0$$ avec $\omega_{0}:=\sqrt{\frac{k}{m}}$

**Méthode 1**

donc $$X\triangleq\alpha\cos\omega_0{t}+\beta\sin\omega_0{t}$$
Or $X(0)=\alpha$ d'où $\alpha = X_0$ et $\frac{dX}{dt}=\beta\omega_0$ d'où $\beta=\frac{v_0}{\omega_0}$

Ainsi: $$X = X_0\cos\omega_0{t}+\frac{v_0}{\omega_0}\sin\omega_{0{t}}$$
$\Box$

**Méthode 2**

donc: $$X\triangleq{X_m}\cos(\omega_0{t}+\varphi)$$
Or:$$X_0=X_m\cos\varphi$$ et $v_0=-X_m\omega_0\sin\varphi$

Donc: $$X_m=\sqrt{X_m^2}=\sqrt{X_m^2\cos(\varphi)^2+X_m^2\sin(\varphi)^2}=\sqrt{X_0^2+\Big(\frac{v_0}{\omega_0}\Big)^2}$$
Ainsi: $$X=\sqrt{X_0^2+\Big(\frac{v_0}{\omega_0}\Big)^2}\cos(\omega_0{t}+\varphi)$$
$\Box$
### 2.3.5. Pendule simple

### 2.3.6. Particule chargée dans un champ électrique uniforme

Force de Lorentz:

- Contribution électrique: $$\overrightarrow{F_{élec}}\triangleq{q}\overrightarrow{E}$$
- Contribution magnétique: $$\overrightarrow{F_{mag}}\triangleq{q}\vec{v}\land{\overrightarrow{B}}$$

# 3. Aspects énergétiques

## 3.1. Travail d'une force

Travail infinitésimal: $$\delta{W}\triangleq\overrightarrow{F}\cdot\mathrm{d}\vec{\ell}=\overrightarrow{F}\cdot\vec{v}\cdot\mathrm{d}t$$

d'où le travail global: $$W_{A\rightarrow{B}}(\overrightarrow{F})\triangleq\int_A^B{\overrightarrow{F}\cdot\mathrm{d}\vec{\ell}}$$
Cas d'une force constante: $$W_{A\rightarrow{B}}(\overrightarrow{F})=\overrightarrow{F}\cdot\overrightarrow{AB}$$

Puissance: $$\mathscr{P}\triangleq\frac{\delta{W}}{\mathrm{d}t}=\overrightarrow{F}\cdot{\vec{v}}$$
## 3.2. Champs de forces conservatives
### 3.2.1. Travail du poids

$$W_{A\rightarrow{B}}(\overrightarrow{P})=mg(\Delta_{A\rightarrow{B}}z)$$
### 3.2.2. Travail de la force électrostatique

$$W_\Gamma(\overrightarrow{F_{élec}}) = \int_\Gamma{q\overrightarrow{E}\cdot\mathrm{d}\ell}$$$$=\int_\Gamma{q\Bigl(-\frac{\partial{U}}{\partial{x}}\overrightarrow{e_x}\Bigr)\cdot\Bigl({\partial{x}\overrightarrow{e_x}+\partial{y}\overrightarrow{e_y}+\partial{z}\overrightarrow{e_{z}}}\Bigr)}$$$$=q(\Delta_{A\rightarrow{B}}U)$$
