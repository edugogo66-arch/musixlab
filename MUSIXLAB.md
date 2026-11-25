# MusixLab · Documento maestro

**Revisión documental:** 1.0 · **Fecha de referencia:** 25 de noviembre de 2026  
**Ámbito:** dirección general del laboratorio. Este documento distingue acuerdos, estado confirmado por el usuario, propuestas y tareas pendientes.

## 1. Propósito y criterios pedagógicos

MusixLab es una familia de aplicaciones musicales interactivas para comprender visual e intuitivamente la música, conectar teoría y práctica instrumental y favorecer la exploración activa. Se priorizan el rigor teórico, la sencillez, la utilidad didáctica y la coherencia entre aplicaciones. Evitar elementos superfluos y la memorización desprovista de comprensión. Los informes de aprendizaje deben traducir los resultados en recomendaciones comprensibles y ejercicios concretos.

## 2. Identidad visual común

Estética cálida, elegante y minimalista. Iconos propios con identidad gráfica familiar. Paleta adoptada:

| Uso | Color | HEX |
|---|---|---|
| Fondo | Marfil | `#FAF7F0` |
| Arena | Beige cálido | `#C6B69C` |
| Superficies secundarias | Arena clara | `#E9E0D0` |
| Texto | Marrón oscuro | `#302820` |

### Código cromático de grados (norma adoptada)

| Grado | Color | HEX |
|---|---|---|
| I | Rojo | `#D94B4B` |
| II | Naranja | `#E99738` |
| III | Amarillo | `#E4CA45` |
| IV | Verde | `#56A568` |
| V | Azul | `#438BD1` |
| VI | Violeta | `#9364C9` |
| VII | Rosa | `#D36B9D` |

El color identifica el grado relativo, nunca la nota absoluta. Mantenerlo en cualquier tonalidad, modo, tabla o diagrama. Elementos no seleccionados: tonos neutros. El sistema de colores para especies interválicas aún no está definido; deberá distinguir grado tonal de intervalo respecto de una fundamental y conservar la coherencia del sistema existente. Propuesta: complementar los colores con etiquetas para no depender exclusivamente de la percepción cromática.

### Logotipos e iconos

Conservar los diseños existentes de MusixLab, Fifther y FretTrainer como referencias. Pendiente inventariar archivos originales, variantes, dimensiones, iconos instalables y rutas. No se dispone aquí de los originales para reproducirlos con fidelidad.

## 3. Convenciones musicales

Nombres castellanos de las notas; cifrado americano para acordes; números romanos para grados; escritura enarmónica correcta según el contexto; distinción rigurosa entre número y especie de intervalo, tónica y fundamental. Mantener estas convenciones en textos, mapas, ejercicios y tablas.

## 4. Inventario de aplicaciones

| Aplicación | Versión confirmada | Estado al 25/11/2026 |
|---|---|---|
| MusixLab (portal) | 1.2 | Publicado, operativo e instalado en Dock de Mac e iPhone |
| Fifther | 2.0 | Operativo; pruebas satisfactorias en Mac e iPhone |
| FretTrainer | No registrada | Operativo; mejoras de evaluación verificadas por el usuario |
| Mapa interválico (nombre provisional) | Sin versión | Conceptualización; no implementado |

### 4.1. Portal MusixLab

Punto central de acceso a las aplicaciones. Conservar su identidad visual y su instalación como aplicación independiente. El usuario confirma su funcionamiento en Mac e iPhone. Cada incorporación futura deberá incluir acceso, icono, descripción y comprobación de enlaces y comportamiento móvil. No se ha auditado el código del portal en esta sesión.

### 4.2. Fifther

**Consolidado:** círculo de quintas tridimensional, exploración de relaciones tonales y armónicas, biblioteca de 32 progresiones armónicas, presentación adaptada a Mac e iPhone. Versión 2.0 confirmada por el usuario.

**Pendiente (no implementado según el estado comunicado):** optimización visual; canciones de referencia; reproducción sonora; inversiones de acordes; conducción de voces; reharmonización. No atribuir estas funciones a la versión 2.0.

### 4.3. FretTrainer

**Consolidado:** aprendizaje de notas del diapasón, mapa del mástil, configuración de hasta 24 trastes, preguntas de entrenamiento, evaluación, informes personalizados, recomendaciones verbales y ejercicios de mejora. En el chat de desarrollo se corrigió un problema de evaluación que aparecía incluso sin respuestas incorrectas y se confirmó el funcionamiento de la sección de informes. El usuario confirmó también la aparición en el Dock.

**Pendiente de documentar:** versión exacta, inventario de archivos, cobertura de pruebas y configuración efectiva de instrumentos. No hay una nueva funcionalidad comprometida en la hoja de ruta actual.

### 4.4. Nueva aplicación: mapa interválico

Objetivo: mostrar la geometría de las relaciones interválicas en guitarra y bajo desde cualquier fundamental del diapasón. Funciones previstas: seleccionar una fundamental y una región del mástil; visualizar intervalos con código cromático permanente; explorar tríadas, acordes de cuatro notas y extensiones. Todo está pendiente de diseño o implementación.

Decisiones abiertas: nombre, icono, sistema cromático para especies interválicas, representación de equivalencias enarmónicas y extensiones, afinaciones y número de cuerdas admitidos, límites de región y controles de selección. No fijar estos detalles sin trabajarlos en el chat propio.

Complementariedad: FretTrainer responde a «¿qué nota estoy tocando?»; Fifther a «¿cómo se relaciona armónicamente?»; el mapa interválico a «¿dónde encuentro esa relación en el instrumento?».

## 5. Tecnología, GitHub y publicación

Acuerdos: aplicaciones PWA con HTML, CSS y JavaScript; publicación mediante GitHub Pages; adaptación a móviles, tabletas y ordenadores; instalación y funcionamiento sin conexión como objetivos comunes. Entregar paquetes completos, conservar funcionalidades previas, controlar versiones y caché y verificar funcionamiento.

### Registro de direcciones

| Aplicación | Repositorio GitHub | URL GitHub Pages |
|---|---|---|
| MusixLab | Pendiente de recuperar | Pendiente de recuperar |
| Fifther | Pendiente de recuperar | Pendiente de recuperar |
| FretTrainer | Pendiente de recuperar | Pendiente de recuperar |
| Mapa interválico | No creado o no documentado | No publicada |

Las direcciones exactas, el propietario de los repositorios y la estructura de publicación no aparecen en el contexto recuperado. No se inventan enlaces ni se presupone que exista un repositorio independiente por aplicación. Completar este registro con las direcciones reales y verificar las páginas publicadas. Inventariar rama y carpeta de publicación, archivos de entrada, manifiestos, service workers, iconos y dependencias. No se ha accedido ni modificado GitHub en esta sesión.

## 6. Versionado, pruebas y mantenimiento

Mantener la numeración vigente. Propuesta pendiente de ratificación: versionado semántico MAYOR.MENOR.PARCHE (cambios incompatibles o sustanciales, ampliaciones compatibles y correcciones, respectivamente). No renumerar retrospectivamente las versiones actuales.

Procedimiento recomendado para cada entrega:

1. Registrar alcance, versión de partida y cambios previstos.
2. Conservar una copia o referencia de la última versión estable.
3. Preparar el paquete completo; revisar manifiesto, iconos, rutas y service worker cuando corresponda.
4. Actualizar identificadores de versión y caché cuando proceda; comprobar que la actualización no deja recursos obsoletos.
5. Probar funciones nuevas y anteriores, diseño adaptable, instalación y funcionamiento sin conexión; distinguir pruebas realizadas de las pendientes. Priorizar Mac e iPhone como dispositivos ya utilizados.
6. Publicar y verificar la URL real; actualizar el portal si procede.
7. Registrar versión, cambios, pruebas, incidencias y siguiente paso en este documento maestro.

No considerar una función implementada por el mero hecho de haberla diseñado. No considerar verificado un comportamiento que no se ha probado.

## 7. Organización y continuidad

Un chat por aplicación. Dirección general centraliza identidad, teoría, normas técnicas, portal, documentación, versiones y hoja de ruta. Chats existentes: Fifther y FretTrainer. Este chat es «00 · MusixLab – Dirección general». Crear un chat específico para el mapa interválico cuando comience su desarrollo; numeración 01/02/03 propuesta, no requisito técnico.

Este archivo `MUSIXLAB.md` será la referencia de continuidad. Propuesta: conservarlo en la raíz del repositorio general o junto a la documentación principal del portal, una vez identificada su estructura real. No es imprescindible dividirlo todavía. Si crece, separar `DESIGN.md`, `CHANGELOG.md` y `ROADMAP.md`; `README.md` para la presentación pública. Estas ubicaciones son propuestas, no archivos ya creados en GitHub.

Después de cada avance importante, actualizar la revisión documental, fecha, versiones, funciones comprobadas, tareas pendientes, decisiones y punto de recuperación. Incorporar las novedades procedentes de los chats particulares. En cada nueva sesión, utilizar la copia vigente del documento y contrastarla con el estado del código cuando sea necesario. La actualización requiere una intervención en una sesión o una edición explícita del archivo; no se realiza automáticamente entre chats.

## 8. Hoja de ruta general

| Línea | Prioridad propuesta | Resultado esperado | Estado |
|---|---|---|---|
| Inventario GitHub, URLs y versiones | Alta | Registro verificable de publicación | Pendiente |
| Inventario de iconos y logotipos | Alta | Referencias gráficas reutilizables | Pendiente |
| Consolidar documentación y mantenimiento del portal | Alta | Documento maestro accesible y enlaces comprobados | Documento creado localmente; publicación pendiente |
| Definir mapa interválico | Alta | Especificación pedagógica, musical, visual y funcional | Conceptualización |
| Fifther: optimización visual | Por acordar | Mejor legibilidad y usabilidad | Pendiente |
| Fifther: canciones de referencia | Por acordar | Vincular progresiones con repertorio | Pendiente |
| Fifther: reproducción sonora | Por acordar | Escuchar relaciones y progresiones | Pendiente |
| Fifther: inversiones | Por acordar | Explorar disposiciones de acordes | Pendiente |
| Fifther: conducción de voces | Por acordar | Comprender enlaces entre acordes | Pendiente |
| Fifther: reharmonización | Por acordar | Explorar alternativas armónicas | Pendiente |
| FretTrainer | Mantenimiento | Preservar entrenamiento e informes | Operativo |

El orden de las seis mejoras de Fifther recoge la secuencia propuesta en dirección general, no un calendario vinculante. No existen fechas de entrega acordadas.

## 9. Registro de decisiones

| ID | Decisión | Estado |
|---|---|---|
| D001 | Dirección general centralizada | Adoptada |
| D002 | Chat propio por aplicación | Adoptada |
| D003 | Paleta cálida y minimalista común | Adoptada |
| D004 | Colores permanentes de los siete grados | Adoptada |
| D005 | PWA, HTML/CSS/JS, GitHub Pages | Adoptada |
| D006 | Conservar funcionalidades, entregar paquetes completos y controlar caché | Adoptada |
| D007 | Documento maestro actualizado tras avances importantes | Adoptada |
| D008 | Versionado semántico de tres componentes | Propuesta |
| D009 | Código cromático de especies interválicas | Pendiente |
| D010 | Inventario de repositorios, URLs e iconos | Pendiente |
| D011 | Documentación modular y ubicación en repositorio general | Propuesta |
| D012 | Prioridades de la hoja de ruta y protocolo de entrega detallado | Propuesta |

## 10. Historial y punto de recuperación

**Rev. 1.0 · 25/11/2026:** consolidación del estado comunicado por el usuario y de los acuerdos disponibles de dirección general, Fifther y FretTrainer. Creación de este archivo Markdown, sin cambios en repositorios.

**Última situación conocida:** portal 1.2 estable según pruebas del usuario; Fifther 2.0 estable según pruebas del usuario; FretTrainer operativo, versión exacta pendiente; mapa interválico por diseñar.

**Siguiente paso recomendado:** incorporar las URLs reales de GitHub y GitHub Pages, registrar la versión exacta de FretTrainer y conservar los iconos originales. A continuación, iniciar la especificación del mapa interválico o retomar las mejoras de Fifther según se decida.

**Ficha para futuras revisiones:** fecha y revisión documental; aplicación y versión; cambios confirmados; pruebas realizadas y pendientes; decisiones generales; errores abiertos; enlaces o referencia de entrega; siguiente paso.

---
**Principio rector:** cada elemento visual debe tener una razón musical y cada interacción una finalidad didáctica.
