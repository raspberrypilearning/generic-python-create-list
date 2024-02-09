Une liste Python est un type de structure de données. Elle peut contenir des collections de n'importe quel type de données, et même un mélange de types de données. Voici une liste vide :

```python
liste_vide = []
```

Tu peux créer une liste en lui donnant un nom et en ajoutant les éléments de données entre crochets :

```python
boussole = ["nord", "sud", "est", "ouest"]
```

Une fois qu'une liste a été créée, tu peux y ajouter d'autres données à l'aide de `append` :

```python
nombres = [5, 10, 15, 20]
nombres.append(25)
print(nombres)

[5, 10, 15, 20, 25]
```

Tu peux te débarrasser d'une donnée de la liste en utilisant `remove` :

```python
nombres.remove(5)
print(nombres)

[10, 15, 20, 25]
```
