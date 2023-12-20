### Cheat Sheet : Calcul de la Complexité en JavaScript

#### Notations de Complexité

- **O(1)** : Constante
- **O(log n)** : Logarithmique
- **O(n)** : Linéaire
- **O(n log n)** : Linéarithmique
- **O(n^2)** : Quadratique
- **O(2^n)** : Exponentielle

#### Types de Boucles

1. **Boucle For :**

   ```javascript
   for (let i = 0; i < n; i++) {
     // Code
   }
   ```

   - Complexité : O(n)

2. **Boucle While :**

   ```javascript
   while (condition) {
     // Code
   }
   ```

   - Complexité dépend de la condition

3. **Boucle ForEach (Array) :**
   ```javascript
   array.forEach(function (element) {
     // Code
   });
   ```
   - Complexité : O(n)

#### Complexité des Opérations Courantes

1. **Accès à un Élément dans un Tableau :**

   - Complexité : O(1)

2. **Recherche dans un Tableau non Trié :**

   - Complexité : O(n)

3. **Recherche dans un Tableau Trié :**

   - Complexité : O(log n)

4. **Ajout/Suppression en Fin de Tableau :**

   - Complexité : O(1)

5. **Ajout/Suppression au Début de Tableau :**

   - Complexité : O(n)

6. **Ajout/Suppression dans un Tableau Trié :**

   - Complexité : O(n) pour la recherche + O(n) pour le décalage

7. **Objets JavaScript (Clés/Valeurs) :**
   - Accès, Ajout, Suppression : O(1) en moyenne

#### Récurssion

- **Complexité de la Récursion :**
  - Dépend du nombre d'appels récursifs
  - Examinez le nombre d'appels et la complexité de chaque appel

#### Exemples

1. **Recherche Binaire :**

   ```javascript
   function binarySearch(array, target) {
     // Code
   }
   ```

   - Complexité : O(log n)

2. **Tri par Fusion (Merge Sort) :**

   ```javascript
   function mergeSort(array) {
     // Code
   }
   ```

   - Complexité : O(n log n)

3. **Recherche Linéaire :**
   ```javascript
   function linearSearch(array, target) {
     // Code
   }
   ```
   - Complexité : O(n)
