# Desafío - Calculando el total 🧮

Este proyecto fue desarrollado como parte del módulo de introducción a JavaScript del programa Desafío Latam. 
El objetivo es practicar la manipulación del DOM y eventos de usuario para implementar una tarjeta de producto con cantidad dinámica y cálculo automático del total a pagar.

## 📋 Descripción
La tarjeta muestra un producto con:
- Una imagen.
- Título y precio base del producto.
- Botones para aumentar o disminuir la cantidad.
- Cálculo del total a pagar en tiempo real.

Todo esto se logra con JavaScript, sin necesidad de recargar la página.

## 🧠 Habilidades evaluadas según rúbrica

1. **Agregar evento que reacciona al clic en elementos HTML:**
   - Uso de `onclick` en botones para llamar funciones `sumar()` y `restar()`.

2. **Uso correcto de `querySelector()` e `innerHTML`:**
   - Se accede al DOM para obtener referencias a los elementos `#cantidad` y `#total` y se actualizan dinámicamente.

3. **Lógica para modificar total a pagar en función de la cantidad:**
   - La función `actualizarTotal()` realiza el cálculo dinámico y actualiza el contenido.

4. **Hacer funcionar los botones + y - para modificar la cantidad:**
   - Los botones `<button onclick="sumar()">` y `<button onclick="restar()">` incrementan o disminuyen la cantidad mostrando el total actualizado, impidiendo que baje de 1 unidad.

     
## 📁 Estructura del proyecto

```
introjava/
├── index.html                 # Estructura principal del sitio
├── assets/
│   ├── css/
│   │   └── styles.css         # Estilos personalizados para la tarjeta
│   └── img/
│       └── rtrx5090.webp      # Imagen del producto (ejemplo: laptop gamer)
```

## 💻 Cómo ejecutarlo

1. Clona o descarga el repositorio.
2. Abre `index.html` en tu navegador.
3. Interactúa con los botones `+` y `-` para ver el cálculo del total.

## ✨ Autor
**Williams Arias**  
[GitHub](https://github.com/wiimri)

---
> Proyecto realizado como parte del programa de estudios en **Desafío Latam**.
