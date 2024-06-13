# Quipudigital

Una biblioteca de visualización para Python

# Estrcutura del Proyecto

```
|--assets/        <-- archivos GIF para construir un quipu
|--quipudigital/  <-- Archivos de python
|--setup.py       <-- Define el Python build
```

# Uso

Un ejemplo de como usar la biblioteca

```
import quipudigital.main as qd

```

```
numbers =[1000, 2024, 1234 , 5234, 120, 1000]

quipu = qd.Quipu(numbers)

quipu.screen.setup(width=0.99, height=0.99)  

quipu.draw()
```