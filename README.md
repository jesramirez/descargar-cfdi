# Métodos de la clase ServicioCfdi
*descargarPorAnnioYMes
*descargarPorAnnioMesYDia

## descargarPorAnnioYMes
Filtra por año y mes para despues almacenar los xml encontrados en el directorio 
que recibe como parametro.

```python
descargarPorAnnioYMes(directorio, año, mes)
```

*directorio: Indica donde se almacenarán los xml encontrados, es necesario que 
directorio ya exista y termine con / .
*año: Año a buscar.
*mes: Mes a buscar
    *01=Enero
    *02=Febrero
    *03=Marzo
    *04=Abril
    *05=Mayo
    *06=Junio
    *07=Julio
    *08=Agosto
    *09=Septiembre
    *10=Octubre
    *11=Noviembre
    *12=Diciembre

#### Ejemplo de uso método descargarPorAnnioYMes

```python
from ServicioCfdi import ServicioCfdi

servicio = ServicioCfdi('RFC', 'Contrasena')
servicio.descargarPorAnnioYMes('/home/usuario/xml/', '2015', '03')
```
## descargarPorAnnioMesYDia
Filtra por año, mes y dia para despues almacenar los xml encontrados en el directorio 
que recibe como parametro.

```python
descargarPorAnnioMesYDia(directorio, año, mes, dia)
```

*directorio: Indica donde se almacenarán los xml encontrados, es necesario que 
directorio ya exista y termine con / .
*año: Año a buscar
*mes: Mes a buscar
    *01=Enero
    *02=Febrero
    *03=Marzo
    *04=Abril
    *05=Mayo
    *06=Junio
    *07=Julio
    *08=Agosto
    *09=Septiembre
    *10=Octubre
    *11=Noviembre
    *12=Diciembre
dia: Dia a buscar.

#### Ejemplo de uso método descargarPorAnnioMesYDia

```python
from ServicioCfdi import ServicioCfdi

servicio = ServicioCfdi('RFC', 'Contrasena')
servicio.descargarPorAnnioMesYDia('/home/usuario/xml/', '2015', '03', '14')
```
