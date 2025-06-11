# Cuidados de Amelia - Versión DEMO

Esta es una versión DEMO de la app Cuidados de Amelia, la cual creé para registrar los cuidados de mi bebé prematura y visualizar métricas e históricos en tiempo real.

En esta versión de demostración, los registros se almacenan en una hoja de cálculo de prueba y no afectan la base de datos original.

## Cómo puedes usar esta app

1. Crea un repositorio en GitHub y sube estos archivos.
2. Ve a [Streamlit Cloud](https://streamlit.io/cloud) y haz clic en "New app".
3. Conecta tu repo y rama principal.
4. En la sección "Secrets", crea una variable llamada `GOOGLE_SHEETS_CREDENTIALS` y pega el contenido del archivo `credenciales.json`.
5. Da clic en **Deploy**.

Tu app quedará publicada en una URL como: `https://tuusuario.streamlit.app`

## Funcionalidades de la app

- Formulario para registrar cuidados, con campos adaptativos según el tipo de evento (toma de leche, puenteo, extracción, seno materno, etc.)
- Tablero con las últimas métricas, actualizado en tiempo real:
  
  * Alimentación: volumen de leche consumida, calorías, porcentaje de leche materna, duración de seno materno, etc.
  
  * Digestión: volumen puenteado, evacuaciones, tiempos desde último cambio y vaciamiento.
  
- Gráficos históricos con media móvil para visualizar tendencias (consumo de calorías y extracción de leche).
