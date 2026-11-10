# LogiData — Dashboard de resultados (Streamlit)

Este proyecto incluye los **resultados reales** aportados por el usuario. El dashboard se abre con el consolidado oficial `LogiData_Fases_I_II_consolidado.xlsx` sin solicitar un archivo ni ejecutar la heurística.

## Publicación

1. Extrae el ZIP en tu computador.
2. Sube el **contenido** de esta carpeta a la raíz de un repositorio de GitHub.
3. En Streamlit Community Cloud elige ese repositorio, rama `main` y archivo principal `app.py`.
4. Selecciona Deploy.

## Prueba local

```bash
python -m pip install -r requirements.txt
python -m streamlit run app.py
```

## Resultados incluidos

- `LogiData_Fases_I_II_consolidado.xlsx`: fuente activa del dashboard, con 45 hojas (FI, FII, comparaciones, movimientos y coordenadas).
- `respaldos_parciales/`: mejores resultados parciales de FI y FII; respaldos, no se usan como fuente del dashboard.

No se incluyen los Excel de instancias históricas 5, 10, 15 y 20 clientes. Esa comparación requiere incorporarlos posteriormente en `resultados_logidata/` usando los nombres que espera el código.

**Privacidad:** si el repositorio es público, cualquier persona podrá consultar el código y los archivos Excel del repositorio.
