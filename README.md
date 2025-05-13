# 🧠 Ataque con Rainbow Tables a contraseñas MD5

Este proyecto forma parte de una práctica de la asignatura de **Criptografía** (3.º Ingeniería Matemática), cuyo objetivo es aplicar y analizar la técnica de *rainbow tables* para invertir funciones hash, concretamente sobre el algoritmo **MD5**.

## 🔍 Descripción

Las *rainbow tables* permiten precomputar cadenas de transformación entre contraseñas y hashes, reduciendo el tiempo necesario para romper contraseñas a costa de espacio en memoria. En este trabajo:

- Se ha limitado el espacio de búsqueda a todas las contraseñas de **4 dígitos** (`0000` a `9999`).
- Se ha definido una función de reducción personalizada que transforma hashes MD5 en contraseñas numéricas.
- Se ha construido una Rainbow Table que almacena los *endpoints* de cada cadena generada.
- Se ha simulado un ataque sobre hashes objetivo, midiendo la efectividad y analizando colisiones y falsos positivos.

## 📁 Estructura del repositorio

📦 rainbow-md5-attack  
┣ 📜 README.md ← Este archivo  
┣ 📜 Tarea_RainbowTable.ipynb ← Notebook principal con todo el código y análisis  


