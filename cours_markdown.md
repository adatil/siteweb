# Chapitre 1 : Fonction polynôme du second degré

*Partie 1 : formes développée et factorisée. Racines.*

---

## Introduction

### Objectifs du chapitre

À la fin de ce chapitre, vous saurez :
- Reconnaître une fonction polynôme du second degré sous forme factorisée ou développée
- Déterminer les racines d'une fonction polynôme du second degré donnée sous forme factorisée
- Étudier le signe d'une fonction polynôme du second degré donnée sous forme factorisée
- Utiliser les relations entre coefficients et racines notamment quand on connaît une racine

Les fonctions polynômes du second degré sont omniprésentes en mathématiques et dans de nombreux domaines d'application : physique (trajectoires de projectiles), économie (optimisation de profits), géométrie (calculs d'aires)...

## Définitions et vocabulaire

### Définition 1 - Forme développée

Une **fonction polynôme du second degré** est une fonction $f$ définie sur $\mathbb{R}$ par :

$$f(x) = ax^2 + bx + c$$

où $a$, $b$ et $c$ sont des nombres réels avec $a \neq 0$.

On dit que cette fonction est donnée sous **forme développée réduite**.

### Définition 2 - Forme factorisée

Une fonction polynôme du second degré est donnée sous **forme factorisée** lorsqu'elle s'écrit :

$$f(x) = a(x - \alpha)(x - \beta)$$

où $a \neq 0$, et $\alpha$ et $\beta$ sont des nombres réels.

### Exemples

- $f(x) = 2(x - 1)(x + 3)$ est sous forme factorisée avec $a = 2$, $\alpha = 1$ et $\beta = -3$
- $g(x) = -\frac{1}{2}(x - 4)(x - 7)$ est sous forme factorisée avec $a = -\frac{1}{2}$, $\alpha = 4$ et $\beta = 7$
- $h(x) = 3(x + 2)^2$ peut s'écrire $h(x) = 3(x - (-2))(x - (-2))$ avec $\alpha = \beta = -2$

## Racines d'une fonction polynôme du second degré

### Définition

Les **racines** (ou **zéros**) d'une fonction polynôme du second degré $f$ sont les valeurs de $x$ pour lesquelles $f(x) = 0$.

Graphiquement, les racines correspondent aux abscisses des points d'intersection de la courbe représentative avec l'axe des abscisses.

### ⚠️ Remarque importante 

L'axe de symétrie de la parabole passe par le point d'abscisse égale à la moyenne des racines.

*Exemple :* Pour des racines $-1$ et $5$, la moyenne $= \frac{-1 + 5}{2} = 2$.

L'axe de symétrie a donc pour équation $x = 2$, et c'est aussi l'abscisse du sommet.

### Lecture directe des racines

**Propriété :** Si une fonction polynôme du second degré est donnée sous forme factorisée :

$$f(x) = a(x - \alpha)(x - \beta)$$

alors les valeurs $\alpha$ et $\beta$ sont les racines de la fonction $f$.

**Justification :**
- $f(\alpha) = a(\alpha - \alpha)(\alpha - \beta) = a \times 0 \times (\alpha - \beta) = 0$
- $f(\beta) = a(\beta - \alpha)(\beta - \beta) = a \times (\beta - \alpha) \times 0 = 0$

On admet de plus que si une fonction du second degré $f$ définie sur $\mathbb{R}$ par $f(x) = ax^2 + bx + c$ admet deux racines $\alpha$ et $\beta$ alors on peut écrire : $f(x) = a(x - \alpha)(x - \beta)$

### Exemple

Déterminons les racines de $f(x) = -2(x - 5)(x + 1)$.

La fonction est sous forme factorisée avec $a = -2$, $\alpha = 5$ et $\beta = -1$.

Les racines sont donc $5$ et $-1$.

**Vérification :**
- $f(5) = -2(5 - 5)(5 + 1) = -2 \times 0 \times 6 = 0$
- $f(-1) = -2(-1 - 5)(-1 + 1) = -2 \times (-6) \times 0 = 0$

## Étude du signe d'une fonction polynôme du second degré

### Rappel : Signe d'une fonction affine

Soit $f(x) = ax + b$ une fonction affine avec $a \neq 0$.

La fonction $f$ s'annule pour $x = -\frac{b}{a}$.

**Si $a > 0$ :**
- $f(x) < 0$ pour $x < -\frac{b}{a}$
- $f(x) = 0$ pour $x = -\frac{b}{a}$
- $f(x) > 0$ pour $x > -\frac{b}{a}$

**Si $a < 0$ :**
- $f(x) > 0$ pour $x < -\frac{b}{a}$
- $f(x) = 0$ pour $x = -\frac{b}{a}$
- $f(x) < 0$ pour $x > -\frac{b}{a}$

### Exemple de fonction affine

Étudions le signe de $g(x) = 3x - 6$.

On a $a = 3 > 0$ et $b = -6$.

$g(x) = 0 \Leftrightarrow 3x - 6 = 0 \Leftrightarrow x = 2$

Comme $a > 0$ :
- $g(x) < 0$ pour $x < 2$
- $g(x) = 0$ pour $x = 2$
- $g(x) > 0$ pour $x > 2$

### Signe d'une fonction du second degré

L'étude du signe d'une fonction polynôme du second degré sous forme factorisée se fait en utilisant un tableau de signes.

**Propriété :** Soit $f(x) = a(x - \alpha)(x - \beta)$ avec $\alpha \leq \beta$.

Le signe de $f(x)$ est obtenu en appliquant la règle des signes au produit :
$$f(x) = a \times (x - \alpha) \times (x - \beta)$$

### Exemple détaillé

Étudions le signe de $f(x) = -3(x - 1)(x + 2)$.

**Identification :** $a = -3 < 0$, racines : $-2$ et $1$

**Tableau de signes :**

| $x$ | $-\infty$ | $-2$ | | $1$ | $+\infty$ |
|-----|-----------|------|---|-----|-----------|
| $-3$ | $-$ | $-$ | $-$ | $-$ | $-$ |
| $x + 2$ | $-$ | $0$ | $+$ | $+$ | $+$ |
| $x - 1$ | $-$ | $-$ | $-$ | $0$ | $+$ |
| $(x + 2)(x - 1)$ | $+$ | $0$ | $-$ | $0$ | $+$ |
| $f(x) = -3(x + 2)(x - 1)$ | $-$ | $0$ | $+$ | $0$ | $-$ |

**Conclusion :**
- $f(x) < 0$ pour $x \in ]-\infty ; -2[ \cup ]1 ; +\infty[$
- $f(x) = 0$ pour $x \in \{-2 ; 1\}$
- $f(x) > 0$ pour $x \in ]-2 ; 1[$

## Relations entre coefficients et racines

Lorsqu'une fonction polynôme du second degré admet deux racines, il existe des relations importantes entre ces racines et les coefficients de la forme développée.

### Propriété fondamentale

Soit $f(x) = ax^2 + bx + c$ une fonction polynôme du second degré admettant deux racines $\alpha$ et $\beta$.

Alors :
- **Somme des racines :** $\alpha + \beta = -\frac{b}{a}$
- **Produit des racines :** $\alpha \times \beta = \frac{c}{a}$

### Démonstration

Si $f(x) = ax^2 + bx + c$ admet deux racines $\alpha$ et $\beta$, alors on peut écrire :
$f(x) = a(x - \alpha)(x - \beta)$

Développons la forme factorisée :
$$\begin{align}
f(x) &= a(x - \alpha)(x - \beta) \\
&= a(x^2 - \beta x - \alpha x + \alpha \beta) \\
&= a(x^2 - (\alpha + \beta)x + \alpha \beta) \\
&= ax^2 - a(\alpha + \beta)x + a\alpha \beta
\end{align}$$

Par identification avec $f(x) = ax^2 + bx + c$ :
- Coefficient de $x$ : $b = -a(\alpha + \beta) \Rightarrow \alpha + \beta = -\frac{b}{a}$
- Terme constant : $c = a\alpha \beta \Rightarrow \alpha \beta = \frac{c}{a}$

### Exemple d'application

Soit $f(x) = 2x^2 - 6x + 4$.

On remarque que $f(1) = 2(1)^2 - 6(1) + 4 = 2 - 6 + 4 = 0$.

Donc $1$ est une racine évidente de $f$.

On a $a = 2$, $b = -6$, $c = 4$.

D'après les relations entre coefficients et racines :
- $\alpha + \beta = -\frac{(-6)}{2} = 3$
- $\alpha \times \beta = \frac{4}{2} = 2$

Comme $\alpha = 1$, on a :
- $1 + \beta = 3 \Rightarrow \beta = 2$
- $1 \times \beta = 2 \Rightarrow \beta = 2$

Les deux relations donnent bien $\beta = 2$. Les racines de $f$ sont donc $1$ et $2$.

**Vérification :** $f(2) = 2(2)^2 - 6(2) + 4 = 8 - 12 + 4 = 0$

### Méthode pratique

Lorsqu'une racine est évidente, on peut utiliser les relations entre coefficients et racines pour trouver l'autre racine rapidement.

**Méthode :** Si $\alpha$ est une racine connue et $\beta$ l'autre racine :
- $\beta = -\frac{b}{a} - \alpha$ (en utilisant la somme)
- Vérifier avec le produit : $\alpha \times \beta = \frac{c}{a}$
- On retiendra en particulier que quand une des racines vaut $1$, l'autre vaut $\frac{c}{a}$ (car le produit vaut $\frac{c}{a}$)