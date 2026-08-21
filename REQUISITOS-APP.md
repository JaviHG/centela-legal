# Requisitos para nuestra app

Documento base para la tormenta de ideas. **Primero fijamos los filtros, luego proponemos ideas.**
El objetivo no es "hacer una app chula": es **hacer una app que gane dinero**. Todo lo que hay aquí
está pensado para descartar rápido y no perder tres meses construyendo algo que no compra nadie.

Regla de oro: **una idea que no se puede describir en una frase del tipo _"[quién] paga [cuánto] por
[qué resultado]"_ no entra en la votación.**

---

## Bloque A — Filtros eliminatorios

Si una idea falla **uno solo** de estos ocho puntos, se cae. Sin debate, sin "es que si además...".

| # | Requisito | Cómo se comprueba |
|---|---|---|
| **A1** | **Monetización explícita desde el día 1** | Se rellena la frase: "**[perfil concreto]** paga **[X €/mes o X € por uso]** por **[resultado medible]**". Nada de "luego monetizamos con publicidad". |
| **A2** | **Primer euro cobrado en ≤ 90 días** | Se puede cobrar antes de que la app esté "terminada". Si hay que construir 6 meses para poder facturar, fuera. |
| **A3** | **MVP en ≤ 6 semanas a tiempo parcial** | Presupuesto real: ~8-10 h/semana por persona. Se lista el alcance mínimo y tiene que caber. Si no cabe, se recorta la idea o se descarta. |
| **A4** | **Coste fijo < 20 €/mes hasta el primer cliente** | Hosting, dominio, base de datos y correo entran en ese presupuesto. Nada que exija servidores caros, licencias o inventario. |
| **A5** | **Margen por usuario ≥ 70 %** | Coste variable (tokens de IA, SMS, APIs de pago, almacenamiento, comisiones) < 30 % del precio. **Si la idea usa IA, hay que traer el cálculo de coste por usuario/mes hecho**, no a ojo. |
| **A6** | **Sabemos dónde están los primeros 100 usuarios** | Se nombran **3 sitios concretos** (subreddit, grupo de Facebook, foro gremial, colegio profesional, Discord, feria, lista de correo) donde podemos publicar gratis y nos van a leer. "Redes sociales" no es una respuesta. |
| **A7** | **El dolor está demostrado, no supuesto** | Mínimo **3 pruebas** externas: gente quejándose por escrito, un competidor de pago vivo, un Excel monstruoso haciendo el trabajo a mano, o un servicio que hoy se resuelve pagando a una persona. |
| **A8** | **Legalmente manejable** | Sin datos de salud, sin custodiar dinero de terceros, sin scraping contra los términos de uso de una plataforma, sin sector regulado (banca, seguros, sanidad, menores). RGPD abordable con lo que sabemos. Y facturable: alguien tiene que poder emitir la factura. |

## Bloque B — Suma puntos (no eliminan, pero deciden empates)

- **B1 — Recurrencia**: el usuario tiene motivo para volver al menos una vez por semana. Suscripción > pago único. Si es de un solo uso, el ticket tiene que ser alto (> 50 €).
- **B2 — B2B antes que B2C**: una empresa pequeña paga 30 €/mes sin pestañear; un particular regatea 3 €. Nicho profesional aburrido > app de consumo masivo.
- **B3 — Sin efecto red**: la app aporta valor al **primer** usuario, ella sola. Los marketplaces y las redes sociales necesitan miles de usuarios para valer algo: nosotros no llegamos ahí.
- **B4 — El dolor cuesta dinero, no tiempo**: "te ahorra 4 horas" se vende regular; "recuperas 800 € de facturas impagadas" se vende solo.
- **B5 — Ventaja nuestra**: alguien del grupo conoce el sector, tiene contactos ahí o ya ha sufrido el problema en primera persona. Vale más que cualquier idea brillante en abstracto.
- **B6 — Defendible a 6 meses**: hay algo (datos acumulados, integración pesada, relación con el cliente, contenido propio) que impide que la clonen en un fin de semana y nos coman.
- **B7 — Sin dependencia mortal**: si vive de una API ajena, hay **plan B escrito** para cuando esa empresa suba precios, cierre el acceso o cambie los términos.

## Bloque C — Descarte automático

Estas ideas ya están sobre la mesa antes de proponerlas, y las tiramos:

- Clon de algo que ya hace **gratis** un gigante (Google, Notion, Microsoft, WhatsApp) igual de bien.
- "Es como X pero con IA" sin nada más detrás.
- Marketplace, red social, app de citas o cualquier cosa que necesite las dos partes a la vez.
- Cripto, apuestas, trading, "ingresos pasivos".
- Todo lo que dependa de que **nos hagamos virales** para funcionar.
- Que necesite inversión, stock físico, logística o un comercial a sueldo.
- Que necesite permiso, licencia o certificación para operar.
- Modelo publicitario: hacen falta cientos de miles de visitas para ganar cuatro duros.
- Cosas donde el usuario tendría que meter datos manualmente durante horas antes de recibir nada.

## Bloque D — Rúbrica de puntuación

Solo puntúan las ideas que hayan pasado el **Bloque A** entero. Cada uno puntúa de 0 a 5:

| Criterio | Peso |
|---|---|
| Disposición a pagar (¿cuánto y cómo de rápido?) | ×3 |
| Facilidad de llegar a los primeros usuarios | ×3 |
| Rapidez del MVP | ×2 |
| Recurrencia / retención | ×2 |
| Ventaja nuestra en ese nicho | ×2 |
| Margen y coste variable | ×1 |
| Defendibilidad a 6 meses | ×1 |

**Máximo: 70 puntos. Umbral para pasar a validación: 45.** Pasan las 3 mejores.

## Bloque E — Plantilla para proponer una idea

Cada propuesta se manda **con esta plantilla rellenada**. Una idea sin plantilla no se puntúa.

```
IDEA:
EN UNA FRASE: [quién] paga [cuánto] por [qué resultado]
CLIENTE CONCRETO: (perfil, no "pymes": "gestorías de 2-5 personas en España")
DOLOR: qué hace hoy para resolverlo y qué le cuesta
PRUEBAS DEL DOLOR (3): enlaces, competidores de pago, capturas
PRECIO Y MODELO: €/mes, por uso, por proyecto
MVP (lo mínimo que se puede cobrar): 3-5 funciones, nada más
SEMANAS ESTIMADAS:
COSTE FIJO MENSUAL:  |  COSTE VARIABLE POR USUARIO:
DÓNDE ESTÁN LOS 100 PRIMEROS (3 sitios):
COMPETENCIA: quién lo hace ya y por qué nos elegirían a nosotros
BLOQUE A: A1 ☐ A2 ☐ A3 ☐ A4 ☐ A5 ☐ A6 ☐ A7 ☐ A8 ☐
RIESGO PRINCIPAL:
```

## Bloque F — Cómo lo hacemos

1. **Divergencia (hasta [FECHA])** — cada uno mete **mínimo 3 ideas** con la plantilla. Prohibido criticar ideas ajenas en esta fase: solo se aportan.
2. **Filtro duro** — pasamos el Bloque A a todo. Lo que cae, cae, y no se resucita.
3. **Puntuación** — cada uno puntúa **todas** las ideas supervivientes con la rúbrica. Se suma.
4. **Validación de las 3 finalistas (1 semana)** — landing con precio real + botón de "quiero esto", y **10 conversaciones** con clientes potenciales. No vale preguntar "¿te gustaría?": hay que preguntar "¿qué usas ahora y cuánto pagas?".
5. **Decisión** — gana la que consiga **señales reales** (correos, apuntados, alguien que diga "cuándo lo tenéis"). Si ninguna las consigue, volvemos al paso 1. Es un resultado válido y barato.

## Bloque G — Requisitos del equipo (esto también es un requisito)

Se acuerda **antes** de escribir la primera línea de código:

- **Horas/semana** que se compromete cada uno, por escrito. El que no puede, no pasa nada, pero que se sepa.
- **Reparto**: por trabajo aportado, no por "la idea fue mía". Con **periodo de prueba de 3 meses** antes de repartir nada en firme.
- **Quién decide** cuando no hay acuerdo (una persona con voto de calidad por área: producto, técnica, ventas).
- **Qué pasa si alguien se va**: se marcha con lo hecho hasta la fecha, el resto sigue.
- **Dónde entra el dinero** y quién factura.
- **Fecha de corte**: si a los **3 meses** no hay ningún euro cobrado, se revisa o se mata el proyecto. Sin drama.

---

## Versión corta para pegar en Discord

> **Reglas para las ideas de la app 💸**
>
> Antes de proponer nada, la idea tiene que pasar estos 8 filtros. Falla uno = fuera:
> **1.** Se rellena la frase "**[quién]** paga **[cuánto]** por **[qué resultado]**".
> **2.** Podemos cobrar el primer euro en **90 días**.
> **3.** MVP en **6 semanas** a 8-10 h/semana por cabeza.
> **4.** Coste fijo **< 20 €/mes** hasta el primer cliente.
> **5.** Margen **≥ 70 %** (si lleva IA, traed el coste por usuario calculado).
> **6.** Sabemos decir **3 sitios concretos** donde están los 100 primeros usuarios.
> **7.** **3 pruebas** de que el dolor existe (quejas, competidor de pago, Excel infernal).
> **8.** Nada regulado, nada de datos de salud, nada de custodiar dinero ajeno.
>
> **Descarte automático:** clones de algo gratis de Google/Notion, "X pero con IA", marketplaces y redes sociales, cripto/apuestas, cualquier cosa que necesite hacerse viral, publicidad como modelo de negocio.
>
> **Suma puntos:** que sea de pago recurrente, B2B, aburrido y de nicho, y que alguien de aquí conozca ese sector.
>
> **Plantilla obligatoria por idea** (sin esto no se puntúa):
> ```
> IDEA:
> EN UNA FRASE: [quién] paga [cuánto] por [qué]
> CLIENTE CONCRETO:
> DOLOR + 3 PRUEBAS:
> PRECIO Y MODELO:
> MVP (3-5 funciones):  |  SEMANAS:
> COSTE FIJO:  |  COSTE POR USUARIO:
> DÓNDE ESTÁN LOS 100 PRIMEROS (3 sitios):
> COMPETENCIA:
> RIESGO PRINCIPAL:
> ```
>
> **Plan:** cada uno mete **3 ideas mínimo antes del [FECHA]** → filtramos → puntuamos → las 3 mejores se validan con una landing y 10 conversaciones reales → elegimos 1.
> En la fase de proponer **no se critica a nadie**, solo se aporta. El filtro viene después. 🚀
