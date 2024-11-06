# Configuración en MacOS y Linux

Ejecute los siguientes comandos en el terminal:

```bash
python3 -m venv .venv
source .venv/bin/activate
source setup.sh
```

# Configuración en Windows

Ejecute los siguientes comandos en el terminal:

```bash

asegurarse de hacerlo en cmd, no powershell (settings, buscar: windows terminal, como sale en user, cambiar a workspace (pestañas) Terminal › External: Windows Exec
Customizes which terminal to run on Windows.) y ahi seguir con lo siguiente:

python3 -m venv .venv
.venv\Scripts\activate
setup
```

# Ejecución de pruebas

Ejecute el siguiente comando en el terminal:

```bash
pytest
```
