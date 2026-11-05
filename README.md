# Práctica 19 - El Panel del Gimnasio: El Tablero en Angular

## Respuestas del Ejercicio 1[cite: 2]

main.tsx → src/main.ts: Es el archivo de entrada donde se arranca la aplicación mediante bootstrapApplication, inicializando el componente raíz.

App.tsx → src/app/app.ts: Es el componente principal que actúa como contenedor base de la interfaz de usuario.

vite.config.ts → angular.json: Es el archivo de configuración global del proyecto y de la CLI (controla la compilación, estilos globales, assets y parámetros de build).

## Respuestas del Ejercicio 2[cite: 2]

* **¿Por qué `clase()` lleva paréntesis?**
Porque en las versiones recientes de Angular, input() crea una Signal (Input Signal). Para leer o resolver el valor que almacena —tanto en la clase TypeScript como en la plantilla HTML— es necesario invocar la función mediante los paréntesis ().
* **¿Para qué sirve `track`?**
Asigna un identificador único a cada elemento dentro del bucle @for (cumpliendo la misma función que la propiedad key en React). Esto permite que Angular reconozca exactamente qué ítems cambian, se insertan o se eliminan, re-renderizando únicamente las partes indispensables del DOM para maximizar el rendimiento.
