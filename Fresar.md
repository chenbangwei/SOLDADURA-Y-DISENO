# Fresar y utilizar mods con la monofab

## Apuntes de teoría

## Archivo a utilizar

[conejo de Alba, poner enlace, comentar que se tiene su permiso explícito]
![](https://github.com/chenbangwei/SOLDADURA-Y-DISENO/blob/main/conejito.png)

## Proceso para pasarlo a archivo .rml

¿Qué es un archivo .rml?

Es el archivo que lee la monofab para poder moverse y fresar un objeto. Es un set de instrucciones en un "sabor" de Gcode. 

PASO 1:
- CARGAR MODS

http://mods.cba.mit.edu/

PASO 2:
-Cargar Png Y Ajustar DPI

Tamaño 50mm máx

He utilizado este png 

![](https://github.com/chenbangwei/SOLDADURA-Y-DISENO/commit/960eb3bb7f87d92056e4c13af5710b0073ca3355)

-Ajustamos la Herramienta
  Diameter 1mm
  Cut Depth 2mm
  Total Cut 2mm
  OFFset Number 4
  OFFset Stepower 0.75
  
  (captura)
  
  ![](https://github.com/chenbangwei/SOLDADURA-Y-DISENO/commit/960eb3bb7f87d92056e4c13af5710b0073ca3355)
  
  ![](https://github.com/chenbangwei/SOLDADURA-Y-DISENO/commit/1269f1838952f8fa6a073ea56541ce8b870f40aa)
  
-Ajustar Roland
  SPEED;10mm/S
  ORIGIN:X-0,Y0,Z0
  JOG Height:4mm
-Ajustar Módulo de guardia archivo

-Darle Calculate.YGuardar el.RML
50x50mm-->   ppp-->fx
![](https://github.com/chenbangwei/SOLDADURA-Y-DISENO/blob/main/Captura%20de%20pantalla%20de%202021-04-22%2013-15-00.png)

## ARCHIVOS
PPP:Puntos(píxeles).Por.Pulgada(cuadrada)
DPI:Dots(puntos)Per(por)INCH(pulgada)
pcb-->Placas electrónicas
svg-->archivo vectorial
png-->archivo ráster(pixeles)
stl-->archivo de puntos 3D



### Archivo rml para fresar

## Proceso de fresado

