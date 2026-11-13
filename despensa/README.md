# 🧺 Mi Despensa

Inventario de la casa con escáner de código de barras. Funciona en el navegador del celular,
**sin instalar nada, sin cuentas y sin base de datos**: todo queda guardado en el propio teléfono.

## Qué hace

- **Escanear** con la cámara (EAN-13, EAN-8, UPC, Code 128, QR) o leer el código desde una foto.
- Busca el producto automáticamente en Open Food Facts / Open Beauty Facts / Open Products Facts
  (nombre, marca, contenido y foto). Si no aparece, lo escribes a mano.
- Movimientos de **Entrada**, **Salida** y **Conteo**, con "Deshacer".
- **Escaneo rápido**: productos ya registrados suman o restan 1 sin abrir la ficha.
- **Inventario** por ubicación (despensa, refrigerador, baño…), búsqueda y orden.
- **Lista de compras** automática con lo agotado o bajo el mínimo; se copia para WhatsApp.
- **Historial** por día, exportación a CSV (abre en Excel), respaldo y restauración en JSON.
- Productos sin código (fruta, verdura, granel) y datos de ejemplo para probar.

## Publicarla (GitHub Pages)

1. En GitHub: repositorio → **Settings** → **Pages**.
2. *Source*: **Deploy from a branch** → Branch **main**, carpeta **/ (root)** → **Save**.
3. En 1–2 minutos queda en:
   **https://carlosandrescasanovachavez-hash.github.io/your-ruta/despensa/**

La cámara solo funciona con `https://` (por eso hay que publicarla; abriendo el archivo directo
se puede escribir el código a mano o usar “Foto”).

**Tip:** en el navegador usa *“Agregar a pantalla de inicio”* para tenerla como una app.
