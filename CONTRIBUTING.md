# Cómo aportar proyectos

Puedes compartir tu proyecto en el grupo de Facebook, agregarlo al [directorio](PROYECTOS.md) de este repositorio, o ambas cosas. Los requisitos son los mismos.

## Qué proyectos se aceptan

Proyectos relacionados con Claude Code o con IA y programación ([regla 3](REGLAS.md#3-temática)):

- Skills, subagentes, hooks, plugins y servidores MCP.
- Plantillas y configuraciones.
- Aplicaciones y ejemplos hechos con Claude Code.
- Cursos, guías y material para aprender.

## Requisitos

### Autoría y licencia

- Es tu proyecto, o nombras a su autor original y enlazas su fuente ([regla 7](REGLAS.md#7-autoría)).
- Un fork explica qué cambia respecto al original.
- El repositorio tiene una licencia declarada.

### Calidad

- El proyecto funciona y el README explica cómo instalarlo y usarlo.
- La descripción que envías está en español. El código y su documentación pueden estar en inglés ([regla 6](REGLAS.md#6-idioma)).
- Si es de pago o freemium, lo indicas. Un enlace de afiliado debe declararse en el grupo y no se acepta en el directorio.

### Seguridad

Los componentes de Claude Code pueden ejecutar comandos y acceder a tus archivos, así que exigimos transparencia:

- El código fuente es público y legible, sin partes ofuscadas.
- No incluye API keys, tokens ni otros secretos.
- Un ejecutable o comprimido (`.apk`, `.exe`, `.zip`) solo se acepta junto con su código fuente.
- Un hook, plugin o servidor MCP explica en su README qué comandos ejecuta, a qué archivos accede y a qué servicios externos se conecta.
- Si recopila datos o telemetría, lo declara y explica cómo desactivarlo.
- Una instalación con `curl | bash` enlaza el script para que se pueda leer antes de ejecutarlo.

## Qué no se acepta

- Software pirata, o herramientas para vender, compartir o revender cuentas de Claude ([regla 4](REGLAS.md#4-legalidad)).
- Herramientas para saltarse los límites de uso o los términos de servicio de un proveedor.
- Malware, o código que robe credenciales o datos.
- Proyectos ajenos presentados como propios.
- Enlaces a otras comunidades ([regla 5](REGLAS.md#5-comunidad-única)).

## Compartirlo en el grupo

Publica el contenido en el grupo, no solo el enlace ([regla 8](REGLAS.md#8-spam)):

```text
Nombre del proyecto:
Qué problema resuelve:
Cómo se usa (un ejemplo o una captura):
Qué aprendí construyéndolo:
Repositorio:
Licencia y precio:
```

Una publicación por proyecto. Vuelve a publicar solo cuando haya una versión con cambios importantes, y cuenta qué cambió.

## Agregarlo al directorio

1. Haz un fork de este repositorio.
2. Agrega una sola línea al final de la categoría que corresponda en [PROYECTOS.md](PROYECTOS.md):

   ```markdown
   - **[Nombre](https://github.com/usuario/repo)** de [@usuario](https://github.com/usuario): qué hace, en una frase. `Licencia` · `Gratis`
   ```

   Usa `Gratis`, `Freemium` o `De pago` según el caso.
3. Abre un pull request con un proyecto por PR y copia esta lista en la descripción:

   ```markdown
   - [ ] Es mi proyecto, o nombro a su autor original.
   - [ ] El repositorio tiene licencia y su README explica cómo instalarlo y usarlo.
   - [ ] El código es público y no incluye secretos.
   - [ ] Si ejecuta comandos o se conecta a servicios externos, el README lo explica.
   - [ ] Indiqué si es gratis, freemium o de pago.
   ```

¿Nunca has hecho un pull request? Pídeselo a Claude Code desde tu fork:

```text
Lee CONTRIBUTING.md, agrega mi proyecto <URL> a PROYECTOS.md con el formato indicado y abre un pull request con la lista de verificación.
```

## Revisión

Un moderador revisa cada propuesta y puede pedir cambios o rechazarla. Estar en el directorio significa que el proyecto cumplió estos requisitos al revisarlo, no que la comunidad garantice su seguridad. Lee el código antes de instalarlo.

Un proyecto se retira del directorio si su enlace deja de funcionar, si deja de cumplir estos requisitos o si se detecta un problema de seguridad. Para avisar de uno, abre un [issue](https://github.com/davila7/claude-code-en-espa-ol/issues).
