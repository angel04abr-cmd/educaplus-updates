# EducaPlus: canal de actualizaciones

Este repositorio **no contiene código fuente**. Solo publica, en *Releases*, los instaladores de EducaPlus y el archivo `latest.json` que el programa usa para saber si hay una versión nueva.

- Cada versión trae `EducaPlus-X.Y.Z-setup.exe` y `latest.json`.
- `latest.json` lleva el tamaño, la huella SHA-256 y una **firma digital (Ed25519)** del instalador. El programa comprueba la firma antes de instalar y rechaza cualquier descarga que no coincida.
- Para actualizar, abra EducaPlus y use **Ayuda → Buscar actualización**.
