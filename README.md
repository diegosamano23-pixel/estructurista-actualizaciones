# Estructurista · actualizaciones

Canal de actualizaciones de **Estructurista**, la app de escritorio para ingeniería estructural (Windows).
Aquí sólo se publican los instaladores; el código de la app no está en este repositorio.

- **Instalar por primera vez:** descarga `Estructurista_<versión>_x64-setup.exe` de la
  [última versión](../../releases/latest). Windows puede avisar «editor desconocido» mientras el instalador no
  tenga firma de código.
- **Actualizar:** la app lo hace sola desde *Proyectos → Conexiones → Actualizaciones de la app*. Antes de
  instalar, verifica que el instalador esté firmado con la llave de Estructurista; si no coincide, lo rechaza.
- **Usar la app** requiere una cuenta.

Cada versión se publica con `latest.json` (versión, notas, fecha, firma y enlace de descarga), que es lo que
consulta la app. La rama `publicar` es un paso intermedio: el flujo `.github/workflows/publicar.yml` une el
instalador, comprueba su huella SHA-256 y crea la versión.
