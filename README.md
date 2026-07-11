# Análisis de Patrones de Movilidad e Inclusión en ECOBICI CDMX

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/15OR4YtvMQKKXtJwtq-tGVwcAqZwvpb9u#scrollTo=fV2BS56OH6fo&uniqifier=4)

##  Descripción del Proyecto
Este proyecto realiza un Análisis Exploratorio de Datos (EDA) y una limpieza profunda sobre el histórico de viajes del sistema ECOBICI en la Ciudad de México durante enero de 2026. El análisis transforma los datos en información estratégica y accionable, evaluando cómo interactúan los ciclos de demanda temporal y la saturación de estaciones con el perfil sociodemográfico de las y los usuarios.

---

##  Tecnologías Utilizadas
* **Lenguaje:** Python
* **Librerías principales:** Pandas (Limpieza y manipulación de datos), NumPy (Operaciones vectoriales).
* **Entorno:** Google Colab
  
---

##  Hallazgos Clave del Análisis

* **La Brecha de Género:** Existe una marcada disparidad en el uso del sistema; el 67.5% de los trayectos son realizados por hombres frente al 27.4% por mujeres. 
* **Patrón de Uso Laboral:** Descontando los registros atípicos aislados (usuarios de 90 a 100 años), el volumen principal de viajes se concentra firmemente en adultos jóvenes durante los horarios pico de lunes a viernes (08:00 AM y 06:00 PM).
* **Comportamiento Asimétrico:** El pico de demanda de la tarde (06:00 PM) es más masivo y síncrono que el matutino, lo que genera cuellos de botella críticos en las estaciones de retorno.
* **Cambio de Dinámica en Fin de Semana:** Los sábados y domingos la estructura bimodal desaparece por completo, transformándose en una curva suave de uso recreativo y comercial centrada entre las 11:00 AM y 03:00 PM.

---

##  Propuestas de Solución Basadas en Datos

### 1. Optimización Operativa (Rutas de Balanceo)
Los camiones repartidores de bicicletas no deben operar de forma simétrica todo el día. El sistema debe inyectar unidades con mayor intensidad por la tarde en las zonas corporativas, anticipando la saturación de anclajes debido al regreso masivo de usuarios.

### 2. Infraestructura Vial con Perspectiva de Género
Para mitigar la brecha del 67.5% vs 27.4%, se fundamenta la necesidad urgente de construir ciclovías completamente segregadas y cruces mejor iluminados en avenidas principales. Estudios del ITDP y el BID explican que la falta de protección física frente a los autos es la razón principal por la que las mujeres y los adultos mayores perciben inseguridad y desisten de usar la bicicleta pública.

### 3. Incentivos de Adopción e Inclusión
Dado que la participación de menores de 18 años y de la tercera edad es minoritaria, se propone el diseño de **tarifas preferenciales** (descuentos estudiantiles y vinculación con tarjetas de INAPAM) junto con talleres gratuitos de ciclismo urbano comunitario para activar estos sectores en viajes cortos o de fin de semana.

---

### 🚀 Cómo Ejecutar el Proyecto
1. Haz clic en el botón **Open In Colab** al inicio de este archivo para abrir la libreta de forma directa.
2. Asegúrate de cargar los dataset correspondientes de ECOBICI y estaciones en tu entorno de ejecución para correr las celdas de forma secuencial.
