### **Représentation des Entiers Naturels en Binaire**  

#### **1. Qu'est-ce que le binaire ?**  
Le **système binaire** (base 2) est un système de numération qui n'utilise que deux chiffres : **0** et **1**.  
Contrairement au système décimal (base 10, chiffres de 0 à 9), chaque position en binaire représente une **puissance de 2**.  

#### **2. Conversion Décimal → Binaire**  
Pour convertir un entier naturel (positif) en binaire, on utilise des **divisions successives par 2** et on note les **restes** dans l'ordre inverse.  

**Exemple : Convertir 13 en binaire**  
```
13 ÷ 2 = 6 → reste 1  
6 ÷ 2 = 3 → reste 0  
3 ÷ 2 = 1 → reste 1  
1 ÷ 2 = 0 → reste 1  
```
Lecture des restes **de bas en haut** → `1101`  
✅ **13 (décimal) = 1101 (binaire)**  

#### **3. Conversion Binaire → Décimal**  
Chaque bit (0 ou 1) est associé à une puissance de 2, en partant de la droite (poids faible).  

**Exemple : Convertir 1011 en décimal**  
```
1 0 1 1  
↓ ↓ ↓ ↓  
1×2³ + 0×2² + 1×2¹ + 1×2⁰ = 8 + 0 + 2 + 1 = 11  
```
✅ **1011 (binaire) = 11 (décimal)**  

#### **4. Représentation sur un Nombre de Bits Fixe**  
En informatique, les entiers sont souvent stockés sur **8, 16, 32 ou 64 bits**.  
- Exemple pour **5 sur 4 bits** : `0101` (les bits inutilisés sont mis à 0).  
- **Limite** : Sur **n bits**, on peut représenter les entiers de **0 à 2ⁿ - 1**.  
  - Exemple : 8 bits → 0 à 255.  

#### **5. Applications**  
- **Mémoire des ordinateurs** : Toutes les données sont stockées en binaire.  
- **Manipulation de bits** : Utilisé en cryptographie, réseaux, etc.  

#### **Exercice Pratique**  
1. Convertir **25** en binaire.  
2. Convertir **11001** en décimal.  

**Réponses :**  
1. `25 → 11001` (car 16 + 8 + 1 = 25)  
2. `11001 → 25`  

---
