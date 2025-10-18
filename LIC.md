# proteger evidencia. Todo abajo — claro, honesto 

---

# A — Investigación rápida (salarios / contexto para negociar)

Resumen ejecutivo:

* El salario de programadores en México varía mucho por nivel y empresa. Fuentes de mercado muestran rangos desde sueldos bajos para junior hasta varios miles de dólares para perfiles senior. ([HireTech][1])
* En empresas retail grandes (OXXO) las referencias públicas de portales como Indeed/Glassdoor reportan cifras que suelen ser **más bajas que la media tech** para roles de desarrollo (ej.: reportes muestran rangos mensuales que pueden estar en el orden de ~11k–31k MXN según posición y reporte). ([Indeed México][2])
* Para Tiendas 3B los datos públicos (Indeed/Glassdoor) muestran sueldos muy variables por cargo; los roles técnicos/innovat. en retail en general suelen pagar menos que una empresa tech pura, pero hay excepciones según la experiencia y localización. ([Indeed México][3])

Qué significa para ti al negociar (práctico):

* **No esperes que una tienda de conveniencia pague lo mismo que una empresa tech**; aún así puedes pedir tarifas por licencia o implementación (no salario) — eso es distinto: negocias un **precio por producto / por tienda / por licencia**.
* Como referencia para tarifas por hora: si un desarrollador gana entre ~12k–25k MXN/mes en promedio, eso implica un rango aproximado por hora (160 h/mes) de ~75–156 MXN/h (solo referencia, hay mucha variación). Usa esto para calcular tarifas de consultoría o soporte. ([HireTech][1])

Fuentes clave (para que las cites si necesitas):

* Panorama general salarios programadores en México (datos agregados). ([HireTech][1])
* Reportes específicos OXXO / Tiendas 3B (Indeed / Glassdoor): muestran estimados por empresa. ([Indeed México][2])

---

# B — Cronología de 15 semanas (Markdown listo para pegar)

**Importante:** abajo tienes *dos tablas*:

1. **Cronología sugerida (completa, 15 semanas con horas sugeridas que suman ~500 h)** — útil si vas a presentar un plan completo.
2. **Cronología real / comprobable (ejemplo honesto)** — donde marcas lo que realmente hiciste y adjuntas evidencia (commits, capturas, fechas). **Usa la que sea honesta**: no recomiendo inflar horas. He dejado una columna “Horas reales (rellenar por Óscar)” para que pongas lo verdadero.

Copia y pega el bloque que prefieras en `CRONOLOGIA.md` o en tu README.

```markdown
# Cronología del Proyecto — Sistema de Caducidades
Autor: Óscar Cruz Díaz (RFC: CUDO000714Q61)
Periodo: [Fecha inicio] — [Fecha fin]
Nota: completa la columna “Horas reales” con el tiempo real trabajado y adjunta evidencia (commits, capturas, timestamps).

## Opción A — Plan completo (15 semanas, ~500 horas) — ejemplo de desglose
| Semana | Fechas (ej.) | Actividades principales | Horas sugeridas | Horas reales |
|---|---:|---|---:|---:|
| 1 | (plan) | Planificación, alcance, estructura del repo, arquitectura (HTML primero) | 34 | ____ |
| 2 | (plan) | Maquetado base en HTML (estructura de vistas y plantillas) | 34 | ____ |
| 3 | (plan) | Lógica JS básica: modelos de producto, manejo de fechas | 34 | ____ |
| 4 | (plan) | Base de datos local (JSON) y CRUD en JS; import/export de inventario | 34 | ____ |
| 5 | (plan) | Organización por categorías; filtros y búsquedas | 34 | ____ |
| 6 | (plan) | Implementación sistema de caducidades: detección y alertas | 34 | ____ |
| 7 | (plan) | Integración visual (CSS: diseño, responsive) | 34 | ____ |
| 8 | (plan) | Panel administrativo: alta/edición/roles (frontend) | 34 | ____ |
| 9 | (plan) | Validaciones, pruebas unitarias básicas, manejo de errores | 34 | ____ |
| 10 | (plan) | Auditoría de seguridad mínima, protección de secrets, sanitización | 34 | ____ |
| 11 | (plan) | Documentación técnica, README, CONTRATO y LICENSE añadidos | 34 | ____ |
| 12 | (plan) | Pruebas de usuario / demo (capturas, videos), correcciones | 34 | ____ |
| 13 | (plan) | Preparar release: tags firmados, generación ZIP legal | 34 | ____ |
| 14 | (plan) | Preparar paquete para INDAUTOR / evidencia legal | 34 | ____ |
| 15 | (plan) | Buffer: soporte, puesta a punto, preparación de entrega/contrato | 30 | ____ |
**TOTAL horas sugeridas:** 500 h

---

## Opción B — Cronología honesta / comprobable (rellena con lo real)
Usa esta tabla si quieres presentar **solo las horas reales que trabajaste** (recomendado si quieres ser sincero).

| Semana / Fecha | Actividades reales (ejemplos) | Horas reales | Evidencia (commits, capturas, notas) |
|---|---:|---:|---|
| 2025-10-10 / 2025-10-11 | Demostración en facultad; explicación del sistema de caducidades; revisión con Emilio (presentación en vivo) | 4–6 | Captura / nota: demo en Facultad (guardar foto o mensaje) |
| Semana X (inventario) | Implementación del inventario inicial (localStorage / JSON), ajustes, pruebas | 48 (total en 3 semanas) | commits: `feat: inventario inicial` (guardar `git log`) |
| (fecha) | Desarrollo módulo caducidades (detectar y mostrar alertas) | 6–12 | commits: `feat: caducidades` |
| (fecha) | Maquetado básico HTML / estructura | 8–16 | commits: `chore: estructura HTML` |
| (fecha) | CSS y diseño final (si aplicó) | 6–20 | capturas/commits |
| (fecha) | Documentación (README, LICENSE, SECURITY, CONTRATO) | 4–8 | archivos agregados y commits |
| ... | ... | ... | ... |

**Total (suma tus horas reales)**: ____ h  
(Guarda evidencia: `git log`, capturas, notas con fecha; si tienes archivos zip con timestamps, también sirven.)
```

> Cómo usar esto en la uni / estadías: **pon la Opción B** si quieres ser honesto — incluye enlaces a commits, capturas de pantalla con fecha, videos de demo (si tienes) y el ZIP con `LICENSE` (todos los derechos reservados). Si la universidad exige 500 h, explícales claramente qué actividades cubrieron la práctica (diseño, documentación, pruebas, investigación, soporte, mejoras, formación, etc.). No recomiendo inventar horas.

---

# C — Cláusulas prácticas para tu contrato/licencia (para cobrar)

Pega esto en tu `CONTRATO_LICENCIA_COMERCIAL.md` o en un anexo:

```markdown
### Cláusula de pago y licencia
1. El Licenciante (Óscar Cruz Díaz) concede al Licenciatario una licencia limitada, revocable, y por escrito, para usar el "Sistema de Caducidades" únicamente tras:
   a) Firma del presente contrato; y
   b) Pago íntegro de la contraprestación acordada.

2. Tarifas y formas de pago:
   - Opción A (Licencia por tienda / punto de venta): MXN [________] por establecimiento (licencia perpetua o por X años).
   - Opción B (Implementación + adaptación): MXN [________] tarifa única + MXN [________]/mes por soporte.
   - Opción C (Pago por hora - consultoría): MXN [________]/hora.

3. Entrega:
   - El autor entregará únicamente el paquete con la versión acordada y la documentación tras la confirmación de pago.

4. Prohibiciones:
   - El Licenciatario no podrá sublicenciar, distribuir, copiar, ni modificar el software sin autorización escrita.
   - Cualquier uso no autorizado será considerado infracción y generará responsabilidades civiles y/o penales.

5. Penalizaciones:
   - Uso no autorizado: penalización equivalente a [X] veces la tarifa de licencia, sin perjuicio de acciones legales adicionales.

6. Jurisdicción:
   - Leyes aplicables: Estados Unidos Mexicanos. Competencia de tribunales de [estado/ciudad].
```

Sugerencia práctica para números (orientativo): calcula tu **precio mínimo** con base en el tiempo que dedicarías (horas estimadas × tarifa por hora). Como referencia, tarifa por hora freelance en México puede ir desde ~150 MXN/h (junior) hasta 400+ MXN/h (senior/consultor). Ajusta según la urgencia, cliente y alcance. Usa tu contrato para dejar claro que **sin firma y pago no hay entrega**.

---

# D — Pasos inmediatos para evidenciar y defender tu trabajo

1. **Sube al repo todo lo que tengas** (LICENSE, README, SECURITY, CONTRATO, CRONOLOGIA.md).
2. **Haz un release** (v1.0) y sube el ZIP (ya lo tienes). Guarda ese ZIP en tu celular.
3. **Haz capturas y videos cortos** (pantalla) mostrando tu código y ejecutándolo, con fecha.
4. **Exporta `git log --pretty=oneline --date=iso`** y guarda como `commit_history.txt`.
5. Si alguien usa tu trabajo sin permiso: primero envía **correo formal** exigiendo cesión/retirada/saldo; si no atienden, contacta a INDAUTOR y consulta con un abogado (puedo ayudarte a preparar ese correo).
6. NO compartas secrets ni credenciales (y si las usaste, cámbialas).

---

## Recursos y acciones que puedo hacer ahora (elige lo que quieres que haga ya)

* ✅ Generar `CRONOLOGIA.md` completo (ya tengo la plantilla; puedo añadir las fechas 10–11 oct y tu inventario de 48h donde quieras).
* ✅ Insertar la cláusula de pago directamente en `CONTRATO_LICENCIA_COMERCIAL.md` con placeholders de montos (yo lo dejo listo y tú pones las cifras).
* ✅ Crear el `README` de perfil (yo lo redacto y lo subes a repo con el nombre de perfil).
* ✅ Preparar el PDF del contrato con tus datos listo para firmar.

Dime (solo si quieres):

1. ¿Quieres que agregue ya la **cronología con las fechas 10–11 oct** y marque las horas que me dijiste (48h inventario + X horas caducidades) en el `CRONOLOGIA.md` y lo ponga en el ZIP? — Si sí, lo añado ahora.
2. ¿Quieres que genere el **PDF del contrato** con tu nombre y RFC (sin cantidades) listo para que tú metas el precio después?

Si te sientes muy mal ahora, está bien tomarte un descanso — hazme saber lo que quieras que haga y yo lo preparo en seguida. Estoy contigo en esto, paso a paso. 💪✨

[1]: https://talently.tech/herramientas/mexico/salario?utm_source=chatgpt.com "Salario de un programador en Mexico - Talently"
[2]: https://mx.indeed.com/cmp/Oxxo-8d171c32/salaries/Desarrollador-a-de-software?utm_source=chatgpt.com "Cuanto paga OXXO en Desarrollador/a de software?"
[3]: https://mx.indeed.com/cmp/Tiendas-3b/salaries?utm_source=chatgpt.com "Sueldos de Tiendas 3B en México: ¿Cuánto paga ..."
