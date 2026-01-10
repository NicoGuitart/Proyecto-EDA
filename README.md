# Análisis Exploratorio de Datos (EDA): Medallero olímpico 

Este proyecto muestra un **Análisis Exploratorio de Datos (EDA)** del historial de los Juegos Olímpicos, con el fin de estudiar la evolución de la participación de atletas y el medallero desde una perspectiva histórica y geopolítica. 

---

## Contenidos
- **Introducción**
- **Metodología**
- **Objetivos**
- **Exploración general**
- **Planteamiento de hipótesis**
- **Análisis exploratorio de datos**
- **Conclusiones**
- **Lineas de investigación futuras**
- **Conclusiones y Recomendaciones**

---

## Fuente de Datos
[Kaggle](https://www.kaggle.com/datasets/heesoo37/120-years-of-olympic-history-athletes-and-results).

- **Variables categóricas**: `Sex`, `Country/NOC`, `Sport`, `Event`,`Medal`.
- **Variables numéricas**: `Age`, `Height`, `Weight`, `ID`.
- **Variables temporales**: `Year`, `Games`.
- **Variables binarias**: `Has_Medal`, `Team_Event`,`Single_Event`.

## Tratamiento de Datos
- **Valores nulos**:
  - Los valores nulos de las medallas asumimos que son aquellos atletas que no han ganado ninguna medalla en aquel evento. Como nos interesa mantener esta condición, los convertimos a “NoMl” (“No Medal”).
  - Fechas incompletas se combinaron para reducir los valores nulos.
  - Las variables Edad, Altura y Peso son numerosas, pero no las priorizamos para este análisis. Se sustiyueron los nulos por la mediana de cada variable diferenciando el sexo masculino y femenino.

---

## Principales Observaciones
1. **Potencias olímpicas**:
   - **USA**, **China**, **Rusia** y **Alemania** dominan el medallero históricamente.
2. **Deportes con más medallas**:
   - Las principales potencias se especializan en deportes diferentes..
3. **PIB y población**:
   - Las grandes potencias medalleras suelen un alto PIB por capita.
   - Hay países con un PIB relativamente menor pero con grandes resultados.
   - Hay países con gran riqueza pero con pocas medallas.
4. **Ventaja del anfitrión**:
   - En casi todos los eventos, el país anfitrión han tenido un éxito rotundo en el medallero.
5. **Participación  y rendimiento de los atletas a lo largo del tiempo**
   - Los grandes acontecimientos históricos influyen directamente tanto en la participación como en el rendimiento deportivo de las principales potencias olímpicas.
6. **Alemania en los JJOO**
   -  Transición desde un modelo deportivo altamente politizado hacia un sistema más equilibrado y sostenible
7. **URSS en los JJOO**
   - Rendimiento consistente entre 90-125 medallas por olimpiada durante 1952 - 1976.
8. **EEUU en los JJOO**
   - EEUU muestra un crecimiento sostenido desde 1896 con picos anómalos en 1904 y 1984.
10. **Comparación promedio URSS vs Rusia**
   - Rusia sufre una gran caída de medallas tras disolución de la URSS.
11. **Comparación URSS vs EUA**
   - Los boicots de 1980 y 1984 marcarons la rivalidad entre ambos países durante la Guerra Fría.
   - En competencia directa y equilibrada (sin boicots), la rivalidad era muy pareja con ligera ventaja soviética.

---

## Conclusiones principales
- **Especialización deportiva**:  el éxito olímpico no depende únicamente de la riqueza, sino de cómo los países orientan sus recursos y programas deportivos.
- **Guerra Mundiales**:  los grandes acontecimientos del siglo XX provocaron rupturas estructurales en la participación y el medallero, así como procesos de recuperación desiguales condicionados por sanciones, crisis económicas y problemas de localización.
- **Rivalidades históricas**: durante la Guerra Fría, los Juegos Olímpicos actuaron como un escenario de rivalidad geopolítica, donde boicots y ausencias distorsionaron el medallero.

---

## Requisitos
### Tecnologías utilizadas
- **Python**: pandas, numpy, matplotlib, seaborn.
- **Jupyter Notebook**: Visualización y análisis interactivo.
- **Presentaciones**: Canva.
- **Memoria**: Word y PDF.

---

## Créditos

Pablo Baro, Nico Guitart y Sergi de la Cruz
Bootcamp Data Science The Bridge
2025/26
