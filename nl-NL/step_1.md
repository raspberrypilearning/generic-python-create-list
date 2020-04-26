Een Python-lijst is een type data-structuur. Het kan verzamelingen van elk gegevenstype bevatten, en zelfs een combinatie van gegevenstypes. Hier is een lege lijst:

```python
een_lege_lijst = []
```

Je kunt een lijst maken door deze een naam te geven en de gegevensitems tussen vierkante haken toe te voegen:

```python
kompas = ["noord", "zuid", "oost", "west"]
```

Nadat een lijst is gemaakt, kun je meer gegevens aan de lijst toevoegen met behulp van `append`:

```python
getallen = [5, 10, 15, 20]
getallen.append(25)
print(getallen)

[5, 10, 15, 20, 25]
```

Je kunt gegevens uit de lijst verwijderen met `remove`:

```python
getallen.remove(5)
print(getallen)

[10, 15, 20, 25]
```
