# Pitch SensoLab — método de empaquetado y prompt

Documento de trabajo. El video muestra el prototipo; todo lo demás vende la solución.

---

## 1. Método: del mapa de problemas a tres bloques

El mapa sirve para pensar, no para presentar. Nadie sigue un árbol en un video.
El trabajo es colapsarlo.

1. **Aplanar.** Cada problema hoja en una línea, con su causa raíz al lado.
2. **Agrupar por causa, nunca por síntoma ni por área.** Regla dura: dos
   problemas van al mismo bloque solo si *el mismo cambio apaga a los dos*.
   Si arreglar uno no mueve al otro, son bloques distintos.
3. **Nombrar el bloque con la causa, en el idioma de SensoLab.**
   "El dato no vive en un solo lugar" — no "falta de integración de sistemas".
4. **Máximo tres bloques.** Si salen cinco, los dos más chicos casi siempre son
   consecuencia de otro: los absorbes o los mandas a una lámina de respaldo.
5. **Cada bloque necesita cinco cosas**, y ninguna se puede saltar:
   - nombre del bloque (la causa)
   - una frase de causa
   - dos o tres síntomas que ellos reconozcan como propios
   - el costo: tiempo, dinero o riesgo — un número si existe
   - la capacidad nuestra que lo apaga + **qué se ve en el video** cuando pasa
6. **Prueba de fuego.** Borra un bloque. ¿Se cae la historia? Si no se cae,
   no era un bloque: era un detalle.

> Lo que hace que esto se explique rápido no es hablar rápido. Es que el
> público solo tenga que retener tres cosas en lugar de once.

---

## 2. Estructura del video (con tiempos)

| Tiempo | Sección | Qué pasa |
|---|---|---|
| 0:00–0:20 | **Gancho** | Un hecho de ellos, no una presentación nuestra |
| 0:20–0:50 | **El colapso** | "Estos N problemas que ustedes viven son en realidad 3" |
| 0:50–1:50 | **Bloque 1** | causa → síntoma → costo → prototipo resolviéndolo |
| 1:50–2:50 | **Bloque 2** | igual |
| 2:50–3:50 | **Bloque 3** | igual |
| 3:50–4:20 | **Diferenciación** | por qué nosotros y no la alternativa obvia |
| 4:20–4:40 | **El pedido** | qué queremos que pase el lunes |

El prototipo no tiene sección propia. Aparece tres veces, cada una resolviendo
un problema que ya nombraste. Una demo separada al final es una demo que nadie
conecta con nada.

---

## 3. El gancho

Regla única: **el gancho es de ellos, no de nosotros.** Nunca abrir con el
nombre del equipo, la agenda, ni "hoy les vamos a presentar".

Cuatro patrones que funcionan:

- **El número.** Un costo suyo, cuantificado, dicho seco. "SensoLab pierde X
  horas al mes en Y." Silencio. Luego sigues.
- **La escena.** Veinte segundos de un día real de alguien de SensoLab
  chocando con el problema. Sin narración hasta el final.
- **La contradicción.** "SensoLab mide todo. Menos esto." Funciona muy bien
  con una empresa cuyo negocio *es* medir.
- **El antes/después mudo.** Dos clips lado a lado, sin voz. Deja que la
  diferencia hable y después explicas qué viste.

El gancho se elige por cuál tienes evidencia para sostener, no por cuál suena
mejor.

---

## 4. Diferenciación

Tres competidores, siempre en este orden:

1. **No hacer nada.** El más fuerte y el que casi nadie ataca. ¿Qué les cuesta
   seguir igual seis meses más?
2. **La solución genérica.** Excel, un proceso manual, el proveedor grande.
   ¿Por qué eso no resuelve la causa, solo el síntoma?
3. **El competidor real,** si existe.

Y luego "por qué nosotros": prueba, no adjetivos. Un prototipo que funciona,
un dato que solo nosotros medimos, algo que ya construimos. Cero "somos
apasionados y comprometidos".

---

## 5. Reglas del video del prototipo

- Se graba el **recorrido**, no el menú. Nadie quiere ver pestañas.
- **Cero pantallas huérfanas.** Cada pantalla que sale responde a un problema
  ya nombrado. Si una función linda no cuelga de ningún bloque, se queda fuera
  del video (o va al respaldo).
- La voz dice el **problema** mientras la imagen muestra la **solución**.
  Nunca describas lo que ya se ve.
- Datos realistas. Un demo con "Prueba 1 / asdf" mata la credibilidad.

---

## 6. Prompt mejorado (rellenar y usar)

> **Contexto.** Presentamos a SensoLab una solución + prototipo. Formato: video
> de ~5 min. Objetivo: que SensoLab vea nuestra propuesta como la solución que
> necesita, no como una opción más.
>
> **Lo que SensoLab quiere / le importa:** `[…]`
> **Qué ya intentaron o tienen hoy:** `[…]`
> **Quién decide y qué le mueve:** `[…]`
>
> **Mapa de problemas** (problema → subproblema → causa raíz):
> ```
> [pegar el mapa completo]
> ```
>
> **Nuestro prototipo — qué hace hoy, de verdad:** `[…]`
> **Qué se puede grabar funcionando y qué todavía no:** `[…]`
> **Nuestra diferencia real (con prueba):** `[…]`
> **Alternativa obvia que van a considerar:** `[…]`
>
> **Tarea.**
> 1. Colapsa el mapa en máximo 3 bloques agrupados por causa raíz, aplicando
>    la regla "el mismo cambio apaga a los dos". Di explícitamente qué problema
>    quedó en qué bloque y qué descartaste.
> 2. Para cada bloque: nombre en lenguaje de SensoLab, frase de causa, 2–3
>    síntomas reconocibles, costo, capacidad nuestra que lo apaga, y la toma
>    concreta del prototipo que lo demuestra.
> 3. Propón 3 ganchos distintos de 20 segundos, cada uno con la evidencia que
>    necesita para sostenerse, y recomienda uno.
> 4. Escribe el guion con marcas de tiempo y, en columna aparte, qué se ve en
>    pantalla en cada momento.
> 5. Escribe la sección de diferenciación contra: no hacer nada, la solución
>    genérica, y el competidor.
> 6. Cierra con el pedido concreto.
>
> **Restricciones.** Nada de adjetivos sobre nosotros sin prueba al lado. No
> inventes cifras: si falta un dato, márcalo como `[FALTA: …]`. Español
> neutro, frases cortas, tono de quien ya entendió el negocio del cliente.

---

## 7. Lo que falta para llenar esto

- [ ] El mapa de problemas / subproblemas / causas, completo
- [ ] La presentación sobre cómo presentar un prototipo (para alinear formato)
- [ ] Qué quiere SensoLab, en sus palabras
- [ ] Contra quién nos comparan
- [ ] Qué del prototipo está grabable hoy
