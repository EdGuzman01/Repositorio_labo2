# Guía de Laboratorio II – Programación Web  
**Tema:** Implementación de Diseño web CSS (Flex, Grid)  
**Ciclo:** 02-2025  
**Materia:** Programación Web – UCA  

---

## 📌 Preguntas y Respuestas

### 1. ¿Qué significa CSS?  
CSS significa **Cascading Style Sheets** o **Hojas de Estilo en Cascada**.  
Permite aplicar estilos (colores, formas, márgenes, posiciones, tipografía, etc.) a uno o varios documentos HTML de manera automática y masiva.

---

### 2. ¿Cuál es la relación entre HTML y CSS?  
- **HTML** se encarga de la **estructura y contenido** del sitio web.  
- **CSS** se encarga de la **presentación y el diseño visual**.  
HTML proporciona el esqueleto, mientras que CSS define cómo se verá ese contenido en el navegador.

---

### 3. ¿Cuáles son las formas de enlazar CSS a un documento HTML?  
1. **Archivo CSS externo:** Usando `<link rel="stylesheet" href="estilos.css">` dentro de `<head>`.  
2. **Bloque de estilos:** Dentro del propio HTML, en la etiqueta `<style>...</style>`.  
3. **Estilos en línea:** Usando el atributo `style="..."` directamente en una etiqueta HTML.

---

### 4. ¿Qué elementos componen la sintaxis de CSS?  
- **Selector:** Elemento al que se aplicará el estilo.  
- **Propiedad:** Característica a definir (ej. color, tamaño, margen).  
- **Valor:** El valor de esa propiedad (ej. `red`, `20px`).  
- **Regla:** Conjunto de propiedad + valor.  
- **Comentario:** Texto entre `/* ... */` que no interpreta el navegador.

---

### 5. ¿Qué es Flexbox?  
Es un modelo de diseño en CSS que permite organizar elementos dentro de un **contenedor flexible**, distribuyendo espacio de manera eficiente y alineando elementos horizontal o verticalmente.  
- El **contenedor padre** define la disposición (`display: flex`).  
- Los **elementos hijos** se adaptan según las reglas definidas (ejemplo: `justify-content`, `align-items`).

---

### 6. ¿Qué es Grid en CSS?  
Es un sistema de diseño bidimensional que permite organizar elementos en **filas y columnas**.  
A diferencia de Flexbox (que trabaja mejor en una sola dimensión), Grid facilita diseños más complejos.  
Ejemplo básico:  

```css
.container {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 10px;
}
