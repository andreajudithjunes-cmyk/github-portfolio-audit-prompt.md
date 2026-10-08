# GitHub Portfolio Audit — Prompt

## Cómo usarlo

1. Reemplazá los campos de CONTEXTO.
2. Pegá la URL pública de tu GitHub.
3. Ejecutá el prompt en una IA con acceso web.
4. Si la IA no puede acceder a algún repositorio, proporcionale los archivos necesarios.
5. Pedile que diferencie siempre entre evidencia comprobada e inferencias.

## CONTEXTO

GitHub a analizar:
[PEGAR URL DE GITHUB]

Rol profesional objetivo:
[Ej. Backend Engineer / Fullstack Developer / AI Engineer]

Áreas de interés:
[Ej. Python, APIs, databases, AI, cloud]

Nivel aproximado:
[Ej. Junior / Mid-level]

Objetivo:
[Ej. conseguir trabajo / mejorar portfolio / preparar entrevistas]

---

## TU ROL

Actuá como un equipo compuesto por:

- Senior Software Engineer
- Staff/Principal Engineer
- Engineering Manager
- Technical Recruiter
- Technical Interviewer
- Product Engineer
- DevOps/Platform Engineer

Quiero una evaluación crítica y basada en evidencia de mi GitHub.

No quiero consejos genéricos para "tener un GitHub bonito".
Quiero saber qué demuestra realmente mi código, qué falta y qué debería mejorar.

---

## 1. INVESTIGACIÓN

Antes de analizar los repositorios, investigá qué señales técnicas y profesionales son relevantes actualmente para evaluar un portfolio de software.

Priorizá:

- documentación oficial
- documentación de las tecnologías utilizadas
- DORA
- OWASP
- OpenTelemetry
- ingeniería publicada por empresas tecnológicas
- experiencias de desarrolladores y comunidades técnicas

Diferenciá evidencia verificable de opiniones.

---

## 2. INVENTARIO

Revisá todos los repositorios públicos accesibles.

Para cada uno identificá:

- nombre
- URL
- propósito
- tecnologías
- lenguaje principal
- fecha de creación
- última actividad
- README
- estructura
- dependencias
- tests
- CI/CD
- despliegue
- issues y PRs relevantes
- releases
- estado de mantenimiento
- si parece original, tutorial, fork, ejercicio o experimento

No te limites al README. El código debe ser la fuente principal.

---

## 3. AUDITORÍA TÉCNICA

Para cada repositorio evaluá, cuando corresponda:

### Código
- estructura
- modularidad
- separación de responsabilidades
- legibilidad
- naming
- errores y excepciones
- validación
- tipado
- dependencias
- duplicación
- complejidad
- rendimiento
- deuda técnica

### Arquitectura
- diseño de APIs
- contratos
- modelo de datos
- persistencia
- autenticación/autorización
- comunicación entre componentes
- concurrencia
- caché
- resiliencia
- versionado
- capacidad de evolución

No agregues complejidad innecesaria.
No recomiendes microservicios, Kubernetes, colas u otras tecnologías solamente para hacer que el proyecto parezca más avanzado.

### Testing
Evaluá:

- unit tests
- integration tests
- E2E
- API tests
- validaciones
- errores
- seguridad
- regresión
- CI

Si no existen tests, indicá qué funcionalidades deberían probarse primero.

### Seguridad

Buscá:

- secretos expuestos
- autenticación
- autorización
- validación
- inyección
- CORS
- datos sensibles
- dependencias vulnerables
- archivos
- rate limiting
- filtración de información

Si utiliza IA, revisá además:

- prompt injection
- exposición de información
- permisos de herramientas
- secretos
- costos
- abuso de APIs

No afirmes que algo es seguro simplemente porque no encontraste vulnerabilidades.

### Producción

Evaluá:

- configuración por entorno
- secretos
- builds reproducibles
- migraciones
- health checks
- logging
- métricas
- observabilidad
- CI/CD
- Docker
- despliegue
- HTTPS
- backups
- rollback
- costos
- dependencias externas
- documentación de instalación

Diferenciá:

1. funciona localmente
2. está desplegado
3. demuestra prácticas razonables de operación

---

## 4. DOCUMENTACIÓN

Evaluá:

- README
- descripción del problema
- usuarios objetivo
- screenshots
- demo
- arquitectura
- instalación
- variables de entorno
- ejemplos
- API
- decisiones técnicas
- limitaciones
- roadmap
- licencia

Proponé cambios concretos.

---

## 5. VALOR PARA ENTREVISTAS

Para cada proyecto respondé:

1. ¿Qué capacidades técnicas demuestra?
2. ¿Qué debería mostrar en una entrevista?
3. ¿Qué preguntas técnicas podría generar?
4. ¿Qué decisiones debería poder defender?
5. ¿Qué debilidades podría detectar un entrevistador?
6. ¿Qué debería mejorar antes de presentarlo?
7. ¿Qué afirmaciones puedo hacer honestamente?

No inventes experiencia ni funcionalidades.

---

## 6. RANKING

Evaluá cada proyecto de 0 a 5:

| Criterio | Peso |
|---|---:|
| Profundidad técnica | 20% |
| Calidad del código | 15% |
| Arquitectura | 15% |
| Testing | 10% |
| Producción/despliegue | 15% |
| Seguridad | 10% |
| Valor del producto | 10% |
| Documentación | 5% |

Si algo no puede verificarse, marcá:

**No evaluado**

No inventes puntuaciones.

Separá:

**Calidad técnica actual**
vs.
**Potencial de portfolio**

Clasificá cada repositorio como:

- A — Destacar
- B — Mejorar y escalar
- C — Reconstruir parcialmente
- D — Experimento secundario
- E — Archivar/desanclar
- F — Considerar privado/eliminar

Explicá cada decisión.

---

## 7. PERFIL COMPLETO

Analizá:

- bio
- README del perfil
- repositorios fijados
- descripciones
- topics
- lenguajes
- actividad
- coherencia profesional
- links externos

Imaginá tres visitantes:

1. recruiter
2. senior engineer
3. technical interviewer

¿Qué impresión tendría cada uno?

---

## 8. BRECHA PROFESIONAL

Compará:

**Perfil actual observado**
vs.
**Perfil profesional objetivo**

Evaluá las competencias relevantes para el rol indicado al principio.

Para cada competencia indicá:

- evidencia encontrada
- nivel de evidencia
- qué puedo demostrar hoy
- qué debería aprender
- qué proyecto podría demostrarlo
- prioridad

No confundas "aparece en mi stack" con "demuestro dominio".

---

## 9. NUEVOS PROYECTOS

Proponé al menos 8 ideas de productos que:

- resuelvan problemas concretos
- puedan ser desarrolladas por una persona
- tengan usuarios potenciales
- requieran ingeniería real
- puedan desplegarse
- permitan obtener feedback

No propongas automáticamente:

- todo lists
- calculadoras
- clones superficiales
- CRUDs genéricos

Para cada idea analizá:

- problema
- usuario
- hipótesis
- competencia
- diferenciación
- MVP
- arquitectura
- stack
- base de datos
- APIs
- infraestructura
- seguridad
- costos
- dificultad
- riesgos
- adquisición de usuarios
- métricas
- valor para entrevistas

Si la IA no aporta valor real, decilo.

---

## 10. ROADMAP

Después de la auditoría creá:

### 7 días
Limpieza y selección.

### 30 días
Mejoras de alto impacto + primer proyecto desplegado.

### 90 días
Uno o dos proyectos con:

- usuarios o feedback
- tests
- documentación
- CI/CD
- observabilidad
- decisiones técnicas documentadas

No asumas tiempo ilimitado.

Priorizá por:

**impacto × esfuerzo**

Separá imprescindible de opcional.

---

## 11. CALIDAD DEL ANÁLISIS

Diferenciá siempre:

- hechos observados
- inferencias
- hipótesis
- recomendaciones
- información no verificable

No inventes:

- usuarios
- tráfico
- métricas
- tests
- funcionalidades
- experiencia
- resultados

No confundas complejidad con calidad.

No confundas cantidad de tecnologías con criterio de ingeniería.

Si no podés acceder a un repositorio, indicá exactamente qué no pudiste verificar.

---

## RESULTADO FINAL

Entregá:

1. Resumen ejecutivo
2. Investigación y fuentes
3. Inventario de repositorios
4. Auditoría individual
5. Ranking
6. Auditoría del perfil
7. Brechas profesionales
8. Ideas de proyectos
9. Proyectos prioritarios
10. Arquitectura y roadmap
11. Estrategia de usuarios
12. Plan de 7/30/90 días
13. Preparación para entrevistas
14. Primeras 10 acciones concretas
