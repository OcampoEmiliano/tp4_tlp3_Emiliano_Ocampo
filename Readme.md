# TP4

Este README proporciona instrucciones paso a paso para ejecutar archivos Jupyter Notebook (extensión `.ipynb`).

## Requisitos Previos

Antes de comenzar, asegúrate de tener instalado:

1. **Python**: Versión 3.6 o superior recomendada
2. **Jupyter**: Ya sea Jupyter Notebook o JupyterLab

## Opciones para Ejecutar un Archivo .ipynb

### Opción 1: Usar Jupyter Notebook localmente

1. **Instalar Jupyter** (si aún no lo tienes):
   ```bash
   pip install notebook
   ```

2. **Navegar a la carpeta** donde se encuentra tu archivo `.ipynb`:
   ```bash
   cd ruta/a/tu/carpeta
   ```

3. **Iniciar Jupyter Notebook**:
   ```bash
   jupyter notebook
   ```

4. En el navegador que se abre automáticamente, haz clic en tu archivo `.ipynb` para abrirlo.

5. **Ejecutar las celdas** utilizando el botón "Run" o presionando `Shift + Enter` en cada celda.

### Opción 2: Usar JupyterLab

1. **Instalar JupyterLab** (si aún no lo tienes):
   ```bash
   pip install jupyterlab
   ```

2. **Iniciar JupyterLab**:
   ```bash
   jupyter lab
   ```

3. Navega hasta tu archivo y ábrelo haciendo doble clic.

### Opción 3: Usar Google Colab (en la nube)

1. Visita [Google Colab](https://colab.research.google.com/).

2. Selecciona "Archivo" > "Subir cuaderno" y sube tu archivo `.ipynb`.

3. Ejecuta las celdas con los botones de reproducción o usando `Shift + Enter`.


## Solución de Problemas Comunes

### El notebook no se abre
- Verifica que Jupyter esté correctamente instalado.
- Asegúrate de estar en el directorio correcto al iniciar Jupyter.

### Las celdas no se ejecutan
- Verifica que todas las dependencias requeridas estén instaladas.
- Reinicia el kernel: "Kernel" > "Restart & Clear Output".