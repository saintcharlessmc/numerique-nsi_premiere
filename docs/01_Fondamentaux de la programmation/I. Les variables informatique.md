### **1. Définition d'une variable en Python**  
Une **variable** est un conteneur qui permet de stocker une valeur (nombre, texte, liste, etc.) en mémoire pour l'utiliser plus tard dans le code.  

En Python, une variable se crée en lui **assignant** une valeur avec le signe `=`.  

**Exemple :**  
```python
age = 25            # Variable de type entier (int)
nom = "Alice"        # Variable de type chaîne de caractères (str)
pi = 3.14            # Variable de type nombre décimal (float)
est_etudiant = True  # Variable de type booléen (bool)
```

📌 **Caractéristiques :**  
- Pas besoin de déclarer le type explicitement (Python le déduit).  
- Une variable peut être modifiée à tout moment.  

---

### **2. Comment choisir un nom de variable ?**  

#### **Règles de base (obligatoires)**  
- Doit commencer par une **lettre** ou un **underscore** `_`.  
- Peut contenir des lettres, chiffres et `_`.  
- **Sensible à la casse** (`maVariable` ≠ `mavariable`).  
- **Interdit** : mots-clés Python (`if`, `for`, `while`, etc.).  

**Exemples valides :**  
```python
prenom = "Luc"  
_age = 30  
note1 = 15.5  
```

**Exemples invalides :**  
```python
2nom = "Marie"    # Commence par un chiffre  
if = 10           # Mot-clé Python  
mon-nom = "Jean"  # Tirets interdits  
```

#### **Bonnes pratiques (recommandées)**  
- Utiliser des noms **clairs** et **descriptifs** (ex: `nombre_utilisateurs` au lieu de `n`).  
- Préférer la **snake_case** (mots séparés par `_`) pour la lisibilité.  
- Éviter les noms trop longs ou trop courts.  

**Exemple :**  
```python
# ✔️ Clair et lisible  
nombre_etudiants = 45  
temperature_max = 28.5  

# ❌ À éviter  
x = 45  
tmp = 28.5  
```

---

### **Résumé en code**  
```python
# Déclaration
ville = "Paris"
population = 2_141_000  # Les _ améliorent la lisibilité des grands nombres

# Réassignation
ville = "Lyon"

# Affichage
print("Ville :", ville)               # Lyon
print("Population :", population)     # 2141000
```

---

### **À toi de jouer !**  
Essaie ces exercices pour t'entraîner :  
1. Crée une variable `prix_ht` valant 100, puis calcule le `prix_ttc` (TVA à 20%).  
2. Pourquoi ce code génère une erreur ? Corrige-le :  
   ```python
   3suisses = "Magasin"  
   ```
