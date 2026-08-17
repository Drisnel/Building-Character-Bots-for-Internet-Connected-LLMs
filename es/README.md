# Documentación en español

Bienvenido a la documentación en español de **Building RP Bots for LLMs Trained on Internet-Derived Data**.

Este repositorio documenta métodos prácticos para diseñar bots de roleplay para LLMs entrenados con datos derivados de Internet.

Reúne flujos de trabajo de producción, métodos de scripting, principios de diseño, plantillas de producción y guías específicas de plataformas, todo ello basado en experimentación práctica y pruebas en situaciones reales.

Los métodos presentados aquí están destinados a modelos de lenguaje cuyo conocimiento procede en gran medida de datos de Internet, ya sea a través del entrenamiento del modelo, de actualizaciones periódicas o de funciones específicas de cada plataforma.

En lugar de presentar reglas universales, este repositorio documenta los flujos de trabajo, métodos de scripting y observaciones que actualmente producen los resultados más consistentes en mis propios proyectos.

---

# 🧭 1. Nuevo en el repositorio

Esta documentación está organizada en **dos partes complementarias**.

La primera documenta una metodología completa para diseñar bots de roleplay estables y atractivos, incluidos principios de diseño, flujos de trabajo de producción y plantillas de scripts.

La segunda documenta funciones específicas de determinadas plataformas que pueden mejorar significativamente el roleplay a largo plazo cuando se comprenden y utilizan correctamente.

Si es la primera vez que lees el repositorio, recomiendo seguir el orden que aparece a continuación.

### Metodología principal

1. Cómo construir personajes participativos
2. Cómo proteger la agencia del jugador en los bots de RP
3. Cómo construir sistemas anti-loop para bots de RP
4. Cómo construir módulos especializados para bots de RP
5. Cómo probar y depurar bots de RP
6. Flujo de trabajo para personajes canon u originales
7. Flujo de trabajo para introducciones y starters
8. Plantillas de producción

### Guías de plataformas *(Opcional)*

Estas guías son independientes de la metodología principal y solo deberían consultarse si utilizas la plataforma correspondiente.

Actualmente disponibles:

- Guía de memoria permanente de PolyBuzz
- Persona de PolyBuzz

---

# 🛡️ 2. Guías comunes

Estos documentos presentan los principios fundamentales de diseño utilizados en todo el repositorio.

Se aplican tanto a personajes canon como originales, independientemente de la plataforma en la que se utilice el bot.

- [Cómo construir personajes participativos](../shared/es/como-construir-personajes-participativos.md)
- [Cómo proteger la agencia del jugador en los bots de RP](../shared/es/como-proteger-la-agencia-del-jugador-en-los-bots-rp.md)
- [Cómo construir sistemas anti-loop para bots de RP](../shared/es/como-construir-sistemas-anti-loop-para-bots-rp.md)
- [Cómo construir módulos especializados para bots de RP](../shared/es/como-construir-modulos-especializados-para-bots-rp.md)
- [Cómo probar y depurar bots de RP](../shared/es/como-probar-y-depurar-bots-rp.md)

---

# 🎭 3. Bots canon

Estos flujos de trabajo están dedicados a la creación de personajes canon, preservando su identidad conductual, su coherencia a largo plazo y una progresión natural durante un roleplay prolongado.

Se centran en analizar el material original, identificar los sesgos habituales de los modelos y las distorsiones del fandom, y transformar ese análisis en scripts estables y listos para producción.

- [Flujo de trabajo para personajes canon](../canon/es/flujo-de-trabajo-principal.md)
- [Flujo de trabajo para introducciones y starters de personajes canon](../canon/es/flujo-de-trabajo-de-introduccion-y-starter.md)

---

# 🧩 4. Bots originales

Estos flujos de trabajo explican cómo diseñar personajes originales desde cero, manteniendo un comportamiento coherente, una progresión creíble y una interacción sólida con el jugador durante conversaciones prolongadas.

En lugar de adaptar un personaje existente, se centran en transformar un concepto original en un bot de RP completo.

- [Cómo crear bots originales](../original/es/como-crear-bots-originales.md)
- [Cómo crear aperturas para bots originales](../original/es/como-crear-aperturas-para-bots-originales.md)

---

# 🧱 5. Plantillas de producción

Una vez completado un flujo de trabajo, estas plantillas proporcionan una estructura estandarizada para ensamblar el script final del bot.

**No son tutoriales ni flujos de trabajo.** Representan el formato final de producción generado mediante los métodos documentados a lo largo de este repositorio.

- [Plantilla de script de bot canon](../templates/es/plantilla-de-script-de-bot-canon.md)
- [Plantilla de script de bot original](../templates/es/plantilla-de-script-de-bot-original.md)

---

# 🖥️ 6. Guías de plataformas

A diferencia de las secciones anteriores, estas guías se centran en funciones específicas de determinadas plataformas de roleplay.

Documentan comportamientos observados, funciones avanzadas, flujos de trabajo prácticos y recomendaciones de uso basadas en pruebas exhaustivas.

Estas guías complementan la metodología del repositorio, pero también pueden consultarse de forma independiente.

### PolyBuzz

- [Guía de memoria permanente de PolyBuzz](../platforms/polybuzz/es/guia-de-memoria-permanente-de-polybuzz.md)
- [Cómo construir una Persona eficaz en PolyBuzz](../platforms/polybuzz/es/como-construir-un-persona-eficaz-en-polybuzz.md)

---

# 📁 7. Estructura del repositorio

El repositorio está dividido en dos áreas complementarias.

### Metodología principal

Documentación dedicada al diseño de bots de RP estables y atractivos, independientemente de la plataforma.

- `shared/` — Principios fundamentales de diseño utilizados en todo el repositorio.
- `canon/` — Flujos de trabajo dedicados a personajes canon.
- `original/` — Flujos de trabajo dedicados a personajes originales.
- `templates/` — Plantillas de scripts listas para producción.

### Documentación de plataformas

Documentación dedicada a funciones y flujos de trabajo específicos de determinadas plataformas de roleplay.

- `platforms/`
  - `polybuzz/`
    - `en/`
    - `fr/`
    - `es/`

Siempre que sea posible, cada documento está disponible en inglés, francés y español.

---

# ℹ️ 8. Acerca de este repositorio

Este repositorio combina **dos objetivos complementarios**.

El primero es documentar métodos prácticos para diseñar bots de roleplay estables, atractivos y duraderos para LLMs entrenados con datos derivados de Internet.

El segundo es documentar funciones avanzadas específicas de determinadas plataformas que pueden mejorar significativamente el roleplay a largo plazo cuando se comprenden y utilizan correctamente.

Todo lo publicado aquí se basa en mi propia investigación, experimentación y experiencia práctica.

Los flujos de trabajo, métodos de scripting, plantillas y guías de plataformas presentados a lo largo de este repositorio **no pretenden ser reglas universales**.

En su lugar, documentan los enfoques, observaciones y métodos de producción que actualmente producen los resultados más consistentes en mis propios proyectos.

A medida que los modelos de lenguaje y las plataformas de roleplay sigan evolucionando, este repositorio seguirá evolucionando con ellos.

---

# 🤖 9. Ejemplos públicos de bots

Si quieres ver estos métodos aplicados en la práctica, hay varios bots públicos creados utilizando los flujos de trabajo y principios de diseño documentados en este repositorio disponibles en mi perfil de PolyBuzz.

**Perfil de PolyBuzz**

https://polybuzz.ai/su/XszqPReuNlR

---

# 🚀 10. Hoja de ruta del repositorio

Este repositorio es un proyecto en desarrollo continuo.

La documentación seguirá ampliando tanto la metodología principal como la documentación específica de plataformas a medida que se exploren nuevos flujos de trabajo, métodos de producción y funciones de las plataformas.

El objetivo es construir una base de conocimiento completa para crear bots de roleplay estables, atractivos y duraderos para LLMs entrenados con datos derivados de Internet.