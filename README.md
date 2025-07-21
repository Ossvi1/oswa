<h1 align="center">🎶 Sistema de Concierto - Pilas y Colas</h1>

**Nombre:** LUIS ALBERTO FIGUEROA GONZÁLEZ  
**Grupo:** 11 a 2 | Materia: Estructura de Datos  

## 🎯 Descripción  
Sistema web con Flask que simula:

- Una **cola** para personas esperando su entrada al concierto.
- Una **pila** con el historial de actos presentados, permitiendo deshacer el último.

## 🚀 ¿Cómo instalar y ejecutar este proyecto?

1. **Descarga o clona el repositorio**
   ```bash
   git clone https://github.com/Ossvi1/Colas-y-Pilas.git
   cd Colas-y-Pilas
   ```

2. **Crea y activa un entorno virtual, instala dependencias y ejecuta la app**
   ```bash
   python -m venv venv
   venv\Scripts\activate   # En Windows
   source venv/bin/activate   # En Mac/Linux
   pip install flask
   python app.py
   ```

   Luego abre tu navegador y entra a:
   ```
   http://localhost:5000
   ```

## 🖼️ Ejemplo de uso

- En **Entrada al Concierto (Cola)** puedes agregar nombres de personas a la fila.
- Al presionar **"Atender siguiente"**, se elimina al primero de la fila y se muestra un mensaje con su nombre.
- En **Historial de Actos (Pila)** puedes añadir actos del concierto (por ejemplo: Banda 1, DJ Set, etc.).
- Al presionar **"Quitar último acto"**, se elimina el último acto añadido.

## 🎬 Ejemplo de cómo debería funcionar

<img src="https://raw.githubusercontent.com/Ossvi1/Colas-y-Pilas/main/assets/COLAS%20Y%20PLILAS.gif" alt="Demostración del sistema" width="500">
