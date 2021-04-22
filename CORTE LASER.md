
# CORTE LÁSER 

## COnceptos sobre corte láser (teoría)

// Apuntes classe ( corte laser)

Este es el enlace base http://academy.cba.mit.edu/classes/computer_cutting/index.html

## THE FAB Academy (Apuntes de diversas maquinas de corte i otros)
// Hemos entrado en la pagina web i pinchado el enlace schedule (2020),del feb12 computer-controlled cutting

 knife
 
    Roland Zund Othercutter ultrasonic
    
 print and cut
 
    Roland
    
     Laser:Trotec 
     
    hay cinco estados materiales :solido,liquido,gaseoso,plasma y condensado de Bose Einstein
    
 PLASMA
 
 Forest Scientific Torchmate
 
 torchmate:
 
 WATERJET
 es una maquina a presion de agua para corta varias cosas ,pero se utiliza en metales
 HOT WIRE
 
 WIRE EDM
 
 CAD(Computer.Aided.Design)diseño assistido por ordenador
 
 
 
 
 CAM(Computer.Aided.Machining)mover maquinas 
 

VINYLCUTTER(cortador de viñylo)
se ulitiza para circuitos flexibles (existen placas de cobre flexible)
-ORIGAMI
LASERCUTTER(cortadora de laser)
// amplificaccion de luz a travess de emission estimulada
TIPOS DE LASER 
-CO2(10.6 u)
-fiber(1-2 u)
-InGaAsP(1-2u)
-AlGaAs(600-900 nm)
-Nd:YAG(1054-532 nm)
-Ti:sapphire (650-1100 nm)
-Excimer(100-300 nm)


## Diseño inicial para corte láser

¿Qué imagen he escogido? ¿Por qué?

Metro exodus,por qué es un juego que me gusta i lo juego 

¿Qué características tiene la imagen y por qué?

-Mascarillas anti-radiactivas

-Esta en una estación del año de nieve

-Desforestaciónes

-vias de tren 

-El personaje principal que manejas 

Para cortar con láser, tuvimos que pasar la imagen a blanco y negro y vectorizarla. Además hubo que hacer una circunferencia con un trazo de color rojo 255,0,0 en RGB, para que el láser lo cortase. 

*imagen * 

## Viaje a la UPC (antes de cortar)

-¿Qué Impresiones tengo del sitio>¿Qué me ha gustado? ¿Cómo es?

FresadoraCNC,Máquinas de Impressión 3D,me ha gustado corte de plasma....

-¿Qué he visto y qué he aprendido en general?-->CNC-->LUGAR

La Maquina. He aprendido a cortar con láser piezas pequeñas y vectorizar imágenes. 

## CORTE LÁSER

-¿Cómo es la láser?¿como se hace funcionar?¿Que medidas de seguridad hay?

La láser pequeña con una luz potente concentrada,conectando con la fresadora i el inkscape final dandole un boton a la fresadora para INICIAR ,cristal de plastico resistente

-¿Cómo pasamos del diseño al corte?

Primero necesitamos el archivo svg. Este lo abriremos con inkscape y este inkscape tendrá de tamaño del lienzo la cama de la máquina. Después de eso, posicicionamos la imagen en el lugar donde vamos a realizar el corte. 

Revisamos sus características (grosor de línea, etc). 

Después guardamos como pdf

Y el pdf lo imprimimos. 

Revisamos las caracteristicas de impresión y lanzamos el "job". Luego le damos al botón de "play" en la láser. 

## PIEZA CORTADA 

¿Qué opinión tienes de cómo ha quedado?
guay,queda los bordes quemados i te puedes mancharte pero bien.

## PIEZAS ADICIONALES

PASO 1:
- CARGAR MODS
PASO 2:
-Cargar Png Y Ajustar DPI
Tamaño 50mm máx
-Ajustamos la Herramienta
  Diameter 1mm
  Cut Depth 1mm
  Total Cut 1mm
  OFFset Number 4
  OFFset Stepower 0.75
-Ajustar Roland
  SPEED;10mm/S
  ORIGIN:X-0,Y0,Z0
  JOG Height:4mm
-Ajustar Módulo de guardia archivo

-Darle Calculate.YGuardar el.RML
50x50mm-->   ppp-->fx

## ARCHIVOS
PPP:Puntos(píxeles).Por.Pulgada(cuadrada)
DPI:Dots(puntos)Per(por)INCH(pulgada)
pcb-->Placas electrónicas
svg-->archivo vectorial
png-->archivo ráster(pixeles)
stl-->archivo de puntos 3D

