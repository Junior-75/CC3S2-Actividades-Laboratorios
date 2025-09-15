### Actividades y evidencias

#### 1) HTTP: Fundamentos y herramientas

1. **Levanta la app** con variables de entorno (12-Factor):
   `PORT=8080 MESSAGE="Hola CC3S2" RELEASE="v1" python3 app.py` (usa tu *venv*). La app **escucha** en el puerto indicado y **loggea en stdout**. Incluye extracto de salida (stdout) en el reporte. Ahora activamos el entorno virtual:
   ![VENV](Imagenes/VENV.png)
   Instalamos la libreria flask:
   ![FLASK](Imagenes/FLASK.png)

2. **Inspección con `curl`:**
   - `curl -v http://127.0.0.1:8080/` (cabeceras, código de estado, cuerpo JSON).
   ![CURL](Imagenes/CURL.png)

   - `curl -i -X POST http://127.0.0.1:8080/` (explica qué ocurre si no hay ruta/método).
   ![CURL2](Imagenes/CURL2.png)

3. **Puertos abiertos con `ss`:**
   `ss -ltnp | grep :8080` (evidencia del proceso y socket).
   ![TCP](Imagenes/TCP.png)

4. **Logs como flujo:** Demuestra que los logs salen por stdout (pega 2–3 líneas). Explica por qué **no** se escriben en archivo (12-Factor).
    ![LOGS](Imagenes/LOGS.png)