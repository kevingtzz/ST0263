# Laboratorio 02 Big Data (Mapreduce)

## En el presente laboratorio se plantea la solución de un problema de almacenamiento de datos en el framework Hadoop; con los scripts planteados se prentende calcular los respectivos valores 'key' & 'value' con operaciones de map reduce en la librería MRjop de python.

---

### :white_check_mark: Requerimientos:

- [x] Los scripts son compatibles con python 2 y 3, pero es necesario instalar previamente en caso de ser necesario.
- [x] Para la implementación de los mapreducers se hace uso de la librería mrjob de python, para instalarla ejecuta el siguiente comando en la terminal:

```bash
pip install mrjob
```

### :arrow_forward: Ejecución:

Cada uno de los scripts requiere de una un archivo de datos .csv que será suministrado como argumento.
[x] Salario promedio por sector economico:

```bash
python SE.py dataempleados.csv
```

[x] Salario promedio por empleado:

```bash
python SP.py dataempleados.csv
```

[x] Numero de salario promedio por empleado que se ha tenido a lo largo de la prueba:

```bash
python NSE.py dataempleados.csv
```

> La solución a los problemas planteados ha sido basada en el siguiente video:

<a href="https://www.youtube.com/watch?v=PAAwR4eRuBY
" target="_blank"><img src="http://img.youtube.com/vi/PAAwR4eRuBY/0.jpg" 
alt="Video image" width="240" height="180" border="10" /></a>
