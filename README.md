# Arquitectura Web SEO

Skill de Diego González para ayudar a diseñar o revisar la organización de una web: jerarquía de páginas, categorías, navegación y criterios técnicos para su implementación.

Está dirigido a consultores SEO, responsables de contenido y equipos que preparan una web o un rediseño. Es un conjunto de instrucciones para IA; este repositorio no incluye un crawler ni un programa que modifique tu sitio.

## Uso como skill en Claude Code

Descarga este repositorio desde **Code > Download ZIP**, descomprímelo y renombra la carpeta a `arquitectura-web-seo`. Conserva todos sus archivos. Colócala dentro de `.claude/skills/` de tu proyecto. La ruta final debe ser:

```text
.claude/skills/arquitectura-web-seo/SKILL.md
```

Para disponer del skill en todos tus proyectos locales, usa `~/.claude/skills/arquitectura-web-seo/` (en Windows, dentro de tu carpeta de usuario). No sobrescribas otra versión sin guardar sus cambios.

Abre Claude Code en el proyecto e invócalo con `/arquitectura-web-seo`, seguido de tu solicitud. Si no aparece, comprueba el nombre de la carpeta y que no haya una carpeta adicional entre ella y SKILL.md.

Esta instalación está documentada para Claude Code. Otros clientes compatibles con Agent Skills pueden requerir otra ubicación o un mecanismo de importación. No basta con pegar la URL de GitHub para instalarlo.

Referencia: [documentación oficial de skills de Claude Code](https://code.claude.com/docs/en/skills).

## Información que debes aportar

- Si es un proyecto nuevo, una auditoría de estructura o un rediseño.
- Tipo de web y cantidad aproximada de URLs.
- Productos o servicios y objetivos comerciales.
- Público, país e idioma.
- Keyword research disponible, indicando su fuente y fecha.
- Para rediseños: inventario de URLs actuales y datos disponibles de tráfico y enlaces.

Si falta información, el asistente debe preguntarla o marcar la limitación. No necesita Python ni una API concreta para leer el skill. Investigar y rastrear requiere herramientas adicionales disponibles en tu entorno.

## Ejemplo de solicitud

> Usa arquitectura-web-seo para revisar una web de servicios en Colombia. Adjunto inventario de URLs y keyword research. Mi objetivo es captar solicitudes comerciales. Antes de proponer nuevas páginas, identifica información faltante y posibles solapamientos de intención. Devuelve una estructura de URLs y un mapa de redirecciones propuesto, sin aplicarlo.

## Resultado esperado

El skill pide seis apartados: resumen estratégico, árbol de URLs, revisión de canibalización, plan de enlazado general, directrices técnicas y organización semántica. Son propuestas para revisar con el equipo, no cambios ejecutados ni resultados garantizados.

Para elaborar pares de enlaces y textos de anclaje concretos a partir de un inventario, puedes continuar con [Interlinking Builder](https://github.com/diego-seo/interlinking-builder). Se instala por separado.

## Cómo revisar la propuesta

Comprueba que las páginas responden a necesidades reales, que no se inventan volúmenes y que cada decisión tiene una explicación. Valida con resultados de búsqueda y datos del negocio los posibles solapamientos: compartir palabras no demuestra por sí solo canibalización.

En un rediseño, revisa las redirecciones una por una y comprueba su destino antes de implementarlas. No apliques cambios en robots.txt, canonical o filtros automáticamente: requieren un diagnóstico del sitio.

## Límites del recurso

La regla de tres clics del SKILL.md debe interpretarse como orientación de navegación, no como un límite oficial de Google. El tipo de arquitectura depende del proyecto; los enlaces cruzados relevantes pueden ser útiles.

La propuesta de datos estructurados debe representar contenido visible y verificable. Ni el marcado ni una arquitectura concreta garantizan citas en asistentes de IA, indexación o posiciones.

El repositorio no incluye investigación de palabras clave, acceso a Search Console ni métricas propias. El asistente solo podrá verificarlas si recibe datos o dispone de las herramientas correspondientes. Su salida necesita revisión humana.

## Privacidad, actualización y soporte

Comparte únicamente los datos necesarios y anonimiza información sensible. Las condiciones del asistente que utilices se aplican a los archivos que le entregues.

Para actualizar una instalación manual, descarga la nueva versión y compara los archivos antes de reemplazarlos si hiciste personalizaciones. Para reportar problemas, abre un issue con un ejemplo sin información privada.

## Licencia

[MIT](LICENSE). Uso, modificación y redistribución permitidos, incluso comercialmente, conservando aviso de autoría y licencia. Sin garantías.
