# Proyecto de Análisis de Sentimientos - Parte 5

¡Hola! Quiero compartir la quinta parte del proyecto de Análisis de Sentimientos que mi equipo desarrolló dentro del programa de BIGDATA.

**Título del Post:** Policías podrán retener a civiles hasta por 4 horas si no tienen DNI

**Descripción:** Intervendrán a quienes vean sospechosos y no será necesaria la presencia de un juez o fiscal, según decreto.

![Enlace al tweet](https://twitter.com/larepublica_pe/status/1710265041004495208)

## Proceso:

1. **WEB SCRAPING:** Obtuvimos datos de Twitter.

2. **ETL (PANDAS - PYTHON):** Procesamos y limpiamos los datos.

3. **ANÁLISIS DE SENTIMIENTOS:** Utilizamos TRANSFORMERs - BERT.

4. **DATA VISUALIZACIÓN:** Aplicamos Matplotlib.

5. **DATA VISUALIZACIÓN:** Utilizamos POWER BI (Este post).

En la primera imagen, se aprecia el Dashboard en Power BI, dividido en tres bloques:

### 1er Bloque: 
Visualización general de los datos del post según la clasificación de sentimientos.

### 2do Bloque: 
Línea de tendencia de interacciones con el post por días. Además, lista de comentarios del análisis que nos permite seleccionar para un análisis más profundo en el 3er bloque.

### 3er Bloque: 
Resumen del comentario con Usuario, Fecha y hora, Cantidad de seguidores, Respuestas, Likes, Sentimiento y Contenido del comentario.

Adicionalmente, creamos otra página en el dashboard para profundizar en el análisis de la información. Se agregó el comentario que generó más interacciones, con más likes y el comentario con mayor alcance.

## Conclusión (Visualización de Resultados):

Esta información, junto con sus indicadores (1° página), puede ayudar a analizar ciertos insights ocultos (2° página), que facilitan la moderación de publicaciones y logran mejores interacciones y alcances a la audiencia. Además, es posible obtener un perfil del tipo de usuario que realiza más interacciones.
