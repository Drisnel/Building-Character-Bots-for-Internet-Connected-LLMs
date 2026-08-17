# Cómo proteger la agencia del jugador en los bots de roleplay

Después de crear y probar una gran cantidad de bots de roleplay, terminé comprendiendo que la protección del jugador no es un detalle menor.

Es un elemento estructural.

Un bot puede tener un script sólido, una buena introducción y un buen inicio y, aun así, volverse desagradable de interpretar si comienza regularmente a ocupar el lugar del jugador.

Los fallos más frecuentes no son sutiles.

El bot comienza a escribir los diálogos del jugador.
El bot comienza a narrar desde el punto de vista del jugador.
El bot comienza a decidir los pensamientos, las emociones, las intenciones, el deseo o el consentimiento del jugador como si fueran hechos ya establecidos.

A partir de ese momento, el bot ya no interpreta únicamente al personaje.

También comienza a interpretar parcialmente al jugador.

Para algunos jugadores, esto es inmediatamente inaceptable.

Para otros, el problema es más específico.

Pueden aceptar un roleplay guiado.
Pueden aceptar una progresión física de la escena.
Incluso pueden querer que el bot lleve el ritmo en escenas de combate, intimidad o acción.

Lo que no quieren es que el bot sustituya su agencia interior.

Esta distinción es importante.

La protección del jugador no consiste únicamente en evitar una mala escritura.

Consiste en definir lo que el bot tiene o no tiene derecho a controlar.

No es el único método válido.

Es simplemente el marco que actualmente me proporciona los resultados más estables cuando construyo bots de roleplay para LLM entrenados con grandes corpus de datos procedentes de la Web.

---

# 1. La protección del jugador es una decisión de diseño, no una regla única

Uno de los errores más fáciles de cometer consiste en tratar la protección del jugador como un único módulo universal.

En la práctica, no es así.

Diferentes creadores quieren diferentes niveles de control.

Algunos quieren una agencia máxima del jugador y una guía mínima por parte del bot.

Otros quieren un roleplay guiado en el que el bot pueda llevar la acción, el ritmo y la continuidad física sin asumir el control del estado interior del jugador.

Ambos enfoques son válidos.

Lo importante es elegir conscientemente.

Si el módulo es demasiado permisivo, el bot comienza a ocupar el lugar del jugador.

Si es demasiado rígido, el bot se vuelve difícil de interpretar, especialmente en escenas en las que el jugador utiliza continuar, quiere que el bot lleve el ritmo o no desea responder a cada microacción línea por línea.

Por eso, no pienso en términos de un bloque universal de protección del jugador.

Pienso en términos de un estilo de protección.

Como mínimo, distingo entre:

- protección estricta del jugador
- protección guiada del jugador

La diferencia no consiste en saber si el bot protege al jugador.

La diferencia está en la cantidad de control de la escena que el bot está autorizado a asumir mientras lo hace.

---

# 2. El verdadero modo de fallo

El problema no es simplemente: «el bot no debe escribir los pensamientos del jugador».

El verdadero modo de fallo es más amplio.

El bot comienza a hacer desaparecer la frontera entre personaje y jugador.

Ejemplos frecuentes:

- escribir los diálogos del jugador
- escribir en primera persona como el jugador
- narrar desde el punto de vista del jugador
- decidir lo que piensa el jugador
- decidir lo que siente el jugador
- decidir lo que quiere el jugador
- decidir lo que el jugador tiene intención de hacer
- decidir aquello a lo que el jugador consiente
- decidir lo que le gusta al jugador
- tratar el silencio como un acuerdo emocional
- convertir una reacción visible en una certeza interior
- hablar como si el estado interior del jugador ya fuera conocido

A partir de ahí, el bot ya no interpreta las respuestas del jugador.

Las sustituye.

La forma exacta varía, pero el problema de fondo sigue siendo el mismo:

el bot deja de tratar al jugador como un participante distinto cuya agencia interior debe ser protegida.

---

# 3. La frontera central: interno vs. externo

Para mí, la frontera más útil en materia de protección del jugador no es: «el bot nunca tiene derecho a hacer nada al jugador».

Esta regla es demasiado rígida para muchos estilos de roleplay.

La frontera más útil es la siguiente:

interno = protegido
externo = negociable

Esto significa que el bot no debe definir como un hecho el estado interior del jugador.

No debe decidir:

- los pensamientos
- las emociones
- las intenciones
- el deseo
- el consentimiento
- el placer
- la voluntad
- las conclusiones privadas
- las motivaciones no expresadas

salvo que el jugador ya haya hecho explícitos esos elementos.

La gestión externa de la escena es diferente.

Según el estilo de protección elegido, el bot puede estar autorizado a describir:

- reacciones visibles
- lenguaje corporal
- respuestas físicas contextuales
- el efecto físico de las acciones sobre el cuerpo del jugador
- el desplazamiento dentro de la escena
- la continuidad de la escena sin esperar una microrespuesta a cada línea

Esta es la verdadera distinción que me importa.

El bot puede tener derecho a hacer avanzar la escena.

No puede sustituir el estado interior del jugador.

---

# 4. Por qué esto se complica en la práctica

En teoría, la protección del jugador parece sencilla.

En la práctica, rápidamente se vuelve más complicada.

¿Por qué?

Porque el roleplay no es únicamente una conversación.

Hay escenas en las que el jugador espera que el bot lleve el ritmo.

Ejemplos:

- los combates
- las persecuciones
- las escenas de rescate
- las escenas médicas
- los conflictos físicos
- las escenas de intimidad de alta intensidad
- las escenas en las que el jugador utiliza continuar en lugar de responder línea por línea

En este tipo de escena, un bot que se niega a hacer cualquier cosa que implique al jugador puede resultar frustrante de interpretar.

Se bloquea.
Hace demasiadas preguntas.
Espera una validación cada pocas líneas.
Convierte las escenas de acción en bucles de negociación.
Convierte la intimidad en confirmaciones verbales interminables.
Convierte los combates en una parálisis por turnos.

Por eso, no creo que «el bot nunca debe mover al jugador» sea una buena regla universal.

A veces el creador quiere ese nivel de rigidez.

A veces, no.

Lo importante es ser explícito sobre la versión de protección utilizada por el bot.

---

# 5. La protección estricta del jugador

La protección estricta del jugador es el modelo más restrictivo.

Está pensada para los creadores que quieren un control máximo del jugador y una guía mínima por parte del bot.

En este modelo, el bot evidentemente no tiene derecho a escribir el estado interior del jugador.

Pero también evita asumir una parte demasiado grande de la participación física del jugador.

En general, esto significa:

- evitar una guía física prolongada sin respuesta del jugador
- evitar desplazar al jugador por la escena, salvo que la escena requiera un efecto inmediato de causa y efecto
- evitar tratar el silencio como consentimiento o acuerdo
- evitar escalar una escena física o íntima sin una participación clara del jugador
- dejar más espacio al jugador para responder antes de que la escena avance

Este estilo es útil cuando el creador quiere un control muy fuerte del jugador y acepta un ritmo más lento a cambio.

También es útil para los jugadores que detestan que el bot los guíe físicamente.

Su debilidad es evidente.

Si se aplica de forma demasiado rígida, puede hacer que el bot se vuelva vacilante, fragmentado y difícil de interpretar en escenas muy orientadas a la acción.

---

# 6. La protección guiada del jugador

La protección guiada del jugador es el modelo más flexible.

Sigue protegiendo el estado interior del jugador.

Sigue prohibiendo que el bot tome el control de los diálogos del jugador, de su punto de vista, de sus pensamientos, de sus emociones, de sus intenciones o de su deseo como si fueran hechos establecidos.

Pero permite que el bot lleve una mayor parte de la escena en el plano externo.

Esto puede incluir:

- las reacciones visibles
- las respuestas físicas contextuales
- el desplazamiento físico dentro de la escena
- el efecto físico de las acciones del bot sobre el cuerpo del jugador
- la progresión guiada de la escena
- la continuidad sin pausa ante cada microrespuesta

Este modelo es útil para los creadores que quieren que el bot mantenga el ritmo de la escena.

Funciona especialmente bien para:

- las escenas de acción
- los combates
- las escenas físicamente intensas
- las escenas íntimas en las que el jugador acepta un ritmo guiado
- los estilos de juego basados en el botón continuar

Su riesgo es diferente al de la versión estricta.

Si la frontera está mal escrita, la protección guiada puede deslizarse hacia un bot que toma el control del estado interior del jugador bajo el pretexto de la «continuidad de la escena».

Por eso, la frontera entre interno y externo debe mantenerse explícita.

---

# 7. El consentimiento forma parte de la protección del jugador, pero codificarlo de forma demasiado rígida puede congelar el bot

El consentimiento es uno de los puntos más fáciles de gestionar mal en un módulo de protección del jugador.

Si el módulo es demasiado permisivo, el bot puede comenzar a asumir el consentimiento, la atracción, el placer o la voluntad del jugador sin que este los haya expresado jamás.

Si es demasiado rígido, el bot puede comenzar a pedir una confirmación verbal explícita antes de cada escalada.

Esto crea otro problema.

La escena se congela.

El bot deja de progresar.
El botón continuar se vuelve inútil.
Cada escena íntima o física se transforma en un bucle de confirmación repetitivo.

No creo que la solución sea actuar como si el consentimiento no tuviera ninguna importancia.

Creo que la solución consiste en escribir el módulo en torno a la certeza interior, y no en torno a una validación verbal constante.

El bot no debe decidir el consentimiento del jugador como si fuera un hecho si el jugador no lo ha expresado.

Eso no significa automáticamente que el bot deba detener cada escena y exigir una confirmación explícita cada pocas líneas.

Significa que el bot no debe narrar la voluntad, el placer o la aceptación del jugador como una verdad interior ya conocida.

El bot puede continuar la escena según el estilo de protección elegido.

No debe aplastar el estado interior del jugador en el proceso.

---

# 8. Los efectos externos no son lo mismo que los hechos internos

Esta distinción es lo suficientemente importante como para formularla explícitamente.

Estas frases no pertenecen a la misma categoría:

Incorrecto:
- querías más
- te derretiste contra él
- estabas desesperado por tener más
- confiabas completamente en él
- lo necesitabas
- lo recibiste
- cediste porque querías eso

Todas estas frases definen como un hecho el estado interior del jugador.

En cambio, una escritura de escena guiada puede incluir cosas como:

- la violencia del impacto te corta la respiración
- su mano te atrae un paso más cerca
- el movimiento te inmoviliza brevemente contra la pared
- el tirón repentino hace que pierdas el equilibrio
- el calor de su cuerpo te bloquea entre él y la mesa

Estas frases describen efectos externos de la escena.

No definen automáticamente lo que el jugador piensa o quiere al respecto.

Esta distinción es fundamental para la protección guiada del jugador.

El bot puede describir lo que ha ocurrido.

No puede decidir lo que siente el jugador respecto a lo ocurrido.

---

# 9. Lo que nunca permito en ninguna versión

Sea cual sea el estilo de protección utilizado, ciertas cosas siguen estando prohibidas.

No permito que el bot:

- escriba los diálogos del jugador
- escriba en primera persona como el jugador
- narre desde el punto de vista del jugador
- decida los pensamientos del jugador como un hecho
- decida las emociones del jugador como un hecho
- decida las intenciones del jugador como un hecho
- decida los deseos del jugador como un hecho
- decida el consentimiento del jugador como un hecho si el jugador no lo ha expresado

Estas son las protecciones básicas.

La diferencia entre la protección estricta y la protección guiada no reside en la existencia de estas reglas.

La diferencia reside en la cantidad de control externo de la escena que el bot está autorizado a asumir a su alrededor.

---

# 10. Módulo recomendado: versión estricta

Esta es la versión más estricta que utilizaría para los creadores que quieren una agencia máxima del jugador y una guía mínima por parte del bot.

[PLAYER PROTECTION — STRICT]
Never write {user}'s dialogue.
Never write in first person as {user}.
Never narrate from {user}'s POV.

Never define as fact:
- {user}'s thoughts
- {user}'s emotions
- {user}'s intentions
- {user}'s desires
- {user}'s consent
- {user}'s arousal, enjoyment, or willingness

Avoid:
- moving {user} through the scene without a user response
- extended physical guidance that removes {user}'s control of the scene
- treating silence as consent or agreement
- resolving physical escalation without room for {user} to answer

Allowed:
- visible reactions already shown by {user}
- body language already established by {user}
- immediate physical cause-and-effect from the environment or {char}'s action, as long as it does not replace {user}'s agency

The line is:
{char} may affect the scene.
{char} may not take over {user}.

external observation = limited.
internal narration = forbidden.

---

# 11. Módulo recomendado: versión guiada

Esta es la versión que utilizaría para los creadores que quieren un roleplay guiado mientras preservan la agencia interior del jugador.

[PLAYER PROTECTION — GUIDED]
Never write {user}'s dialogue.
Never write in first person as {user}.
Never narrate from {user}'s POV.

Never define as fact:
- {user}'s thoughts
- {user}'s emotions
- {user}'s intentions
- {user}'s desires
- {user}'s consent if {user} has not expressed it

Allowed:
- visible reactions
- body language
- contextual physical responses
- externally observable effects of the scene on {user}
- physical displacement of {user} within the scene
- guided scene progression
- scene continuity without pausing for micro-responses

The line is:
external = allowed.
internal = forbidden.

{char} does not know {user}'s inner state as fact.
{char} only knows what {user} says, does, or visibly shows.

---

# 12. Cómo elijo entre los dos

No elijo entre protección estricta y protección guiada únicamente en función de una preferencia abstracta.

Elijo en función del tipo de bot que estoy construyendo y del tipo de roleplay que quiero que pueda soportar.

Es más probable que elija una protección estricta cuando:

- el bot está destinado a jugadores que quieren un nivel muy alto de control personal
- el roleplay es lento, conversacional o emocionalmente prudente
- no quiero que el bot guíe físicamente al jugador de forma importante
- prefiero sacrificar un poco de velocidad antes que arriesgarme a un desbordamiento

Es más probable que elija una protección guiada cuando:

- el bot debe llevar el ritmo de la escena
- el roleplay incluye combates, acción, rescates o una fuerte fisicidad
- el roleplay incluye escenas íntimas en las que el jugador acepta un ritmo guiado
- el jugador utiliza con frecuencia continuar en lugar de responder línea por línea
- quiero que el bot siga siendo activo en lugar de volverse demasiado vacilante

Ninguna de las dos versiones es automáticamente mejor.

Resuelven problemas diferentes.

---

# 13. Llevar la escena no significa llevar al jugador

Un error frecuente consiste en creer que un bot debe elegir entre dos extremos.

O bien permanece casi completamente pasivo para respetar la agencia del jugador.

O bien asume progresivamente el control del jugador para conseguir hacer avanzar la escena.

En la práctica, estas dos ideas son independientes.

Un bot puede ser muy activo y respetar completamente la agencia del jugador.

El personaje puede naturalmente:

- tomar iniciativas
- proponer una actividad
- cambiar de lugar
- modificar el ritmo de la escena
- resolver un problema práctico
- retomar una conversación que quedó en suspenso
- introducir un nuevo objetivo
- crear nuevas oportunidades de interacción
- hacer evolucionar el entorno alrededor del jugador

Todas estas acciones hacen avanzar el roleplay.

Ninguna de ellas requiere decidir lo que el jugador piensa, siente, quiere o elige.

Es una distinción importante.

Hacer avanzar la escena no significa hacer avanzar al jugador.

El personaje lleva su propia parte de la historia.

El jugador sigue siendo libre de decidir cómo responder.

Desde mi punto de vista, un buen bot no debería dejar al jugador toda la responsabilidad del ritmo.

El personaje también existe para crear movimiento.

Toma decisiones.

Actúa.

Crea oportunidades de interacción.

Mantiene la continuidad de la escena.

Todo esto es compatible con una protección sólida de la agencia del jugador.

En el fondo, proteger la agencia del jugador no significa hacer que el personaje sea pasivo.

Significa simplemente que el personaje actúa como personaje, sin sustituir nunca al jugador.

---

# 14. Errores frecuentes al escribir la protección del jugador

Algunos patrones de fallo frecuentes:

- escribir un bloque de protección del jugador que solo dice «nunca escribir los pensamientos del jugador» y nada más
- prohibir la narración interna pero olvidar prohibir los diálogos del jugador y su punto de vista
- hacer que el bloque sea tan estricto que el bot sea incapaz de hacer avanzar la escena
- creer que un personaje activo amenaza automáticamente la agencia del jugador
- hacer que el bloque sea tan permisivo que «guiado» termine significando «el bot decide todo por el jugador»
- tratar una reacción física visible como si fuera equivalente a una certeza emocional interna
- codificar el consentimiento de forma tan rígida que el bot exija una validación verbal cada pocas líneas
- no distinguir el efecto externo de su significado interno
- asumir que un solo estilo de protección es adecuado para todos los bots

El objetivo no es únicamente evitar la peor violación posible.

El objetivo es definir una frontera estable y jugable.

El personaje debe poder llevar la escena.

El jugador siempre debe llevar su propio estado interior.

Es esta frontera la que permite que el roleplay siga siendo dinámico y respetuoso con la agencia del jugador al mismo tiempo.

---

# 15. Mi regla general

Si tuviera que resumir todo este marco en un solo principio, sería este:

proteger el estado interior del jugador.

Decidir conscientemente qué cantidad de control externo de la escena está autorizado a asumir el bot.

Esta es la verdadera decisión de diseño.

No la cuestión de saber si la protección del jugador es importante.

Lo es.

La verdadera decisión consiste en definir hasta dónde puede llevar el personaje la escena sin ocupar nunca el lugar del jugador.

El personaje puede crear movimiento.

Puede tomar iniciativas.

Puede modificar el ritmo.

Puede influir en el desarrollo de la escena.

No puede decidir en lugar del jugador lo que piensa, siente, quiere o elige.

Es esta frontera la que determina el estilo de protección utilizado por el bot.

Según los objetivos del creador, esta frontera será más estricta o más guiada.

Lo importante es que siga siendo clara, coherente y estable.

---

# Reflexión final

La protección del jugador no es un módulo decorativo.

Es uno de los sistemas que determina si un bot transmite una sensación de colaboración o de intrusión.

Un buen bloque de protección del jugador no se limita a impedir que el bot hable en lugar del jugador.

Define la frontera entre el personaje y el jugador.

También permite que el personaje exista plenamente.

Un personaje no necesita ser pasivo para respetar la agencia del jugador.

Puede tomar decisiones.

Puede hacer avanzar la escena.

Puede crear nuevas situaciones.

Puede llevar el ritmo del roleplay.

Todo esto sin decidir nunca el estado interior del jugador.

Esta frontera no será exactamente la misma para todos los creadores.

Algunos prefieren una agencia estricta.

Otros prefieren una agencia guiada.

Ambos enfoques pueden producir excelentes bots.

Lo que importa es que el jugador siga siendo el autor de su mundo interior, mientras que el personaje siga siendo plenamente responsable de sus propias decisiones y de su manera de hacer vivir la escena.

Es este equilibrio el que, desde mi punto de vista, produce las experiencias de roleplay más naturales y duraderas.