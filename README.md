
# Proyecto IoT – Medidor de Nivel de Agua

Este repositorio contiene las tres entregas progresivas de un proyecto IoT basado en ESP32 para medir el nivel de agua en un tanque. El proyecto fue desarrollado como parte de la materia **Aproximación al Mundo del Trabajo de la Tec. Sup en Desarrollo de Software**

## 🔹 Evidencia 1 – Prototipo básico con ESP32

- Sensor ultrasónico + ESP32 + LED de alerta
- Simulación en Wokwi
- Programado en MicroPython

📄 `evidencia-1/informe.pdf`  
🔗 [`link-wokwi-medidor.txt`](evidencia-1/link-wokwi-medidor.txt)

🧾 Código: [`codigo/evidencia-1/medidor_agua.py`](codigo/evidencia-1/medidor_agua.py)


## 🔹 Evidencia 2 – Escalado con almacenamiento en MySQL

- Flask + base de datos MySQL en Clever Cloud
- ESP32 simulado en Wokwi enviando datos a Flask
- Despliegue en Render

📄 `evidencia-2/informe.pdf`  
🔗 [`link-wokwi.txt`](evidencia-2/link-wokwi.txt)  
📹 [`link-video.txt`](evidencia-2/link-video.txt)

🧾 Código: [`codigo/evidencia-2/app.py`](codigo/evidencia-2/app.py)


## 🔹 Evidencia 3 – Visualización en Dashboard Web

- Desarrollado en React con Chart.js y Axios
- Muestra datos en tiempo real desde la API
- Estilo violeta y negro, gráfico + tabla paginada

📄 `evidencia-3/informe.pdf`  
🔗 [`link-dashboard.txt`](evidencia-3/link-dashboard.txt)


## Código

Todo el código está dentro de la carpeta `codigo/`, separado por evidencia.


## Descripción general

Este sistema mide el nivel de agua en un tanque mediante un sensor ultrasónico, activa alertas visuales y permite consultar los datos a través de una API y un dashboard web.

- Simulado en Wokwi
- Código backend en Flask
- Datos almacenados en MySQL
- Visualización en React

