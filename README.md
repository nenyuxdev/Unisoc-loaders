# Unisoc (Spreadtrum) FDL Binaries Repository

Una colección modular y verificada de binarios de cargadores de arranque (`FDL1` y `FDL2`) organizados por familia de SoC para el mantenimiento y flasheo de dispositivos Unisoc/Spreadtrum.

## 📂 Estructura del Repositorio

Los binarios están categorizados estrictamente según su arquitectura de SoC para evitar errores de incompatibilidad al flashear:

* **`SC7731E/`** - Cargadores para dispositivos de gama de entrada con SC7731E.
* **`SC9832E/`** - Cargadores para arquitectura SC9832E.
* **`SC9863A_32/`** - Cargadores para implementaciones de 32 bits de SC9863A.
* **`SC9863A_64/`** - Cargadores para implementaciones de 64 bits de SC9863A.
* **`T310/`** - Cargadores para Tiger T310.
* **`T606/`** - Cargadores para Tiger T606.
* **`T612/`** - Cargadores para Tiger T612.
* **`T616/`** - Cargadores para Tiger T616.
* **`T618/`** - Cargadores para Tiger T618.

## ⚠️ Notas Técnicas Importantes

* **Compatibilidad por SoC:** Los archivos FDL son universales por cada familia de procesador y funcionan de manera independiente de la marca o modelo del teléfono. Asegúrate siempre de usar el cargador correspondiente al procesador exacto.
* **Separación de Firmwares:** Los paquetes de firmware completos (`.pac`) son estrictamente específicos para cada modelo de dispositivo. Nunca cruces firmwares completos entre distintas marcas, incluso si comparten la misma familia de SoC.

## 🛠️ Herramientas Recomendadas

* **ResearchDownload** / **FactoryDownload** (Herramientas oficiales de flasheo para Windows en dispositivos Unisoc).
* **Scripts de Python / alternativas de bajo nivel** para flujos de trabajo personalizados.
