<h1 align="center">Laboratorio 8</h1>

<br>

## ⚙️ Requisitos 

- **Python**

## 🚀 Instalación y configuración

### 1. Clonar el repositorio
```bash
git clone https://github.com/JAVIERCLO/Lab8TC.git
```
```bash
cd Lab8TC
```

### 3. Instalar extensiones recomendadas

VS Code 

Para instalarlas manualmente:
1. Presiona `Ctrl+Shift+X`
2. Busca "Python" y "Jupyter"
3. Haz clic en "Install"

### 4. Crear el ambiente virtual

Abre la terminal integrada de VS Code (`Ctrl+ñ` o `View` → `Terminal`) y ejecuta:
```bash
python -m venv .venv
```

### 5. Activar el ambiente virtual

La terminal debería activar automáticamente el ambiente virtual. Si no:

**Windows (CMD/PowerShell en VS Code):**
```powershell
.venv\Scripts\activate
```

**Linux/Mac:**
```bash
source .venv/bin/activate
```

Deberías ver `(.venv)` al inicio de tu terminal.

### 6. Instalar las dependencias
```bash
pip install -r requirements.txt
```

### 7. Seleccionar el intérprete de Python

1. Presiona `Ctrl+Shift+P`
2. Escribe: **"Python: Select Interpreter"**
3. Selecciona: **Python 3.x.x ('.venv': venv)**

## 8. Cómo ejecutar los notebooks

1. Abrir el archivo que deseemos ejecutar:
```bash
jupyter notebook Ejercicios.ipynb
```

