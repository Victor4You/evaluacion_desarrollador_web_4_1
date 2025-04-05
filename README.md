# evaluacion_desarrollador_web_4_1
aquí esta el segundo ejercicio

# Evaluación Desarrollador Web 4.1 - Ejercicio 2

Este proyecto corresponde al **Ejercicio 2** de la evaluación para desarrollador web. Consiste en una página HTML que consume un servicio REST desarrollado en el Ejercicio 1 y muestra la información en una tabla dinámica.

---

## Requisitos

- [XAMPP](https://www.apachefriends.org/) o cualquier servidor local compatible con PHP
- Navegador web moderno
- Proyecto del **Ejercicio 1** ejecutándose en `localhost`

---

##  Instrucciones de uso

1. Clona o descarga este repositorio en tu servidor local (ejemplo: `htdocs/evaluacion_desarrollador_web_4_1/`).
2. Asegúrate de que el proyecto del **Ejercicio 1** esté disponible en:

http://localhost/evaluacion_desarrollador_servicio_4_1/

markdown
Copiar
Editar

3. Abre en tu navegador:

http://localhost/evaluacion_desarrollador_web_4_1/index.html

yaml
Copiar
Editar

4. Verás una tabla y un botón que dice **"Consumir Servicio PHP"**.
5. Haz clic en el botón y los datos del servicio se cargarán dinámicamente.

---

##  ¿Qué hace este proyecto?

- Obtiene la **IP pública y región** del usuario utilizando `https://ipapi.co/json`.
- Al hacer clic en el botón, consume un **servicio PHP REST** (`fetch`) que retorna un listado de objetos en formato JSON.
- Los datos se insertan automáticamente en la tabla HTML como filas.
- Toda la lógica está contenida dentro del script JS en la misma página.

---

##  Estructura de archivos

index.html # Página principal con la interfaz y el script JS

yaml
Copiar
Editar

---

##  Autor

- Evaluación técnica realizada por: **Victor4You**
- Año: 2025

---

##  Notas

- La estructura visual no fue modificada del diseño original.
- El consumo del servicio se realiza en la función `CallApiRest()` dentro de la etiqueta `<script>`.
