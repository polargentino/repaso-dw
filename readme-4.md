# Clase 5: Formularios en HTML

Los formularios en HTML permiten a los usuarios ingresar datos y enviarlos al servidor. A continuación, se explican los elementos más comunes utilizados en formularios.

---

## 1. Etiqueta `<form>`
La etiqueta `<form>` define un formulario HTML. Incluye los atributos:
- **`action`**: Especifica la URL donde se enviarán los datos.
- **`method`**: Define el método HTTP para enviar los datos (`GET` o `POST`).

Ejemplo:
```html
<form action="/submit" method="POST">
    <!-- Campos del formulario -->
</form>