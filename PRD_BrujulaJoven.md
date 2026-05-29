# PRD — Brújula Joven Cartagena
### Tu brújula para participar, formarte y trabajar en Cartagena

> Plataforma con IA que centraliza la información juvenil dispersa de Cartagena y la convierte en **rutas personalizadas** de participación, formación, empleo e incidencia territorial.

**Versión:** 1.0 (Hackathon) · **Fecha:** 29 de mayo de 2026 · **Equipo:** [tu equipo]

---

## 1. Resumen ejecutivo (el pitch en 30 segundos)

Cartagena tiene **245.653 jóvenes** (24,3% de la población) pero **el 87% no participa en ningún espacio ciudadano**. El problema **no es la falta de oportunidades** —hay 33 organizaciones, 57 consejeros de juventud, escuelas de liderazgo y convocatorias activas— sino que **la información está dispersa, segmentada y desactualizada**: vive en grupos de WhatsApp, redes institucionales y formularios sueltos. El joven que ya está conectado se entera; el resto, nunca.

**Brújula Joven** resuelve exactamente eso. Es una plataforma que:
1. Hace un **test inicial inteligente** (estilo test vocacional) y genera un **perfil de cada joven** con IA.
2. **Centraliza** en un solo lugar todas las convocatorias, eventos, mesas, vacantes y rutas de formación.
3. Usa IA para **recomendar a cada joven exactamente lo que le sirve y queda cerca**, con alertas personalizadas.
4. Le da a la Alcaldía y a las organizaciones un **panel para publicar y medir el impacto real**.

Convertimos información invisible en **rutas de participación reales**.

---

## 2. El problema (respaldado en datos)

**Pregunta central de la problemática:**
> *¿Cómo organizar, centralizar y comunicar de manera clara, atractiva y accesible la información sobre oportunidades, convocatorias y mesas de participación juvenil, para que más jóvenes puedan conocerlas, vincularse e incidir en las decisiones de sus territorios?*

### 2.1 Las cifras que duelen (fuente: *Juventudes Cartagena reporte.xlsx*, Calidad de Vida 2024, DANE)

| Indicador | Dato | Implicación |
|---|---|---|
| Jóvenes 14–28 años | **245.653 (24,3%)** | 1 de cada 4 cartageneros |
| No participan en ningún espacio | **87%** | Exclusión informativa masiva |
| Participan en espacios de la Alcaldía/Gobernación | **solo 6%** | Los canales oficiales no llegan |
| Usan encuestas/chatbot web institucional | **solo 3%** | Canal digital subutilizado → oportunidad |
| **Querrían** participar en Acción Comunal/similares | **51%** | **El interés existe; falta el puente** |
| Ocupación juvenil 2023 → 2024 | **39,2% → 34,8%** | Cae, vs. 55,3% general |
| Organizaciones juveniles mapeadas | **33** (dispersas) | Oferta existe, sin articular |
| Participación comunitaria (volátil) | 74% (2019) → 30,1% (2022) → 45,1% (2024) | Pérdida de confianza y continuidad |
| Homicidios en juventud | 2 (2020) → 56 (2023) → 37 (2024) | La desconexión tiene costo social |

### 2.2 Las tres causas raíz (textual de la problemática)

1. **Información dispersa** — Redes, WhatsApp, formularios independientes y convocatorias temporales sin un lugar único.
2. **Desconexión institucional** — Alcaldía, Sec. de Participación, UTB, Fundación Mi Sangre, Escuela de Gobierno, Colectivo TRASO, Gobernación operan aislados, duplicando esfuerzos.
3. **Baja articulación** — 33 organizaciones sin interoperabilidad; el joven sin "cercanía organizacional" simplemente nunca recibe la información.

> **El desafío no es crear espacios desde cero, sino organizar, centralizar y comunicar los que ya existen.** ← Esto es exactamente lo que hace Brújula Joven.

---

## 3. Visión del producto

> "Que **cualquier** joven de Cartagena —del Centro o de la Localidad 3— pueda abrir una app, hacer un test de 3 minutos y recibir su **ruta personalizada**: dónde participar, qué formación tomar, qué vacante aplicar y a qué mesa de incidencia sumarse, todo **cerca de él y en lenguaje claro**."

No es un repositorio de PDFs. Es un **centro de conexión juvenil con IA** que personaliza y empuja la información hacia el joven, no al revés.

---

## 4. Usuarios y personas

| Persona | Descripción | Necesidad principal |
|---|---|---|
| **Valentina, 16, Localidad 3** | Estudiante, no sabe que existen escuelas de liderazgo cerca | Descubrir oportunidades sin saber qué buscar |
| **Andrés, 22, desempleado** | Busca trabajo/formación, está en grupos de WhatsApp saturados | Vacantes y cursos filtrados para él |
| **Daniela, 25, lideresa comunitaria** | Ya participa, organiza eventos | Difundir convocatorias y medir asistencia |
| **Secretaría de Participación** | Publica programas, no sabe a quién llegan | Centralizar, medir alcance e impacto real |
| **Organizaciones (33) / consejeros (57)** | Tienen oferta dispersa | Visibilidad y articulación |

---

## 5. La solución — Módulos del producto

### 🧭 Módulo 0 — Onboarding con IA: "Test de tu Brújula" *(diferenciador clave)*
Encuesta inicial estilo test vocacional (3–5 min, conversacional). Pregunta por **intereses** (deporte, cultura, política, ambiente, emprendimiento), **objetivos** (empleo, formación, voluntariado, incidencia), **disponibilidad**, **localidad/barrio** y **nivel de experiencia**.
→ La IA genera un **Perfil Joven** (ej. *"Líder Comunitario en formación, perfil cultural, Localidad 2"*) y desde ese momento **todo se personaliza**.

### 📍 Módulo 1 — Mapa y feed centralizado
Todas las oportunidades en un solo lugar, **geolocalizadas por localidad/barrio**: convocatorias, eventos, mesas de participación, espacios físicos de trabajo. Filtros por tipo, fecha, cercanía. Responde literalmente las 7 preguntas de la problemática (qué, dónde, cuándo, cómo vincularse, qué está abierto, qué impacto genera, dónde hay espacio físico).

### 🎯 Módulo 2 — Recomendador IA + Alertas personalizadas
La IA cruza el Perfil Joven con la base de oportunidades y entrega un **feed priorizado** + **alertas push/WhatsApp**: *"Valentina, abrió la inscripción a la Escuela de Liderazgo UTB, a 10 min de tu casa. Cierra el viernes."* Convierte oportunidades invisibles en rutas reales.

### 🎓 Módulo 3 — Rutas de formación y liderazgo
Itinerarios: talleres, escuelas de gobierno, mentorías (Fundación Mi Sangre, UTB, Escuela de Gobierno, Colectivo TRASO). Seguimiento de progreso y "ruta de incidencia" (cómo pasar de asistente a consejero de juventud).

### 💼 Módulo 4 — Empleo y emprendimiento
Vacantes y programas filtrados por perfil (ataca la caída de ocupación juvenil 39,2%→34,8%). Conecta con sectores reales (comercio/hotelería, servicios, manufactura).

### 🗳️ Módulo 5 — Incidencia y democracia
Mapa de mecanismos democráticos, Consejos de Juventud, JAL, presupuestos participativos. Cómo vincularse paso a paso. Visibiliza el impacto real de cada espacio.

### 📊 Módulo 6 — Panel institucional (lado oferta)
Alcaldía/organizaciones publican convocatorias (que se distribuyen automáticamente al perfil correcto) y ven **analítica de alcance e impacto**: cuántos jóvenes alcanzados, por localidad, conversión a participación. Elimina la duplicación de esfuerzos y la desarticulación.

### 🤖 Módulo 7 — Bot de WhatsApp (inclusión)
Porque la información hoy vive en WhatsApp y solo el 3% usa chatbots oficiales. Bot que hace el test, envía alertas e inscribe **sin necesidad de instalar app** → llega al joven sin "cercanía organizacional".

---

## 6. Flujo de usuario (happy path)

```
Joven entra (web/WhatsApp)
   → Test de la Brújula (3 min)
   → IA genera Perfil Joven
   → Feed personalizado + Mapa por localidad
   → Recibe alertas de convocatorias que le sirven y le quedan cerca
   → Se inscribe con 1 clic
   → La organización lo recibe y mide el impacto
   → El joven avanza en su "ruta de incidencia"
```

---

## 7. Alcance del MVP para la Hackathon (lo que se demuestra en vivo)

**Sí entra (demo funcional):**
- ✅ Test de onboarding conversacional + generación de Perfil Joven con IA (Claude API).
- ✅ Feed/mapa con datos sembrados reales de Cartagena (33 organizaciones, escuelas, localidades del Excel).
- ✅ Recomendador IA que ordena oportunidades según el perfil.
- ✅ Una alerta personalizada de ejemplo (WhatsApp o push simulado).
- ✅ Mini panel institucional para publicar una convocatoria.

**Fuera del MVP (roadmap):** login con cédula/SISBÉN, verificación institucional, app nativa, analítica avanzada.

> Regla de oro para ganar: **que el jurado haga el test en vivo y vea su propio feed personalizado.** Eso vende solo.

---

## 8. Arquitectura técnica (factible en hackathon)

| Capa | Tecnología sugerida | Por qué |
|---|---|---|
| Frontend | **Next.js / React + Tailwind** | Rápido, responsive, demo-friendly |
| Backend / DB | **Supabase (Postgres)** o Firebase | Auth + DB + realtime sin servidor propio |
| IA | **Claude API (claude-opus-4-8 / haiku para velocidad)** | Genera perfil, recomienda, redacta alertas en lenguaje claro |
| Geolocalización | Mapbox / Google Maps | Mapa por localidad/barrio |
| Mensajería | WhatsApp Cloud API / Twilio | Canal de mayor alcance real |
| Datos semilla | Excel *Juventudes Cartagena* | Realismo en la demo |

**Cómo se usa la IA (clave técnica):**
1. **Perfilado:** prompt estructurado → JSON con perfil, intereses ponderados, localidad.
2. **Matching/recomendación:** embeddings o scoring por afinidad perfil↔oportunidad.
3. **Comunicación:** la IA reescribe convocatorias densas en lenguaje claro y atractivo + redacta la alerta.

---

## 9. Modelo de datos (núcleo)

- **Joven**: id, edad, localidad, barrio, intereses[], objetivos[], perfil_IA, canal.
- **Oportunidad**: id, tipo (convocatoria/evento/empleo/formación/mesa), título, descripción, organización, localidad/geo, fechas, requisitos, estado, impacto.
- **Organización**: id, nombre, enfoque, localidad, contacto.
- **Match/Inscripción**: joven_id, oportunidad_id, score, estado, fecha.
- **Alerta**: joven_id, oportunidad_id, canal, enviada, abierta.

---

## 10. Métricas de éxito (KPIs)

- **Tasa de activación:** % de jóvenes que completan el test.
- **Cobertura informativa:** % de jóvenes alcanzados (atacar el 87% que no participa).
- **Conversión:** alertas → inscripciones reales.
- **Equidad territorial:** participación por Localidad 1/2/3.
- **Reducción de la dispersión:** nº de convocatorias centralizadas vs. canales sueltos.
- **Incidencia:** jóvenes que escalan a mesas/Consejos de Juventud.

---

## 11. Por qué esta solución GANA la hackathon

1. **Responde la pregunta central palabra por palabra** (organizar + centralizar + comunicar claro + accesible + incidir).
2. **Usa los datos reales del Excel** en la demo → credibilidad inmediata ante el jurado.
3. **Diferenciador con IA tangible:** el test + perfil + recomendación es un "wow" demostrable en vivo, no una promesa.
4. **Doble cara (joven + institución):** no solo informa, **articula** a los 33 actores dispersos.
5. **Inclusión real:** WhatsApp llega al joven desconectado, no solo al que ya participa.
6. **Impacto medible y social:** participación, empleabilidad y prevención (la desconexión correlaciona con violencia juvenil).
7. **Factible y sostenible:** alianza natural con Alcaldía, Sec. Participación, UTB y Fundación Mi Sangre (ya nombradas en los datos).

---

## 12. Sostenibilidad y escalabilidad

- **Dueño institucional:** Secretaría de Participación / Oficina de Juventud como administrador.
- **Aliados:** UTB, Fundación Mi Sangre, Escuela de Gobierno, Colectivo TRASO, Gobernación de Bolívar.
- **Escala:** modelo replicable en otros municipios de Bolívar y ciudades con Ley 1622/2013.

---

## 13. Roadmap

| Fase | Tiempo | Entregable |
|---|---|---|
| **Hackathon (MVP)** | Ahora | Demo: test IA + feed + mapa + 1 alerta + panel |
| **Piloto** | 1–3 meses | 1 localidad, datos reales, alianza con Sec. Participación |
| **Ciudad** | 6–12 meses | 3 localidades, WhatsApp masivo, panel de impacto |
| **Región** | 12+ meses | Bolívar / replicable nacional |

---

## 14. Guion de demo (5 min para el jurado)

1. **Gancho (30s):** "El 87% de los jóvenes de Cartagena no participa. No por falta de oportunidades, sino porque la información está rota." (mostrar mapa de datos).
2. **Test en vivo (1 min):** un jurado hace el Test de la Brújula.
3. **Magia IA (1 min):** aparece su Perfil Joven y su feed personalizado por localidad.
4. **Alerta (1 min):** llega una alerta de WhatsApp con una convocatoria real reescrita en lenguaje claro.
5. **Lado institución (1 min):** la Alcaldía publica una convocatoria y ve a cuántos jóvenes llegó.
6. **Cierre (30s):** "Convertimos información invisible en participación real. Esto ya es replicable."

---

## 15. Riesgos y mitigación

| Riesgo | Mitigación |
|---|---|
| Calidad/actualización de datos | Panel institucional + verificación; integración con fuentes oficiales |
| Brecha digital | Canal WhatsApp + versión ligera; puntos físicos en escuelas de liderazgo |
| Adopción institucional | Alianza temprana con Sec. Participación; demuestra ahorro de esfuerzos |
| Privacidad de menores (14+) | Consentimiento, datos mínimos, cumplimiento Ley 1581/2012 |

---

*Fuentes: Juventudes Cartagena reporte.xlsx · Informe de Calidad de Vida 2024 (módulo participación ciudadana) · Proyecciones Censo DANE 2018–2050 · Ley 1622 de 2013 (Estatuto de Ciudadanía Juvenil).*
