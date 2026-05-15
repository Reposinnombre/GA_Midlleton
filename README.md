# 🧬 Algoritmo Genético para Estimación de Ruido Middleton Clase A

<p align="center">
  Implementación y validación de una arquitectura basada en algoritmos genéticos
  para la estimación de parámetros del modelo de ruido impulsivo Middleton Clase A.
</p>

---

## 📖 Descripción

Este repositorio contiene el desarrollo completo del análisis, simulación e implementación hardware de un algoritmo genético aplicado a la estimación de ruido Middleton Clase A.

El proyecto incluye:

- 🐍 Simulaciones desarrolladas en Python/Jupyter Notebook.
- ⚙️ Descripciones de hardware en VHDL.
- 🖼️ Diagramas de bloques y arquitectura del sistema.
---

# 📂 Organización del repositorio

```bash
.
├── notebooks/
│   └── Algoritmos_geneticos.ipynb
│
├── vhdl/
│   ├── control/
│   ├── operadores_geneticos/
│   ├── memoria/
│   ├── fitness/
│   └── top/
│
├── Readme/
│   ├── arquitectura_general/
│   ├── fsm/
│   └── Proceso_evolutivo/
|   └── Operador_binario/
│   └── Operador_vecindad/
│   └── Bloque funcion de costo/
│   └── Elite_y_guardar/
└── README.md
```

---

# 🧪 Simulación en Python

El notebook principal contiene:

✔️ Modelado del ruido Middleton Clase A  
✔️ Implementación del algoritmo genético  
✔️ Evaluación de convergencia  
✔️ Validación de resultados  
✔️ Análisis de desempeño  

📄 Archivo principal:

```bash
/notebooks/Algoritmos_geneticos.ipynb
```

---

# ⚙️ Implementación Hardware

La implementación hardware fue desarrollada en VHDL e incluye distintos bloques funcionales del sistema:

- Unidad de control
- Máquina de estados finitos (FSM)
- Operadores genéticos
- Evaluación de fitness
- Memorias y registros auxiliares
- Integración top-level

📁 Código fuente:

```bash
/vhdl
```

---

# 🖼️ Figuras y documentación

El repositorio incluye documentación gráfica utilizada durante el diseño y validación:
- Arquitectura general del sistema para implementacion en Hardware
- Diagramas de bloques
- Máquinas de estados

📁 Directorio:

```bash
/figures
```

---

# 🎯 Objetivo del proyecto

Desarrollar una arquitectura hardware eficiente basada en algoritmos genéticos para la estimación de parámetros asociados al modelo de ruido impulsivo Middleton Clase A, con posibilidad de implementación sobre FPGA.

---

# 🛠️ Herramientas utilizadas

| Herramienta | Uso |
|---|---|
| Python | Simulación y validación |
| Jupyter Notebook | Desarrollo del algoritmo |
| VHDL | Implementación hardware |
| ModelSim / QuestaSim | Simulación digital |
| Vivado / Quartus | Síntesis FPGA |

---

# 🚧 Estado del proyecto

<p align="center">
  <b>Proyecto actualmente en desarrollo</b>
</p>
