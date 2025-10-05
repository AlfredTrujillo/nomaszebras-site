# Nomaszebras

Copia del proyecto local `nomaszebras` — sitio estático con ejemplos de tipografías y testers.

Contenido incluido:
- `index.html` — página principal
- `styles.css` — estilos
- `fonts/` — fuentes usadas (Calgary88, SuperChango94)
- `assets/` — logo SVG
- `scripts/` — helper para generar `woff2` desde OTF

Cómo probar localmente

1. Servir la carpeta por un servidor estático (por ejemplo con VS Code Live Server o `python -m http.server`):

```bash
# desde la raíz del proyecto
python3 -m http.server 5500
# luego abre http://127.0.0.1:5500
```

2. Si ves mensajes sobre font sanitizer, regenera `fonts/Calgary88.woff2` con `woff2_compress` o usa el script `scripts/build-fonts.sh`.

Licencia

MIT — ver `LICENSE`.
