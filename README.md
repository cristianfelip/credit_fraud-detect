# Detección de Fraude en Tarjetas de Crédito (AML)

Este proyecto es una herramienta de Inteligencia Artificial diseñada para detectar automáticamente transacciones bancarias sospechosas o posibles fraudes.

## ¿Qué problema resuelve?
el fraude con tarjetas es muy difícil de detectar porque el 99% de las transacciones son normales y legítimas. Además, los estafadores siempre cambian de estrategia.

## ¿Cómo funciona?
Utiliza un algoritmo llamado **Isolation Forest** (Bosque de Aislamiento). Su lógica es simple:
1. **Aprende lo normal:** El modelo analiza los datos para entender el comportamiento habitual del usuario (montos comunes, horarios y lugares frecuentes).
2. **Aísla lo extraño:** Las transacciones sospechosas (como un gasto gigante a mitad de la noche) son raras y diferentes. El algoritmo las detecta rápidamente porque "resaltan" del resto.
3. **Alerta:** El sistema le da una puntuación alta a lo que parece un fraude, permitiendo bloquear la tarjeta o revisar la operación a tiempo.

## Tecnología utilizada
* **Python 3.10+:** Para procesar y analizar la información.
* **Isotree:** Una librería de alta velocidad que permite procesar miles de transacciones por segundo con muy poco consumo de memoria.
* **GIF:** Una librería de alta velocidad que permite procesar miles de transacciones por segundo con medio consumo de memoria.
* **Lof:** Una librería de alta velocidad que permite procesar miles de transacciones por segundo con medio consumo de memoria.

