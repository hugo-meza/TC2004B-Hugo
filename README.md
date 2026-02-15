# TC2004B - Análisis de Ciencia de Datos

**Nombre:** Hugo André Meza Fierros
**Matrícula:** A00841695  
**Semestre:** Febrero-Junio 2026

## Descripción

Repositorio personal para el curso TC2004B. Contiene notebooks y proyectos del semestre.

## Estructura

TC2004B-Hugo/
├── README.md
├── .gitignore
├── notebooks/      # Jupyter Notebooks
└── data/          # Datasets (cuando aplique)

## Contenido por Semana



### Semana 1
- Práctica de Git/GitHub
- Primer notebook con dataset Iris
- Familiarización con herramientas

## Contacto

- Email: [A00841695@tec.mx]
- GitHub: [@hugo-meza](https://github.com/hugo-meza/)
## Setup Local


### Requisitos
- Python 3.8+
- Git

### Instalación

#### 1. Clonar repositorio
```bash
git clone https://github.com/hugo-meza/TC2004B-Hugo.git
cd TC2004B-Hugo
```

#### 2. Crear ambiente virtual

**Mac/Linux:**
```bash
python3 -m venv tc2004b_env
source tc2004b_env/bin/activate
```

**Windows (PowerShell):**
```bash
python -m venv tc2004b_env
tc2004b_env\Scripts\Activate
```


#### 3. Instalar dependencias
```bash
pip install -r requirements.txt
```

#### 4. Ejecutar Jupyter
```bash
jupyter notebook
```

Navega a `notebooks/` y abre el .ipynb

### Desactivar ambiente
```bash
deactivate
```

### Problemas Comunes

**Error: comando no encontrado**
- Verifica que Python esté instalado: `python --version`

**Error de permisos (Windows)**
- Ejecuta: `Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser`

**ModuleNotFoundError**
- Verifica que el ambiente esté activo
- Reinstala dependencias: `pip install -r requirements.txt`
