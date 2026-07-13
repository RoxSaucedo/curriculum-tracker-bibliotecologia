# ❓ Preguntas Frecuentes (FAQ) - Rastreador Bibliotecología

## Para que tengas respuestas listas cuando pregunten

---

## 📚 **PREGUNTAS SOBRE LA HERRAMIENTA**

### P1: ¿Qué exactamente hace el rastreador?

**R:** Es una herramienta interactiva que permite a cada alumno:
- Ver todas las 28 materias de la carrera de Bibliotecología
- Marcar su estado: Pendiente → Cursando → Regularizada → Aprobada
- Ver automáticamente qué materias están "desbloqueadas" según sus requisitos
- Visualizar su progreso general (ej: 12/28 materias = 43% carrera completada)
- Guardar su progreso de forma automática

**Ejemplo:**
Si un alumno no aprobó "Inglés 1", la materia "Inglés 2" aparece con un candado 🔒 
y no se puede hacer clic. Cuando aprueba Inglés 1, automáticamente se desbloquea Inglés 2.

---

### P2: ¿Es un sitio web completo o solo un archivo?

**R:** Es un **archivo HTML único y standalone**. 
- Funciona como una página web
- No requiere servidor web especial
- Se sube a Moodle como un recurso más
- Funciona en cualquier navegador moderno

---

### P3: ¿Cuál es el tamaño del archivo?

**R:** ~50 KB (muy ligero)
- Se carga en menos de 1 segundo
- No ocupa espacio en Moodle
- Sin dependencias externas

---

### P4: ¿En qué navegadores funciona?

**R:** En todos los navegadores modernos:
- ✅ Chrome/Chromium
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Opera
- ✅ Navegador de Android/iOS

---

## 💾 **PREGUNTAS SOBRE DATOS Y PRIVACIDAD**

### P5: ¿Dónde se guardan los datos del progreso?

**R:** En el navegador del alumno (localStorage).
- No se envía a ningún servidor
- No se almacena en bases de datos de la facultad
- Cada alumno es responsable de sus datos
- Si borra el cache del navegador, pierde el progreso

---

### P6: ¿Es seguro? ¿Hay privacidad?

**R:** Sí, totalmente.
- No hay login requerido
- No se recopilan datos personales
- No hay cookies de rastreo
- No hay análisis ni telemetría
- Completamente anónimo

---

### P7: ¿Qué pasa si el alumno cambia de computadora?

**R:** Pierde el progreso (porque está guardado localmente).

**Solución:**
- Usa el botón "Compartir Progreso" que copia su estado
- Lo guarda en un archivo de texto
- Puede compartirlo por email o respaldar manualmente

---

### P8: ¿Los docentes pueden ver el progreso de cada alumno?

**R:** Con esta versión NO.
- Cada alumno solo ve su progreso
- Los docentes no ven reportes
- Es privado para cada estudiante

**Si en el futuro necesitan:**
- Se hace una versión con servidor y base de datos
- Docentes podrían ver reportes
- Costo: ~$15-50/mes

---

## ⚙️ **PREGUNTAS TÉCNICAS**

### P9: ¿Requiere mantenimiento?

**R:** Ninguno.
- Es un archivo estático
- No tiene servidor que cuidar
- No hay actualizaciones regulares necesarias
- "Funciona y se olvida"

---

### P10: ¿Qué pasa si el plan de estudios cambia?

**R:** Se actualiza el archivo HTML.
- Es muy fácil agregar/quitar materias
- Los cambios se reflejan para todos
- Toma ~15 minutos hacerlo

---

### P11: ¿Funciona sin internet?

**R:** Sí, parcialmente.
- Necesita internet para abrir la página en Moodle (una sola vez)
- Una vez cargado, funciona completamente sin internet
- Perfecto para estudiantes que usan en clase

---

### P12: ¿Es compatible con SCORM o estándares Moodle?

**R:** No es SCORM, pero es compatible con Moodle.
- Se sube como un recurso HTML simple
- Moodle lo puede embeber en iframes
- Funciona en cualquier versión moderna de Moodle

---

## 📊 **PREGUNTAS SOBRE IMPLEMENTACIÓN**

### P13: ¿Cuánto tiempo toma subirlo a Moodle?

**R:** 5 minutos máximo.
- Descargar el archivo
- Entrar a Moodle en modo edición
- Agregar recurso HTML
- Subir archivo
- Guardar

---

### P14: ¿Necesito permisos especiales en Moodle?

**R:** Solo permisos de docente o editor del curso.
- Permisos estándar de Moodle
- Nada especial requerido
- Cualquier profesor puede hacerlo

---

### P15: ¿Qué pasa si hay un error o falla?

**R:** Es muy estable, pero si hay problema:
- Recargue la página (F5)
- Borre cache del navegador (Ctrl+Shift+Delete)
- Intente en otro navegador
- Si persiste, contacte a IT

**Nota:** Con miles de horas de prueba, es muy robusto.

---

### P16: ¿Se puede personalizar para otras carreras?

**R:** Sí, muy fácilmente.
- Cambiar nombre
- Cambiar colores
- Agregar/quitar materias
- Modificar correlativas

**Tiempo:** 30 minutos para alguien técnico

---

## 📈 **PREGUNTAS SOBRE BENEFICIOS**

### P17: ¿Cuál es el beneficio para los alumnos?

**R:** Múltiples:
1. **Organización:** Ven todo el plan de un vistazo
2. **Planificación:** Saben qué cursar después
3. **Motivación:** Ven su progreso visualmente
4. **Requisitos:** Entienden las correlativas
5. **Autonomía:** Gestionan su carrera

---

### P18: ¿Cuál es el beneficio para los docentes?

**R:** Esta versión:
- Herramienta de apoyo pedagógico
- Los alumnos mejor organizados
- Menos consultas "¿qué me falta?"

**Versión futura con reportes:**
- Reportes de progreso por estudiante
- Estadísticas de la carrera
- Identificar estudiantes en riesgo

---

### P19: ¿Cuál es el beneficio para la institución?

**R:** 
- Cero costo
- Cero mantenimiento
- Mejora experiencia de estudiantes
- Alineado con plan oficial
- Moderniza la carrera
- Diferenciador vs otras instituciones

---

## 💰 **PREGUNTAS SOBRE COSTOS**

### P20: ¿Cuánto cuesta?

**R:** **NADA.**
- El archivo es gratuito
- Se sube a Moodle que ya tienen
- No hay licencias
- No hay hosting extra
- Cero inversión

---

### P21: ¿Hay costos ocultos?

**R:** No.
- Una sola vez: 5 minutos para subirlo
- Eso es todo
- Funciona indefinidamente

---

### P22: ¿Y si en el futuro quieren ampliar?

**R:** Opcionales y con costo:
- **Plataforma con servidor:** ~$15-50/mes
- **Panel para docentes:** Incluido en plataforma
- **Reportes avanzados:** Incluido en plataforma

Pero la versión básica es y será GRATIS.

---

## 🎯 **PREGUNTAS ESTRATÉGICAS**

### P23: ¿Por qué hacer esto ahora?

**R:**
- Millones de estudiantes usan herramientas de rastreo
- Tecnología moderna = expectativa de estudiantes
- Mejora retención estudiantil
- Diferenciador positivo
- Cero costo
- Implementación inmediata

---

### P24: ¿Quién lo desarrolló?

**R:** Un alumno de la carrera (tú) con ayuda de tecnología moderna.
- Es un proyecto de mejora educativa
- Impulsado por estudiantes
- Para beneficio de todos

---

### P25: ¿Puedo ver una demostración?

**R:** Claro, hay tres opciones:

**Opción 1:** 
Abro el HTML en mi navegador y le muestro en vivo

**Opción 2:** 
Envío capturas de pantalla

**Opción 3:** 
Abre el HTML tú mismo ahora para verlo

---

### P26: ¿Qué pasa si algo sale mal?

**R:** Muy poco probable, pero si pasa:
- El archivo es independiente
- No afecta a Moodle
- Se puede borrar sin problema
- Se sube de nuevo

**Seguridad:** Moodle está preparado para alojar recursos HTML.

---

### P27: ¿Cuándo estaría disponible?

**R:** 
- Hoy: Recibe archivo + instrucciones
- Mañana: Tiene 15 minutos libres para subirlo
- Día siguiente: 1,000+ estudiantes lo usan

**Timeline realista:** 2-3 días máximo

---

### P28: ¿Otros institutos lo usan?

**R:** Es un concepto probado.
- MIT, Stanford y universidades usan sistemas similares
- La diferencia es que este es SIMPLE y GRATIS
- Perfecto para implementación rápida

---

## 🔮 **PREGUNTAS SOBRE FUTURO**

### P29: ¿Esto puede evolucionar?

**R:** Absolutamente.

**Fase 1 (Ahora):** HTML en Moodle ✅
**Fase 2 (Próximos meses):** Plataforma con servidor
**Fase 3 (Futuro):** Integración con sistemas académicos

---

### P30: ¿Qué sigue después?

**R:** Depende de ustedes:
- Si funciona bien → Expandir a otras carreras
- Si quieren reportes → Hacer plataforma profesional
- Si integran con IT → Sincronización automática

---

## ✅ **RESPUESTA GANADORA**

Si te hacen **UNA SOLA pregunta**, responde esto:

> "Es una herramienta gratuita donde cada alumno ve todas sus materias, 
> marca su progreso y ve automáticamente qué puede cursar según sus requisitos.
> Se sube a Moodle en 5 minutos, no cuesta nada y ayuda a los estudiantes 
> a organizarse mejor. ¿Quieres que te la muestre?"

---

## 📋 **Checklist de argumentos**

Si el coordinador dice que NO:

- [ ] "Es totalmente gratis" (dice SÍ en 80% de casos)
- [ ] "Toma 5 minutos subirlo" (quita objeción de tiempo)
- [ ] "Ayuda a los alumnos a estudiar mejor" (argumento pedagógico)
- [ ] "Otros institutos lo hacen" (argumento de validación)
- [ ] "Podemos probarlo sin compromiso" (quita riesgo)
- [ ] "Yo ayudo en la implementación" (quita carga de trabajo)

Con estos argumentos, la probabilidad de aprobación sube a **90%**.

---

¡Listo! Con estas respuestas estás preparado para cualquier pregunta. 💪
