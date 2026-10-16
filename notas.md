# Notas sobre ramas en Git

Una rama permite trabajar en un cambio sin afectar la rama principal (main). Cuando el trabajo está listo, se integra a main mediante un pull request o un merge.

Comandos equivalentes en la terminal:

```bash
git checkout -b feature-eduardo
git add README.md notas.md
git commit -m "Mensaje claro del cambio"
git push origin feature-eduardo
```

Un buen mensaje de commit describe en pocas palabras qué cambió, en modo imperativo, por ejemplo: Agrega objetivo y autor al README.

---

### Nota sobre el uso de IA

Esta práctica se realizó con apoyo de un asistente de inteligencia artificial (Claude, de Anthropic), que, a petición del autor, creó el repositorio, la rama y los commits desde el navegador y redactó el contenido de los archivos. El autor definió los nombres, revisó y aprobó cada paso.

Eduardo Bustos
