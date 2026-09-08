# ProyectoMitadSemestreVisionArtificial

## Documentación de Proyecto: "El Despertar de Cthulhu"
### Materia: Visión Artificial

#### Semana: 1 - Etapa de Diseño e Ideación

**1. Concepto Artístico e Interactivo**
El proyecto consiste en una instalación interactiva de arte generativo y sombras desarrollada en p5.js. La propuesta busca explorar la intersección entre el terror cósmico y la tecnología, utilizando la silueta del espectador como el catalizador principal de una presencia ancestral.

Cuando el usuario se coloca frente a la cámara, su cuerpo proyecta una silueta digital que despierta una entidad inspirada en Cthulhu. Los tentáculos y las alas de la criatura emergen orgánicamente y responden en tiempo real al movimiento de las extremidades del usuario, creando una simbiosis visual entre la persona y la entidad mitológica.

---

**2. Búsqueda de Referentes e Inspiración**
Para cimentar la propuesta conceptual y técnica de la experiencia, se analizan dos referentes fundamentales que exploran la relación entre la silueta humana, el control gestual y la manifestación de entidades digitales:

**A) "The Treachery of Sanctuary" (Chris Milk):** https://youtu.be/ehjklqL6g84?si=SGgCNYxpRhNbXBk6

Análisis: Esta reconocida instalación interactiva utiliza pantallas gigantes y procesamiento de siluetas en tiempo real donde los movimientos corporales de los espectadores provocan la transformación de su propio cuerpo en aves que emergen, aletean y se desintegran.

Aporte al proyecto: Sirve como inspiración directa para la interacción basada en sombras y la fluidez con la que los elementos gráficos (en nuestro caso, las alas y tentáculos de Cthulhu) brotan y responden dinámicamente al contorno y las extremidades del usuario, logrando una sincronía perfecta entre el cuerpo y el arte generativo.

**B) Película "Colossal" (Dir. Nacho Vigalondo, protagonizada por Anne Hathaway):** https://youtu.be/8GZi7H6fvBY?si=ITF9zvKTPh8Bd4V2

Análisis: En este largometraje, la protagonista descubre que sus movimientos físicos cotidianos realizados en un punto específico de la ciudad controlan, a escala masiva y en tiempo real, las acciones destructivas y de imitación de un monstruo gigante en el otro extremo del mundo.

Aporte al proyecto: Aporta la narrativa conceptual del vínculo de control simbiótico: el usuario no es un simple espectador, sino el motor que da vida y dirige la voluntad de una criatura colossal (Cthulhu). Cada gesto de los brazos y desplazamiento se traduce en una acción directa del ente en el espacio digital.

**C) Película "MEGAMENTE":** https://youtu.be/a_hsjTExzbw?si=zP-Z_clygNVQ0Df0 

<img width="415" height="739" alt="image" src="https://github.com/user-attachments/assets/efefeb9a-5ec0-45eb-80bf-6d464dd5abe1" />


Análisis:

Aporte al proyecto:

---

**3. Primeras Pruebas**

Se realizaron pruebas para construir a Cthulhu directamente dentro del canvas.

### Problema encontrado

Aunque el sistema permitía generar una criatura visualmente compleja, el resultado no conservaba suficientemente la apariencia reconocible de Cthulhu.

Esto era especialmente importante porque la identidad visual del personaje es uno de los elementos principales del proyecto.

### Decisión

Separar la representación del personaje de la simulación del movimiento.

En lugar de intentar generar todo Cthulhu proceduralmente, se plantea utilizar una imagen como base y generar/interpolar el movimiento de elementos específicos, principalmente las alas.

---

**4. Nueva estrategia visual**

### Imagen base

Utilizar una imagen de Cthulhu como referencia visual principal.

<img width="1280" height="1707" alt="cthulhu_face_portrait__by_maskedmidnight_dddjz51-fullview-Photoroom" src="https://github.com/user-attachments/assets/4a7a0ba0-d3c0-414d-9fed-8a03e74ba259" />

La imagen funciona como la representación reconocible del personaje.

### Movimiento

El sistema se encargará de generar el movimiento de las alas mediante deformación, transformación o animación independiente.

La intención es conseguir:

- Movimiento orgánico.
- Sensación de vida.
- Movimiento sincronizado con la interacción.
- Conservación de la apariencia original de Cthulhu.
- Mayor control sobre la animación.

---

## 05 · Interacción

La interacción será utilizada para modificar el comportamiento visual de Cthulhu.

### Posibles variables

- Intensidad de la interacción.
- Movimiento de las alas.
- Escala.
- Oscilación.
- Distorsión visual.

La interacción no busca únicamente controlar al personaje, sino generar una sensación de que el usuario está provocando una reacción en la criatura.

---

## 06 · Movimiento de las alas

### Objetivo

Conseguir que las alas tengan un movimiento independiente del resto del cuerpo.

El movimiento debe evitar verse como una simple rotación mecánica.

Se busca una animación:

- Orgánica.
- Pesada.
- Lenta.
- Irregular.
- Amenazante.

### Pruebas y avamces

https://youtu.be/XiYqHVxfu-8

https://youtu.be/l8KqMk6VnEQ

https://youtu.be/0UMGQHcQZ44



---

## 07 · Problemas y soluciones

| Problema | Solución |
|---|---|
| Cthulhu no era suficientemente reconocible | Utilizar una imagen como base |
| El movimiento procedural alteraba demasiado la figura | Separar personaje y animación |
| Las alas parecían rígidas | Aplicar movimiento independiente |
| La animación se sentía mecánica | Incorporar oscilaciones y variaciones orgánicas |
| La interacción no tenía suficiente impacto | Vincular la intensidad del movimiento a la interacción |

---

## 08 · Estado actual

### Logrado
- [x] Concepto visual definido.
- [x] Cthulhu establecido como figura central.
- [x] Identificado el problema de la generación procedural.
- [x] Definida una nueva estrategia utilizando una imagen base.
- [ ] Implementar alas animadas.
- [ ] Conectar las alas con la interacción.
- [ ] Ajustar movimiento.
- [ ] Diseñar atmósfera final.
- [ ] Integrar todos los elementos.

---

## 09 · Próximos pasos

1. Seleccionar/preparar la imagen definitiva de Cthulhu.
2. Separar visualmente las alas del cuerpo.
3. Implementar el movimiento de las alas.
4. Conectar el movimiento con el mouse/interacción.
5. Ajustar velocidad, amplitud y comportamiento.
6. Incorporar atmósfera y efectos visuales.
7. Realizar pruebas.
8. Documentar resultados.
