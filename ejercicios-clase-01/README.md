# Clase 01 - Lógica operacional y Álgebra booleana

## Ejercicios de evaluación lógica

- True || (1 > 3) && (10 == 5)
- ! (5 < 5) && (40 % 10 == 0) && ! (False) || (2 * 5 >= 11)
- (33 % 2 == 0) || (2**3 + 1 == 9) || (4 >= 4) && False

### Solución

```python
True || False && False # True
True && True && True || False # True
False || True || True && False # True
```

---

## Problemas para pensar

- Voy a andar en bicicleta cuando el día esté soleado o nublado y si es fin de semana.
- Tengo que comprar frutas: si están frescas y el precio está dentro de mi presupuesto, las compro.

### Solución

```python
(soleado || nublado) && fin_de_semana
frescas && (precio <= presupuesto)
```