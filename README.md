# 🧭 Brújula Joven Cartagena

> **Tu brújula para participar, formarte y trabajar en Cartagena.**
> Plataforma con IA que centraliza la información juvenil dispersa de Cartagena y la convierte en **rutas personalizadas** de participación, formación, empleo e incidencia territorial.

Proyecto desarrollado para la **Hackathon de Juventudes de Cartagena (2026)**.

---

## 🎯 El problema

Cartagena tiene **245.653 jóvenes** (24,3% de la población), pero **el 87% no participa en ningún espacio ciudadano**. El problema **no es la falta de oportunidades** —hay 33 organizaciones, 57 consejeros de juventud, escuelas de liderazgo y convocatorias activas— sino que **la información está dispersa, segmentada y desactualizada**: vive en grupos de WhatsApp, redes institucionales y formularios sueltos. El joven conectado se entera; el resto, nunca.

## 💡 La solución

**Brújula Joven** resuelve exactamente eso:

1. 🧭 **Test inicial inteligente** (estilo test vocacional) → la IA genera un **Perfil Joven**.
2. 📍 **Centraliza** en un solo lugar convocatorias, eventos, mesas, vacantes y rutas de formación.
3. 🎯 **Recomienda con IA** lo que le sirve a cada joven y queda cerca, con alertas por WhatsApp.
4. 🏛️ Da a la Alcaldía y organizaciones un **panel para publicar y medir el impacto real**.

## ▶️ Cómo ejecutar

**Opción fácil (offline, sin instalar nada):**
```
Abre la carpeta "BrujulaJoven" y haz doble clic en index.html
```

**Opción servidor local:**
```bash
python -m http.server 5601 --directory BrujulaJoven
# Luego abre http://localhost:5601
```

## 📂 Estructura

| Archivo | Descripción |
|---|---|
| `BrujulaJoven/index.html` | La aplicación (prototipo funcional, 100% offline) |
| `PRD_BrujulaJoven.md` | Documento de producto (PRD): visión, datos, módulos, demo |
| `COMO_PRESENTAR.txt` | Guía rápida + guion de la demo de 5 min |

## 🛠️ Tecnología

HTML + CSS + JavaScript (vanilla), sin dependencias externas — corre en cualquier navegador sin conexión. La capa de IA (perfilado y recomendación) está diseñada para conectarse a la **Claude API** en producción.

## 📊 Fuentes de datos

Juventudes Cartagena reporte.xlsx · Informe de Calidad de Vida 2024 (módulo participación) · Proyecciones Censo DANE 2018–2050 · Ley 1622 de 2013 (Estatuto de Ciudadanía Juvenil).
