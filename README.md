## 🐍 Cours Python : La syntaxe de base

### 1. 💬 Afficher un message

```python
print("Bonjour, monde !")
```

### 2. 🔢 Variables et types

```python
nom = "Ahmed"      # Chaîne de caractères
age = 23           # Entier
taille = 1.75      # Nombre à virgule flottante
est_etudiant = True  # Booléen
```

### 3. 🧮 Opérations mathématiques

```python
a = 10
b = 3

print(a + b)  # Addition
print(a - b)  # Soustraction
print(a * b)  # Multiplication
print(a / b)  # Division
print(a % b)  # Modulo
print(a ** b) # Puissance
```

### 4. 🔀 Conditions (if / elif / else)

```python
note = 15

if note >= 16:
    print("Très bien")
elif note >= 10:
    print("Passable")
else:
    print("Échec")
```

### 5. 🔁 Boucles

#### ➤ Boucle **for**

```python
for i in range(5):  # de 0 à 4
    print(i)
```

#### ➤ Boucle **while**

```python
compteur = 0
while compteur < 5:
    print(compteur)
    compteur += 1
```

### 6. 🧰 Fonctions

```python
def saluer(nom):
    print("Salut", nom)

saluer("Ahmed")
```

### 7. 📦 Listes

```python
fruits = ["pomme", "banane", "orange"]
print(fruits[0])  # Affiche "pomme"

fruits.append("kiwi")  # Ajouter un élément
```

### 8. 📚 Dictionnaires

```python
personne = {
    "nom": "Ahmed",
    "âge": 23
}

print(personne["nom"])
```
