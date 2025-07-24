# 🌌 Proyecto Experimental: Efecto Parallax en CSS

Este repositorio contiene una **prueba técnica del efecto Parallax puro usando HTML y CSS**, sin JavaScript.

> ⚠️ **No es un proyecto profesional ni estético.**  
> Su objetivo no es verse "bien", sino **explorar cómo funciona el parallax nativo en CSS3** con capas, profundidades y desplazamientos visuales.

---

## 🎯 Objetivo

Investigar y experimentar con:

- `perspective` y `transform-style: preserve-3d`
- `translateZ()` y `scale()` para generar capas en diferentes profundidades
- el comportamiento de secciones al hacer scroll
- combinación de texto y fondos con movimiento diferenciado

---

## 🧪 ¿Qué incluye?

- Capas de contenido que se desplazan a distintas velocidades
- Uso de pseudo-elementos (`::after`) para generar fondos de manera independiente
- Textos flotantes que parecen moverse más rápido que el fondo
- Imágenes digitales estilo circuito/futurista para realzar la ilusión de profundidad

---

## 📂 Estructura del proyecto
parallax-experimento/
├── index.html
├── style.css
└── img/
  ├── fondo-1.jpg
  ├── fondo-2.jpg
  ├── fondo-3.jpg

---

## 🧠 Conceptos explorados

- `perspective` aplicada al contenedor `main`
- `translateZ(-1px)` en el fondo para que se mueva más lento
- `translateZ(+0.5px)` en el texto para que se acerque visualmente
- uso de `scale()` para corregir el tamaño percibido de cada capa

---

## 🚫 Advertencia

Este proyecto **no sigue buenas prácticas de accesibilidad ni diseño responsive avanzado**.  
Tampoco tiene estructura de aplicación web o integración real con ningún framework.

Fue creado **exclusivamente para entender cómo se puede lograr el efecto Parallax en CSS puro** sin bibliotecas externas.

---
