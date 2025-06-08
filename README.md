# eda-portuguese-banking
Proyecto donde se lleva a cabo un análisis exploratorio detallado sobre los datos de una campaña de marketing de una entidad bancaria.  Como objetivo nos hemos marcado además de comprobar el exito de ésta, identificar patrones para optimizar futuras campañas o productos ofrecidos por el banco

---

## 📁 Estructura del repositorio

```
├── data/
│   ├── bank-additional.csv
│   └── customer-details.xlsx
├── graficas/
│   └── graficaXX.png (todas las visualizaciones numeradas)
├── EDA_portugues-bank.ipynb
└── README.md                   # Este archivo
```

## 📊 Ejemplos de gráficas

Las siguientes gráficas resumen los resultados clave. Puedes visualizarlas directamente en la carpeta /graficaXX.
Ejemplo de algunas visualizaciones:

- Gráfica 01 – Distribución de edades (pie chart)
- Gráfica 06 – Aceptación por categoría laboral (stacked bars)
- Gráfica 09 – Aceptación según duración de llamada (violín & boxplot)
- Gráfica 13 – Aceptación por año y mes (stacked bars)
- Gráfica 17 – Aceptación según visitas web al mes (stacked bars)

El detalle completo y los comentarios por gráfica están disponibles en el notebook.

## 💻 Requisitos
Este proyecto fue desarrollado con:
- Python 3.x
- Librerías Python: pandas, seaborn, matplotlib, numpy, openpyxl

## 📌 Conclusiones clave
- La mayoría de clientes no han respondido positivamente a la campaña
- El mayor grupo de clientes impactados (entre 30 y 60) son los que menos han aceptado la campaña 
- El resto de grupo de edad son los que mas han aceptado
- Estos grupos además coinciden en la situacion laboral que se espera por su edad:  estudiantes y jubilados
- Dentro del resto de grupos admin, technician y desempleados han sido los más receptivos.
- Los analfabetos son el grupo con mejor feedback a la campaña si hablamos de nivel educativo.
- El resto de factores demograficos (estado civil, numero de hijos, ingresos, y las visitas a la web), no aportan datos relevantes).
- Solteros aceptan algo más que casados o divorciados, pero la diferencia no es significativa.
- Clientes con impagos previos, hipotecas o préstamos activos tienden a rechazar más la campaña.
- No se detecta un mes o año especialmente exitoso.
- Aumentar el numero de contactos y su duración, reduce la tasa de exito.


