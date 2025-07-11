# Assistant Maths - Fonctions du second degré

Bonjour ! Je suis votre assistant pour le **Chapitre 1 : Fonctions polynômes du second degré**.

Que souhaitez-vous réviser aujourd'hui ?

1. [📚 Définitions et vocabulaire](définitions)
2. [🎯 Trouver les racines](racines)
3. [📊 Étudier le signe](signe)
4. [🔗 Relations coefficients-racines](relations)
5. [💡 Exercices guidés](exercices)
6. [❓ J'ai une question spécifique](questions)

---

## définitions

### 📚 Définitions et vocabulaire

**Forme développée :** f(x) = ax² + bx + c (avec a ≠ 0)

**Forme factorisée :** f(x) = a(x - α)(x - β)

**Exemples :**
- f(x) = 2(x - 1)(x + 3) → a = 2, α = 1, β = -3
- g(x) = 3x² - 6x + 2 → forme développée

**Points clés :**
- Le coefficient a ne peut jamais être nul
- La forme factorisée permet de lire directement les racines
- Les deux formes décrivent la même fonction

1. [🎯 Comment trouver les racines ?](racines)
2. [📊 Comment étudier le signe ?](signe)
3. [🏠 Retour au menu principal](menu principal)

## racines

### 🎯 Trouver les racines d'une fonction

**Définition :** Les racines sont les valeurs de x pour lesquelles f(x) = 0.

**Méthode avec la forme factorisée :**

Si f(x) = a(x - α)(x - β), alors les racines sont **α** et **β**.

**Exemple :** f(x) = -2(x - 5)(x + 1)
- Racines : 5 et -1
- Vérification : f(5) = 0 et f(-1) = 0

**Cas particulier :** f(x) = 3(x + 2)²
- Une seule racine (double) : -2

1. [📊 Maintenant, étudier le signe](signe)
2. [💡 Voir un exercice guidé](exercice racines)
3. [🏠 Retour au menu principal](menu principal)

## signe

### 📊 Étudier le signe d'une fonction

**Principe :** Utiliser un tableau de signes avec f(x) = a(x - α)(x - β)

**Méthode en 4 étapes :**

1. **Identifier** a, α et β
2. **Placer** les racines sur une droite
3. **Étudier** le signe de chaque facteur
4. **Appliquer** la règle des signes

**Exemple détaillé :** f(x) = -3(x - 1)(x + 2)
- a = -3 < 0, racines : -2 et 1
- f(x) < 0 pour x ∈ ]-∞;-2[ ∪ ]1;+∞[
- f(x) > 0 pour x ∈ ]-2;1[

1. [💡 Voir l'exercice complet](exercice signe)
2. [🔗 Relations coefficients-racines](relations)
3. [🏠 Retour au menu principal](menu principal)

## relations

### 🔗 Relations entre coefficients et racines

**Si f(x) = ax² + bx + c a deux racines α et β :**

**Somme :** α + β = -b/a
**Produit :** α × β = c/a

**Application pratique :**
Quand une racine est évidente, on trouve l'autre facilement !

**Exemple :** f(x) = 2x² - 6x + 4
- f(1) = 0 donc 1 est une racine
- α + β = 6/2 = 3, donc 1 + β = 3 → β = 2
- Vérification : α × β = 4/2 = 2 ✓

**Cas particulier :** Si une racine vaut 1, l'autre vaut c/a.

1. [💡 Exercice avec relations](exercice relations)
2. [📚 Revoir les définitions](définitions)
3. [🏠 Retour au menu principal](menu principal)

## exercices

### 💡 Exercices guidés

Choisissez le type d'exercice que vous voulez travailler :

1. [🎯 Trouver les racines](exercice racines)
2. [📊 Étudier le signe](exercice signe)
3. [🔗 Utiliser les relations](exercice relations)
4. [🔄 Passer d'une forme à l'autre](exercice formes)
5. [🏠 Retour au menu principal](menu principal)

## exercice racines

### 🎯 Exercice : Trouver les racines

**Énoncé :** Déterminer les racines de f(x) = 5(x - 3)(x + 7)

**Solution étape par étape :**

1. **Identifier la forme :** f(x) = a(x - α)(x - β)
   - a = 5, α = 3, β = -7

2. **Lire les racines :** α = 3 et β = -7

3. **Vérification :**
   - f(3) = 5(3-3)(3+7) = 5×0×10 = 0 ✓
   - f(-7) = 5(-7-3)(-7+7) = 5×(-10)×0 = 0 ✓

**Réponse :** Les racines sont **3** et **-7**.

1. [📊 Maintenant étudions le signe](exercice signe)
2. [💡 Autre exercice](exercices)
3. [🏠 Retour au menu principal](menu principal)

## exercice signe

### 📊 Exercice : Étude du signe

**Énoncé :** Étudier le signe de f(x) = 2(x - 1)(x + 4)

**Solution complète :**

1. **Identification :** a = 2 > 0, racines : -4 et 1

2. **Tableau de signes :**
```
x        | -∞    -4     1    +∞
---------|--------------------
2        |  +     +     +     +
x + 4    |  -     0     +     +
x - 1    |  -     -     0     +
f(x)     |  +     0     -     0     +
```

3. **Conclusion :**
   - f(x) > 0 pour x ∈ ]-∞;-4[ ∪ ]1;+∞[
   - f(x) = 0 pour x ∈ {-4 ; 1}
   - f(x) < 0 pour x ∈ ]-4;1[

1. [🔗 Exercice avec relations](exercice relations)
2. [💡 Autre exercice](exercices)
3. [🏠 Retour au menu principal](menu principal)

## exercice relations

### 🔗 Exercice : Relations coefficients-racines

**Énoncé :** Soit f(x) = 3x² - 12x + 9. On remarque que f(1) = 0.
Trouver l'autre racine sans résoudre l'équation.

**Solution :**

1. **Données :** a = 3, b = -12, c = 9, une racine α = 1

2. **Utilisation des relations :**
   - Somme : α + β = -b/a = 12/3 = 4
   - Donc : 1 + β = 4 → β = 3

3. **Vérification avec le produit :**
   - α × β = c/a = 9/3 = 3
   - 1 × 3 = 3 ✓

**Réponse :** L'autre racine est **3**.

**Vérification finale :** f(3) = 3(9) - 12(3) + 9 = 27 - 36 + 9 = 0 ✓

1. [🔄 Exercice changement de forme](exercice formes)
2. [💡 Autre exercice](exercices)
3. [🏠 Retour au menu principal](menu principal)

## exercice formes

### 🔄 Exercice : Passer d'une forme à l'autre

**Énoncé :** Développer f(x) = -2(x - 3)(x + 1)

**Solution :**

1. **Développer le produit :**
   f(x) = -2(x - 3)(x + 1)
   = -2(x² + x - 3x - 3)
   = -2(x² - 2x - 3)
   = -2x² + 4x + 6

2. **Forme développée :** f(x) = -2x² + 4x + 6

**Vérification :** Les racines restent 3 et -1 dans les deux formes !

1. [💡 Autre exercice](exercices)
2. [📚 Revoir la théorie](définitions)
3. [🏠 Retour au menu principal](menu principal)

## questions

### ❓ Questions fréquentes

**Voici les questions les plus posées :**

1. [Comment savoir si une fonction est du second degré ?](question degré)
2. [Pourquoi a ≠ 0 ?](question coefficient a)
3. [Une fonction peut-elle n'avoir qu'une seule racine ?](question racine unique)
4. [Comment passer de la forme développée à factorisée ?](question factorisation)
5. [À quoi servent les relations coefficients-racines ?](question utilité relations)
6. [🏠 Retour au menu principal](menu principal)

## question degré

### Comment savoir si une fonction est du second degré ?

**Réponse :** Une fonction est du second degré si :
- Elle contient un terme en x²
- Le coefficient de x² n'est pas nul
- C'est le plus haut degré présent

**Exemples :**
✅ f(x) = 3x² - 2x + 1 (degré 2)
✅ g(x) = -x² + 5 (degré 2)
❌ h(x) = 2x + 3 (degré 1)
❌ k(x) = x³ - x² + 1 (degré 3)

1. [❓ Autre question](questions)
2. [🏠 Retour au menu principal](menu principal)

## question coefficient a

### Pourquoi a ≠ 0 ?

**Réponse :** Si a = 0, alors f(x) = 0×x² + bx + c = bx + c

La fonction devient du **premier degré** (fonction affine), plus du second degré !

C'est pourquoi on impose toujours a ≠ 0 dans la définition.

1. [❓ Autre question](questions)
2. [🏠 Retour au menu principal](menu principal)

## question racine unique

### Une fonction peut-elle n'avoir qu'une seule racine ?

**Réponse :** Oui ! Cela arrive quand α = β dans la forme factorisée.

**Exemple :** f(x) = 2(x - 3)² = 2(x - 3)(x - 3)
- Une seule racine : 3 (on dit qu'elle est "double")

**Graphiquement :** La parabole ne fait que "toucher" l'axe des x, sans le traverser.

1. [❓ Autre question](questions)
2. [🏠 Retour au menu principal](menu principal)

## question factorisation

### Comment passer de la forme développée à factorisée ?

**Réponse :** C'est l'objet de la partie 2 du chapitre ! Pour l'instant, nous savons seulement :
- Lire les racines quand la forme factorisée est donnée
- Utiliser les relations entre coefficients et racines

**Aperçu :** Il faudra utiliser le discriminant Δ = b² - 4ac

1. [❓ Autre question](questions)
2. [🏠 Retour au menu principal](menu principal)

## question utilité relations

### À quoi servent les relations coefficients-racines ?

**Réponse :** Elles permettent de :
1. **Trouver une racine** quand on en connaît une
2. **Vérifier** ses calculs rapidement
3. **Résoudre** certains problèmes sans discriminant

**Astuce :** Si une racine vaut 1, l'autre vaut automatiquement c/a !

**Exemple concret :** En contrôle, si vous trouvez une racine évidente, vous gagnez du temps avec ces relations.

1. [❓ Autre question](questions)
2. [🏠 Retour au menu principal](menu principal)

## menu principal

# Assistant Maths - Fonctions du second degré

Que souhaitez-vous réviser ?

1. [📚 Définitions et vocabulaire](définitions)
2. [🎯 Trouver les racines](racines)
3. [📊 Étudier le signe](signe)
4. [🔗 Relations coefficients-racines](relations)
5. [💡 Exercices guidés](exercices)
6. [❓ J'ai une question spécifique](questions)