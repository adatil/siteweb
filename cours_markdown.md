# Fonctions polynômes du second degré

**Chapitre 1 - Partie 1 : Formes développée et factorisée. Racines.**

---

## 🎯 Objectifs du chapitre

À la fin de ce chapitre, vous saurez :

• Reconnaître une fonction polynôme du second degré sous forme factorisée ou développée  
• Déterminer les racines d'une fonction polynôme du second degré donnée sous forme factorisée  
• Étudier le signe d'une fonction polynôme du second degré donnée sous forme factorisée  
• Utiliser les relations entre coefficients et racines notamment quand on connaît une racine  

Les fonctions polynômes du second degré sont omniprésentes en mathématiques et dans de nombreux domaines : physique (trajectoires), économie (optimisation), géométrie (calculs d'aires)...

---

## 📚 Définitions et vocabulaire

### 🔵 Définition 1 : Forme développée

Une **fonction polynôme du second degré** est une fonction f définie sur ℝ par :

f(x) = ax² + bx + c

où a, b et c sont des nombres réels avec a ≠ 0.

On dit que cette fonction est donnée sous **forme développée réduite**.

### 🔵 Définition 2 : Forme factorisée  

Une fonction polynôme du second degré est donnée sous **forme factorisée** lorsqu'elle s'écrit :

f(x) = a(x - α)(x - β)

où a ≠ 0, et α et β sont des nombres réels.

### 💡 Exemples

**Exemple 1 :** f(x) = 2(x - 1)(x + 3)  
→ Forme factorisée avec a = 2, α = 1 et β = -3

**Exemple 2 :** g(x) = -½(x - 4)(x - 7)  
→ Forme factorisée avec a = -½, α = 4 et β = 7

**Exemple 3 :** h(x) = 3(x + 2)²  
→ Peut s'écrire h(x) = 3(x - (-2))(x - (-2)) avec α = β = -2

---

## 🎯 Racines d'une fonction polynôme du second degré

### 🔵 Définition

Les **racines** (ou **zéros**) d'une fonction polynôme du second degré f sont les valeurs de x pour lesquelles f(x) = 0.

**Graphiquement :** les racines correspondent aux abscisses des points d'intersection de la courbe avec l'axe des abscisses.

### ⚠️ Remarque importante

L'axe de symétrie de la parabole passe par le point d'abscisse égale à la moyenne des racines.

**Exemple :** Pour des racines -1 et 5, la moyenne = (-1 + 5)/2 = 2  
→ L'axe de symétrie a pour équation x = 2, et c'est aussi l'abscisse du sommet.

### 🟢 Propriété : Lecture directe des racines

Si une fonction polynôme du second degré est donnée sous forme factorisée :

f(x) = a(x - α)(x - β)

alors les valeurs α et β sont les racines de la fonction f.

**Justification :**
• f(α) = a(α - α)(α - β) = a × 0 × (α - β) = 0  
• f(β) = a(β - α)(β - β) = a × (β - α) × 0 = 0

### 💡 Exemple détaillé

**Énoncé :** Déterminons les racines de f(x) = -2(x - 5)(x + 1)

**Solution :**  
La fonction est sous forme factorisée avec a = -2, α = 5 et β = -1.  
→ Les racines sont donc **5** et **-1**.

**Vérification :**  
• f(5) = -2(5 - 5)(5 + 1) = -2 × 0 × 6 = 0 ✓  
• f(-1) = -2(-1 - 5)(-1 + 1) = -2 × (-6) × 0 = 0 ✓

---

## 📊 Étude du signe d'une fonction polynôme du second degré

### 📋 Rappel : Signe d'une fonction affine

Soit f(x) = ax + b une fonction affine avec a ≠ 0.

La fonction f s'annule pour x = -b/a.

**Si a > 0 :**  
• f(x) < 0 pour x < -b/a  
• f(x) = 0 pour x = -b/a  
• f(x) > 0 pour x > -b/a  

**Si a < 0 :**  
• f(x) > 0 pour x < -b/a  
• f(x) = 0 pour x = -b/a  
• f(x) < 0 pour x > -b/a  

### 💡 Exemple fonction affine

**Énoncé :** Étudions le signe de g(x) = 3x - 6

**Solution :**  
On a a = 3 > 0 et b = -6.  
g(x) = 0 ⟺ 3x - 6 = 0 ⟺ x = 2

Comme a > 0 :  
• g(x) < 0 pour x < 2  
• g(x) = 0 pour x = 2  
• g(x) > 0 pour x > 2  

### 🟢 Propriété : Signe d'une fonction du second degré

Soit f(x) = a(x - α)(x - β) avec α ≤ β.

Le signe de f(x) est obtenu en appliquant la règle des signes au produit :

f(x) = a × (x - α) × (x - β)

### 💡 Exemple détaillé avec tableau de signes

**Énoncé :** Étudions le signe de f(x) = -3(x - 1)(x + 2)

**Identification :** a = -3 < 0, racines : -2 et 1

**Tableau de signes :**

```
x           | -∞      -2       1      +∞
------------|---------------------------- 
-3          |  -       -       -       -
x + 2       |  -       0       +       +
x - 1       |  -       -       0       +
(x+2)(x-1)  |  +       0       -       0       +
f(x)        |  -       0       +       0       -
```

**Conclusion :**  
• f(x) < 0 pour x ∈ ]-∞ ; -2[ ∪ ]1 ; +∞[  
• f(x) = 0 pour x ∈ {-2 ; 1}  
• f(x) > 0 pour x ∈ ]-2 ; 1[  

---

## 🔗 Relations entre coefficients et racines

### 🟢 Propriété fondamentale

Soit f(x) = ax² + bx + c une fonction polynôme du second degré admettant deux racines α et β.

Alors :

**Somme des racines :** α + β = -b/a  
**Produit des racines :** α × β = c/a  

### 📝 Démonstration

Si f(x) = ax² + bx + c admet deux racines α et β, alors on peut écrire :  
f(x) = a(x - α)(x - β)

Développons la forme factorisée :  
f(x) = a(x - α)(x - β)  
= a(x² - βx - αx + αβ)  
= a(x² - (α + β)x + αβ)  
= ax² - a(α + β)x + aαβ  

Par identification avec f(x) = ax² + bx + c :  
• Coefficient de x : b = -a(α + β) ⟹ α + β = -b/a  
• Terme constant : c = aαβ ⟹ αβ = c/a  

### 💡 Exemple d'application

**Énoncé :** Soit f(x) = 2x² - 6x + 4  
On remarque que f(1) = 2(1)² - 6(1) + 4 = 2 - 6 + 4 = 0  
Donc 1 est une racine évidente de f.

**Solution :**  
On a a = 2, b = -6, c = 4.

D'après les relations entre coefficients et racines :  
• α + β = -(-6)/2 = 3  
• α × β = 4/2 = 2  

Comme α = 1, on a :  
• 1 + β = 3 ⟹ β = 2  
• 1 × β = 2 ⟹ β = 2  

Les deux relations donnent bien β = 2.  
→ Les racines de f sont **1** et **2**.

**Vérification :** f(2) = 2(2)² - 6(2) + 4 = 8 - 12 + 4 = 0 ✓

### 🔧 Méthode pratique

Lorsqu'une racine est évidente, on peut utiliser les relations entre coefficients et racines pour trouver l'autre racine rapidement.

**Méthode :** Si α est une racine connue et β l'autre racine :  
• β = -b/a - α (en utilisant la somme)  
• Vérifier avec le produit : α × β = c/a  
• **Cas particulier :** quand une des racines vaut 1, l'autre vaut c/a