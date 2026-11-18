# ISM Snow Day · Labs prácticos con Cortex Code

Dos labs en notebooks de Snowflake para ISM. Cada participante usa su propia cuenta de Snowflake (como ACCOUNTADMIN) y **todo está dentro del notebook**: no hay otro código que ejecutar.

| Lab | Para quién | Duración | Qué construye |
|---|---|---|---|
| [Lab 1 · Pregúntele a sus números](Lab1_ISM_Gerentes_Asistente_Financiero.ipynb) | Gerentes · sin SQL | 20 min | Modelo semántico financiero + **Asistente Financiero ISM** en CoWork, que responde las 9 preguntas del cierre del mes |
| [Lab 2 · Del dato crudo al agente comercial](Lab2_ISM_Tecnico_Agente_Comercial.ipynb) | Equipo técnico · SQL | 90 min | AI Functions en una Dynamic Table incremental, validación de la IA, modelo semántico que cuadra con Finanzas y **Asistente Comercial ISM** multipaís |

Guía completa: **https://juancamilo.dev/ism-lab/**

## Cómo empezar

1. **Reclame su cuenta** en https://go.dataops.live/ism-snowday/register e inicie sesión en Snowsight.
2. Descargue su notebook (`.ipynb`) de este repositorio.
3. En Snowsight: **Projects » Workspaces** → **+ Add New** → **Upload Files**.
4. Abra el notebook y conéctelo al compute pool `SYSTEM_COMPUTE_POOL_CPU`.
5. Ejecute la primera celda: cambia a `ACCOUNTADMIN`, crea el warehouse `ISM_SNOWDAY_WH`, activa la IA entre regiones y crea su schema.
6. Abra **Cortex Code** y siga el notebook. Cada sección trae un prompt para copiar y una celda de referencia.

## Su turno y reto opcional

El Lab 2 tiene 6 preguntas de **Su turno** que el notebook corrige solo, y un **reto opcional avanzado** (días de cobertura de inventario) con una celda de validación.

## Datos

100% sintéticos. Las tablas siguen una estructura tipo SAP (sociedades, ventas, inventario MB52), pero las marcas, los clientes, las notas y las cifras son ficticios.
