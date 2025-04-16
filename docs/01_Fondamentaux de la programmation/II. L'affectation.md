### **Affectation d'une variable**  
L'affectation consiste à **stocker une valeur dans une variable** en utilisant l'opérateur `=`.  
👉 *Exemple :*  
```python
x = 10  # On affecte la valeur 10 à la variable x
```

---

### **Ce qui se passe en mémoire**  
1. Python crée la valeur **10** en mémoire.  
2. Il lie cette valeur au nom **`x`** (comme une étiquette).  


---

### **Caractéristiques clés**  
1. **Dynamic typing** : Le type de la variable est déterminé automatiquement.  
   ```python
   x = 10      # x est un entier (int)
   x = "hello"  # Maintenant x est une chaîne (str) → Pas d'erreur !
   ```  
2. **Réaffectation possible** : La même variable peut changer de valeur.  
3. **Opérateur = est un liage** : `y = x` copie la **référence**, pas la valeur.  

---

### **Exemple concret**  
```python
a = 5    # Affectation initiale  
b = a    # b pointe vers la même valeur que a  
a = 8    # Réaffectation de a  

print(b) # Affiche 5 (b n'est pas modifié)
```

---

### **À retenir**  
- `=` **n'est pas** une égalité mathématique, mais une **assignation**.  
- Une variable peut être réaffectée à tout moment.  
