# Registro de Prompts

En este archivo debés documentar los prompts que usaste con herramientas de IA
(GitHub Copilot, ChatGPT, etc.) durante el desarrollo del TP.

**¿Por qué?** Queremos que aprendas a trabajar con IA de forma reflexiva:
que sepas qué le pediste, qué obtuviste, y si tuviste que corregirlo.

---

## Formato para cada entrada

```
### [Número] - [Módulo]

**Herramienta**: GitHub Copilot / ChatGPT / otra

**Prompt usado**:
> Escribí acá exactamente lo que le pediste a la IA

**Resultado obtenido**:
Describí brevemente qué generó (código, explicación, etc.)

**¿Lo usaste tal cual o lo modificaste?**
Explicá qué cambios hiciste y por qué (o por qué no cambiaste nada).
```

---

## Registro de Prompts
## Aca anote como use la IA para que me ayude con el TP.

### 1 - variables.py

**Herramienta**: Microsoft Copilot

**Prompt usado**: Pasame una receta paso a paso para hacer funciones simples en python: un saludo, una suma, ver si es mayor de edad y tipos de datos.
> 

**Resultado obtenido**:
Me dio el codigo base y me explico como funcionan los tipos de datos en python 3.13.

**¿Lo usaste tal cual o lo modificaste?**
Lo tuve que tocar un poco. El saludo me lo dio con signos de exclamacion (tipo "Hola, Ana!") y el pytest me daba error porque buscaba solo "Hola, Ana!".

---

### 2 - condicionales.py


**Prompt usado**:Quiero hacer funciones para clasificar numeros y ver si un año es bisiesto. Antes de darme el codigo repasemos con preguntas para ver si entendi la logica.
> 

**Resultado obtenido**:
Me pregunto como iba a manejar el cero y que pasaba con los años que son multiplos de 100 y 400.

**¿Lo usaste tal cual o lo modificaste?**
Casi tal cual. Despues de responderle las preguntas me tiro el codigo de es_bisiesto y paso todos los tests de una.

---

### 3 - listas.py


**Prompt usado**:Estoy con un ejercicio de listas (sumar, filtrar pares e invertir). 

**Resultado obtenido**:
Me aviso que si la lista llegaba vacia el promedio me podia dar error de division por cero.

**¿Lo usaste tal cual o lo modificaste?**
Cambie mi idea original y le agregue el if para las listas vacias como me sugirio, asi no rompe el test.

---

### 4 - diccionarios.py


**Prompt usado**:
Dame varios ejemplos de diccionarios de usuarios y mostrame distintas formas de mezclarlos o filtrarlos para ver como se hace en python.
> 

**Resultado obtenido**:
Me tiro un monton de ejemplos y me mostro como usar el operador | para unir diccionarios.

**¿Lo usaste tal cual o lo modificaste?**
Lo use para aprender la sintaxis nueva y lo aplique para que el codigo quede mas limpio.

---

### 5 - loops.py


**Prompt usado**: ¿Como se hace para saber si un numero es primo con un bucle? ¿Hay alguna forma de que sea mas rapido? Mostrame tambien fibonacci.
> 

**Resultado obtenido**:
Me explico que no hace falta probar todos los numeros, sino que con llegar hasta la raiz cuadrada ya alcanza.

**¿Lo usaste tal cual o lo modificaste?**
Use la version optimizada que me dio porque me parecio mas pro y servia para que los tests corran bien.


---

### 6 - funciones.py


**Prompt usado**:Tengo que hacer una funcion que reduzca una lista pero sin usar librerias. ¿Que es mejor, usar recursividad o un bucle for? dame pros y contras.
> 

**Resultado obtenido**:
Me dijo que para este nivel era mejor un bucle for comun con un acumulador porque es mas facil de entender y no se rompe si la lista es muy larga.

**¿Lo usaste tal cual o lo modificaste?**
Le hice caso y use el for manual. Quedo mucho mas simple y paso el test al toque.

---

### 7 - operaciones.py


**Prompt usado**: Necesito ver si una palabra es palindromo y contar vocales. Mostrame formas de hacerlo.
> 

**Resultado obtenido**:
Me mostro las tres formas. con bucles, con compresion de listas y La de slicing con [::-1] me parecio la mas cortita.

**¿Lo usaste tal cual o lo modificaste?**
Elegi la de slicing y la de comprension de listas porque el codigo queda re corto.


---

## Reflexión final

Respondé brevemente (3-5 oraciones):

- ¿Qué aprendiste sobre cómo formular buenos prompts?
- ¿En qué casos la IA fue útil y en cuáles no?
- ¿Qué harías diferente la próxima vez?

Aprendi que si no sos especifico con el prompt la ia te tira cualquier cosa o le erra a los formatos que pide el test. Me sirvio mucho para darme cuenta de errores que no veia, como lo de las listas vacias. Lo que haria distinto la proxima es pasarle desde el principio el formato exacto que quiero para no tener que andar corrigiendo comas o signos de exclamacion despues, aprendi mucho utilizando la ia, podia preguntarles cosas especificas del codigo que me armaba y lo senti mucho mas comodo que ver videos sobre el tema o leer la teoria, se adaptaba a mi y eso me gusto.
