# AGENTS.md

## Estado actual

Este repositorio es una **plantilla vacía para un proyecto nuevo de Spring Boot**. No hay archivo de fuente, configuraciones de build ni archivos de instrucciones. Cualquier agente debe primero configurar la estructura del proyecto antes de intentar ejecutar o probar código.

## Configuración

- **Build:** Spring Boot con Maven (`pom.xml`) o Gradle (`build.gradle`).
- **Skills existentes** en `.opencode/skills/`: `commit`, `gh-cli`, `java-springboot`, `web-design-guidelines`.
- **Comandos** en `.opencode/commands/README.md`.
- **Formateo de editor:** `.editorconfig` configura indentación de 2 espacios, UTF-8, sin tabs.
- **Configuración OpenCode:** `opencode.json` con formatter habilitado y modelo por defecto.
- No existe `CLAUDE.md`, `.cursorrules` ni otros archivos de instrucciones.
- El proyecto necesita ser inicializado con dependencias y estructura de paquetes antes de desarrollo.

## Directrices

- Todas las respuestas deben estar en **español**.
- Responder de forma **corta y concisa**, sin información redundante.
- El flujo de trabajo está guiado por **OpenSpec**.

## Working in This Repo

- Confirmar la estructura del proyecto y la herramienta de build antes de ejecutar cualquier comando — ninguno está configurado aún.
- Una vez inicializado, revisar `AGENTS.md`, `opencode.json`, `.editorconfig` y la configuración de CI para obtener guía específica del proyecto.
- Este archivo debe actualizarse a medida que el proyecto tome forma para capturar comandos, notas de arquitectura y convenciones.
