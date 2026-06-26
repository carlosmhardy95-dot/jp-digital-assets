# JP Digital Assets — Blog técnico

Entrada de blog técnico publicada con **GitHub Pages**, sobre la migración del sitio de JP Digital Assets de un deploy por *arrastrar y soltar* a un flujo con **control de versiones**.

## 🔗 Entrada publicada
- **Sitio (GitHub Pages):** https://<usuario>.github.io/jp-digital-assets/  ← *reemplazá `<usuario>` por tu usuario real*

## 📄 Contenido
La entrada sigue la plantilla del trabajo:
1. **Contexto** — el sitio-catálogo de JP Digital Assets (HTML de un solo archivo, WhatsApp, filtros, lightbox).
2. **Problema** — publicar sin historial: un cambio rompió el filtro y los enlaces de WhatsApp, y no había forma de volver atrás.
3. **Acciones** — post-mortem constructivo + migración a Git/GitHub Pages, commits atómicos y correcciones.
4. **Aprendizajes** — el versionado como red de seguridad; separar "guardar" de "publicar".
5. **Reflexión** — feedback radicalmente sincero (radical candor) aplicado al post-mortem y al testing.

## 🧾 Evidencia de control de versiones
- Historial de commits: `../../commits/main`
- Pull Request del arreglo: `../../pull/1`

## 🛠️ Cómo se publica
El sitio es un único archivo `index.html` servido por GitHub Pages desde la rama `main`
(Settings → Pages → Branch: `main` / `/root`).

---
© 2026 JP Digital Assets — Santiago del Estero, Argentina
