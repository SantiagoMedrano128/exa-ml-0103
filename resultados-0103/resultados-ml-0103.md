# Reporte de Análisis de Datos - Pandas

`Santiago Medrano Machine Learning pandas, NC 0103`

## 1. DataFrame Convertido
```text
         Red  Usuarios_millones  Anio_creacion
0   Facebook               2900           2004
1  Instagram               2000           2010
2    Twitter                400           2006
3     TikTok               1000           2016
4    YouTube               2500           2005
5   LinkedIn                800           2003
```

## 2.1 Primeras Filas (head)
```text
         Red  Usuarios_millones  Anio_creacion
0   Facebook               2900           2004
1  Instagram               2000           2010
```

## 2.2 Últimas Filas (tail)
```text
        Red  Usuarios_millones  Anio_creacion
4   YouTube               2500           2005
5  LinkedIn                800           2003
```

## 2.3 Dimensiones (Filas, Columnas)
```text
(6, 3)
```

## 2.4 Tipos de Datos por Columna
```text
Red                    str
Usuarios_millones    int64
Anio_creacion        int64
dtype: object
```

## 2.5 Información General (info)
```text
<class 'pandas.DataFrame'>
RangeIndex: 6 entries, 0 to 5
Data columns (total 3 columns):
 #   Column             Non-Null Count  Dtype
---  ------             --------------  -----
 0   Red                6 non-null      str  
 1   Usuarios_millones  6 non-null      int64
 2   Anio_creacion      6 non-null      int64
dtypes: int64(2), str(1)
memory usage: 276.0 bytes

```

## 3. Estadísticas Generales de 'Usuarios_millones'
```text
count       6.000000
mean     1600.000000
std      1009.950494
min       400.000000
25%       850.000000
50%      1500.000000
75%      2375.000000
max      2900.000000
Name: Usuarios_millones, dtype: float64
```

## 4. Ordenar Ascendente por año de creación
```text
         Red  Usuarios_millones  Anio_creacion
5   LinkedIn                800           2003
0   Facebook               2900           2004
4    YouTube               2500           2005
2    Twitter                400           2006
1  Instagram               2000           2010
3     TikTok               1000           2016
```

## 5. Ordenar Descendente por usuarios en millones
```text
         Red  Usuarios_millones  Anio_creacion
0   Facebook               2900           2004
4    YouTube               2500           2005
1  Instagram               2000           2010
3     TikTok               1000           2016
5   LinkedIn                800           2003
2    Twitter                400           2006
```

`Santiago Medrano Machine Learning pandas, NC 0103`