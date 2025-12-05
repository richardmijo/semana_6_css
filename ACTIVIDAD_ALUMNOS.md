# 🎓 Taller Práctico: "Master of Puppets" (Dominando CSS)

## 🎯 Objetivo
El objetivo no es solo que el código "funcione", sino que **entiendas** cómo el navegador está animando los elementos.
Vas a descargar este proyecto y realizar **UNO** de los siguientes desafíos en tu propia rama (branch).

## 🛠️ Flujo de Trabajo (Git)
1.  **Clonar** el repositorio.
2.  Crear tu rama: `git checkout -b desafio-tu-nombre` (Ej: `desafio-juan-perez`).
3.  Elegir un desafío de abajo y programarlo.
4.  **IMPORTANTE**: Debes agregar comentarios en el código explicando *qué hace* cada línea clave.
5.  Subir cambios: `git push origin desafio-tu-nombre`.

---

## 🚀 Desafíos (Escoge Uno)

### Nivel 1: El Camaleón (Pseudo-clases & Variables)
**Misión**: Personalizar la identidad del sitio y crear un elemento reactivo.
1.  Ve a `styles.css` y cambia la paleta de colores (Variables `:root`) por tus colores favoritos.
2.  Crea un nuevo botón en el HTML bajo la sección "Pseudo-clases".
3.  Estílalo para que:
    *   **:hover**: Cambie de color de fondo y el texto crezca.
    *   **:active**: Se "hunda" (transform visual) y cambie el borde.

> **Requisito de comprensión**: Comenta por qué usaste `transition` en el estado base y no en el hover.

---

### Nivel 2: El Semáforo (Keyframes)
**Misión**: Crear una animación automática cíclica.
1.  Crea un `div` con forma de círculo en la sección "Keyframes".
2.  Crea una animación `@keyframes semaforo` que:
    *   0% - 33%: Sea Rojo.
    *   33% - 66%: Sea Amarillo.
    *   66% - 100%: Sea Verde.
3.  Asígnasela al círculo para que se repita infinitamente.

> **Requisito de comprensión**: Juega con los porcentajes. ¿Qué pasa si quitas el paso intermedio? Explícalo en un comentario.

---

### Nivel 3: El Cargador "Netflix" (Loader Complejo)
**Misión**: Crear un loader icónico o creativo.
1.  Olvídate del loader circular que ya existe.
2.  Crea tu propio "Spinner" o "Barra de carga".
3.  Debe usar al menos 2 propiedades animadas simultáneamente (Ej: `width` y `opacity`, o `rotate` y `scale`).
4.  Usa una curva de velocidad que NO sea `linear` (prueba `ease-in-out` o `cubic-bezier`).

> **Requisito de comprensión**: Explica en un comentario cómo afecta el `animation-timing-function` a la "personalidad" de tu loader.

---

### Nivel 4: La Carta 3D (Perspectiva & Transform)
**Misión**: Crear una tarjeta que revele información al girar.
1.  Crea una estructura HTML de una "Carta" con cara frontal y trasera.
2.  Usa CSS `perspective` en el contenedor padre.
3.  Usa `transform: rotateY(180deg)` en el hover para voltearla.
4.  Juega con `backface-visibility` para ocultar la cara trasera.

> **Requisito de comprensión**: ¿Para qué sirve `perspective`? ¿Qué pasa si le pones `perspective: 10px` vs `perspective: 1000px`? (Pruébalo y coméntalo).
