# Clue Misterio: Asesinato en la Mansión Blackwood

Este es un simulador interactivo del juego de mesa "Clue", desarrollado como un proyecto web. El juego reta al jugador a resolver un asesinato identificando al culpable, el arma y la locación del crimen.

El proyecto está contenido en una sola página web HTML/CSS/JS, y se complementa con documentos de soporte que detallan su funcionamiento y lógica.

## Cómo Jugar / Ejecutar

No se requiere instalación ni un servidor web.

1. Clona o descarga este repositorio.
2. Abre el archivo `clue-mansion_blackwood.html` en tu navegador web preferido (Google Chrome, Firefox, Safari, etc.).
3. ¡Y a jugar!

## Características

* **Juego Completo de Deducción:** Basado en las reglas clásicas de "Clue".
* **5 Soluciones Secretas:** 5 posibles historias (culpable, arma, locación) seleccionadas aleatoriamente en cada partida.
* **Sistema de Pistas Interactivo:** Investiga a cada sospechoso, arma o locación para obtener un informe.
* **Lógica de Coartadas:** Los informes son consistentes si el ítem es inocente, pero son contradictorios o falsos si investigas un ítem involucrado en el crimen.
* **Diseño Moderno:** Interfaz gráfica responsiva con temática de misterio.
* **Cero Dependencias:** Funciona de manera autónoma en cualquier navegador moderno.

## Estructura del Proyecto

Este repositorio contiene los siguientes archivos:

* `README.md`
  * (Este archivo) La descripción general del proyecto para GitHub.
* `clue-mansion_blackwood.html`
  * **El Juego Principal.** Este único archivo contiene todo el HTML para la estructura, el CSS para el diseño y el JavaScript (JS) para la lógica completa del juego.
* `diagrama_de_flujo.html`
  * Un diagrama de flujo visual e interactivo (creado con Mermaid.js) que describe el flujo lógico completo del programa, desde el inicio hasta la acusación final.

## Tecnologías Utilizadas

* **HTML5**
* **CSS3** (Flexbox, Grid, Animaciones)
* **JavaScript (ES6+)** (Toda la lógica del juego y manipulación del DOM)
* **Mermaid.js** (Usado en `diagrama_visual.html` para renderizar el diagrama de flujo)

