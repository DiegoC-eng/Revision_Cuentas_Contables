# Revision Cuentas Contables - BF CR 2026

Dashboard interactivo de **Cuentas Controlables** (Walmart CAM Costa Rica).

## Contenido
- `index.html` — Dashboard autocontenido (data embebida). Se abre con doble clic o via GitHub Pages.

## Funcionalidad
- Selector de **cuenta**: Horas Extra / Suministros Quimicos (Limpieza).
- Filtro por **Periodo**: Acumulado (YTD) o mes individual (Ene-Jul).
- Filtro por **Gerente Senior** y buscador de tienda.
- **Cuadro por Gerente Senior** y **detalle por tienda** con columnas:
  Gasto LY, Gasto TY, Plan, Crec. %, Alc. %, Var. $
- **Grafica mensual**: Real, Plan y % Crecimiento vs LY.

## Formulas
- **% Crecimiento** = Real / LY - 1
- **% Alcance (logro)** = Plan / Real  (gasto: >=100% dentro de plan)
- **Var. $** = Real - Plan  (positivo = sobre-gasto)

Fuente: `Cuentas Controlables BF CR 2026.xlsb`.
