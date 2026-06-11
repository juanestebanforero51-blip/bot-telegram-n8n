Bot de Telegram con Automatización en n8n

Descripción
Este proyecto consiste en un flujo de trabajo automatizado e independiente desarrollado en n8n. El sistema funciona como un bot conversacional de Telegram estructurado para la captura, procesamiento y registro automatizado de metadatos en tiempo real directamente hacia bases de datos en Google Sheets.

Tecnologías y Herramientas
- n8n: Diseño y ejecución de la lógica del flujo de trabajo (Workflow asincrónico).
- Telegram Bot API: Interfaz de usuario y recepción de comandos/mensajes.
- Google Sheets API: Almacenamiento, ordenamiento y persistencia de los datos capturados.
- JSON: Estructura de intercambio de datos entre nodos.

Cómo utilizar este flujo
1. Descarga el archivo `.json` presente en este repositorio.
2. Abre tu instancia de n8n.
3. Crea un nuevo flujo de trabajo, ve al menú de opciones (...) y selecciona "Import from file".
4. Selecciona el archivo JSON descargado y configura tus propias credenciales de Telegram y Google Sheets en los nodos correspondientes.
