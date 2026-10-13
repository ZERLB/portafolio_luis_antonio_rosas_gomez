# Portafolio · Luis Antonio Rosas Gómez

> Ingeniero en Sistemas Computacionales · Full Stack · Infraestructura · Ciudad de México

<div align="center">

[![Sitio en vivo](https://img.shields.io/website?down_color=red&down_message=fuera%20de%20l%C3%ADnea&label=Sitio%20en%20vivo&up_color=22d3ee&up_message=en%20l%C3%ADnea&url=https%3A%2F%2Fzerlb.github.io%2Fportafolio_luis_antonio_rosas_gomez%2F)](https://zerlb.github.io/portafolio_luis_antonio_rosas_gomez/)
[![Perfil de GitHub](https://img.shields.io/badge/GitHub-ZERLB-181717?logo=github&logoColor=white)](https://github.com/ZERLB)
[![Correo](https://img.shields.io/badge/Correo-luisrosasgom%40gmail.com-EA4335?logo=gmail&logoColor=white)](mailto:luisrosasgom@gmail.com)

**[🌐 Abrir el portafolio](https://zerlb.github.io/portafolio_luis_antonio_rosas_gomez/)** · [English version](https://zerlb.github.io/portafolio_luis_antonio_rosas_gomez/?lang=en)

</div>

## Qué hay dentro

Una sola página que cuenta lo que hago y lo que opero, con datos del inventario real de octubre de 2026:

- **Sobre mí y datos rápidos.** Rol, enfoque, idiomas y lo que estoy usando ahora.
- **Infraestructura en producción.** Mapa SVG de la topología de la Universidad de la Salud: dos HAProxy, aplicaciones Node y PHP, tres Moodle y Canvas, Koha y DSpace, capa de datos MySQL / MariaDB / PostgreSQL / Redis, respaldos nocturnos, NAS, pool XCP-ng y malla Tailscale. Con cifras: 27 servidores, 18 VMs, 8 bases respaldadas cada noche, 16 URL vigiladas.
- **Stack por capas.** Lenguajes, backend, frontend, bases de datos, servidores y virtualización, redes y seguridad, plataformas, IA y flujo de entrega.
- **Proyectos.** Savitar (mi centro de operación), SIGU, NEXUS v2, campos clínicos, reactivos, asistente virtual con voz, 100 UNISOS dijeron, Nobel, clínica universitaria, cursos de inglés, suite DTE, Mente (plugin de Claude Code), pool XCP-ng, respaldos, migración MySQL 8.4, aulas virtuales, red y perímetro, un juego en Godot y este sitio. Donde existe una página pública de entrada, está enlazada.
- **Experiencia, certificaciones y método de trabajo.**
- **Contacto.** Correo, teléfono y un formulario que abre tu cliente de correo con el mensaje listo; no guarda nada en ningún servidor.

## Cómo está hecho

| | |
|---|---|
| **Un solo archivo** | `index.html` con CSS y JavaScript incrustados. Sin frameworks, sin dependencias de compilación, sin rastreadores. |
| **Temas** | Claro y oscuro. Sigue la preferencia del sistema y recuerda la elección. |
| **Idiomas** | Español por defecto e inglés con un botón (o `?lang=en`). Los textos viven en un diccionario dentro de la página. |
| **Íconos** | Incrustados como símbolos SVG (de [Simple Icons](https://simpleicons.org/), CC0), para que la página cargue completa aunque no haya internet hacia terceros. |
| **Mapa de infraestructura** | SVG propio, con flujo animado y respeto a `prefers-reduced-motion`. |
| **Accesibilidad** | Enlace para saltar al contenido, foco visible, etiquetas ARIA en controles y contraste revisado en los dos temas. |
| **Pruebas** | Antes de publicar, la página se recorre con Chrome for Testing sin ventana (escritorio, móvil, tema claro, inglés y filtros) y se revisan las capturas una por una: 0 errores de JavaScript, 0 peticiones fallidas. |

## Verlo en local

No necesita instalar nada:

```sh
git clone https://github.com/ZERLB/portafolio_luis_antonio_rosas_gomez.git
cd portafolio_luis_antonio_rosas_gomez
python3 -m http.server 8080
# abrir http://127.0.0.1:8080/
```

También basta con abrir `index.html` en el navegador.

## Dónde se publica

- **GitHub Pages**, desde la rama `main`: <https://zerlb.github.io/portafolio_luis_antonio_rosas_gomez/>
- Una copia en mi propio servidor, que se actualiza con `git pull` después de cada publicación.

---

<div align="center">
<sub>© 2026 Luis Antonio Rosas Gómez · <a href="https://github.com/ZERLB">ZERLB</a> · Hecho a mano con HTML, CSS y JavaScript.</sub>
</div>
