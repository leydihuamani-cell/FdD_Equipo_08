# TALLER 03: BÚSQUEDA BIBLIOGRÁFICA

## 1. Artículos científicos

### Artículo científico 1

### Artículo científico 2

### Artículo científico 3

| N.° | Recurso | Tema | Aporte al proyecto | Variables/Caracteristicas | Valores/Rango |
|---:|---|---|---|---|---|
| 1 |  |  |  |  |  |
| 2 |  | |  |  |  |
| 3 |  |  |  |  |  |

## 2. Patentes

### 2.1. *Reverse Vending Machine* (US6547055B2)

![Esquema de la máquina de vending inverso](https://patentimages.storage.googleapis.com/85/1c/6a/8a992bfab66183/US06547055-20030415-D00000.png)

*Figura 4. Esquema general de la máquina de vending inverso. Fuente: [patente US6547055B2](https://patents.google.com/patent/US6547055B2/en).*

Coyne et al. desarrollaron una máquina de vending inverso destinada a recibir y procesar envases reciclables de bebidas. El sistema cuenta con una zona de ingreso que permite depositar varios recipientes, un mecanismo que los transporta individualmente y un escáner óptico que lee sus códigos para determinar si son aceptados o rechazados [1].
Después de identificar cada envase, un procesador registra la cantidad aceptada y activa un mecanismo de separación. Los recipientes válidos son enviados al depósito correspondiente, mientras que los no aceptados se dirigen hacia una salida de devolución. La máquina también puede incorporar un mecanismo de compactación para reducir el volumen ocupado y emitir un comprobante o cupón para el usuario.
Esta patente aporta al proyecto la posibilidad de automatizar la recepción, identificación y conteo de residuos reciclables. También permite considerar variables como la cantidad de envases ingresados, el tipo de material, el estado de aceptación o rechazo y el volumen ocupado en el contenedor.

---

### 2.2. *Reverse Vending System and Method* (WO2023195003A1)

<!-- Arrastrar aquí una imagen o esquema de la patente WO2023195003A1 -->

*Figura 5. Esquema del sistema de identificación, clasificación y procesamiento de envases. Fuente: [patente WO2023195003A1](https://patents.google.com/patent/WO2023195003A1/en).*

Bardugo y Porat propusieron un sistema de vending inverso capaz de recibir recipientes de distintos materiales, como plástico, vidrio y metal. El sistema puede emplear cámaras, lectores de códigos y sensores para reconocer las características de cada envase antes de dirigirlo al mecanismo de procesamiento correspondiente [2].
Después de la identificación, los materiales son clasificados, triturados o compactados y almacenados en depósitos independientes. Esta separación evita la mezcla de los residuos y facilita su posterior aprovechamiento. Además, el sistema puede registrar datos de cada operación, como la fecha, hora, identificación del usuario y tipo de recipiente procesado [2].
La patente menciona una capacidad aproximada de 45 o más envases por minuto, una abertura de ingreso situada aproximadamente a 1200 mm del suelo y un nivel promedio de ruido menor de 60 dBA. También considera propiedades como el peso, la forma y la conductividad para reconocer los materiales [2].
Esta propuesta aporta al proyecto un método de clasificación automática y almacenamiento separado. Sus principios pueden utilizarse para definir sensores, controlar el ingreso de residuos, medir la cantidad procesada y mejorar la segregación en los puntos de acopio.

### 2.3. *Waste sorting apparatus and method* (US20250058968A1)

<p align="center">
  <img 
    src="https://github.com/leydihuamani-cell/FdD_Equipo_08/blob/bca0e120019590e252e96998ca6228a32450e344/Recursos/Taller_3/patente3.jpeg"
    width="400"
    alt="Esquema general de la máquina de vending inverso">
</p>

<p align="center">
  <em>*Figura 1. Esquema general del sistema inteligente. Fuente: (https://patents.google.com/patent/US20250058968A1/en)* 
</p>

Brimmo, Pilscheur y Glia propusieron un sistema inteligente para la clasificación automática de residuos. El dispositivo cuenta con un compartimento de recepción y un sistema de detección capaz de identificar y localizar los residuos mediante reconocimiento óptico, detección de metales, detección de peso y técnicas de inteligencia artificial. La clasificación puede considerar materiales como papel, plástico y metal. Una característica principal de la propuesta es su mecanismo de separación basado en la posición de los objetos. Después de identificar los residuos, una plataforma móvil puede inclinarse para dirigirlos hacia diferentes contenedores, mientras que mecanismos de retención mantienen en su lugar los objetos que deben ser separados posteriormente. La patente contempla incluso la clasificación simultánea de varios residuos de diferentes tipos, utilizando un sistema compacto que evita depender de grandes bandas transportadoras
Esta propuesta aporta a nuestro proyecto el uso de cámaras e inteligencia artificial para identificar residuos y mecanismos automatizados para su separación, sirviendo como referencia para diseñar el sistema de clasificación de plástico, papel, cartón y metal en nuestro prototipo.

| N.° | Recurso | Tema | Aporte | Variables o características | Valores o rangos |
|---:|---|---|---|---|---|
| 1 | Coyne et al., *Reverse Vending Machine* (US6547055B2) [1] | Recepción, identificación y clasificación automática de envases reciclables. | Demuestra que los envases pueden identificarse mediante códigos ópticos, separarse y compactarse automáticamente. | Código óptico, material, cantidad de envases, aceptación o rechazo, mecanismo de transporte y compactación. | Dos resultados de clasificación: aceptado o rechazado; conteo por tipo de envase; recepción individual o masiva; no establece una capacidad numérica general. |
| 2 | Bardugo y Porat, *Reverse Vending System and Method* (WO2023195003A1) [2] | Identificación y separación de recipientes de plástico, vidrio y metal. | Aporta un sistema que detecta, clasifica, procesa y almacena separadamente los residuos, evitando la mezcla de materiales. | Material, peso, forma, conductividad, código de barras, velocidad de ingreso, altura, ruido y tamaño de trituración. | ≥45 envases/min; ingreso a aproximadamente 1200 mm; ruido promedio <60 dBA; plástico: 10–20 mm; vidrio y aluminio: 20–40 mm. |
| 3 | Brimmo, Pilscheur, Glia. *Waste sorting apparatus and method* (US20250058968A1) | Clasificación automática de residuos mediante detección de objetos e inteligencia artificial. | Propone un sistema que identifica, localiza y clasifica residuos para dirigirlos automáticamente hacia diferentes contenedores mediante un mecanismo de separación basado en la posición. | Cámara/reconocimiento óptico, inteligencia artificial, detección de metales, detección de peso, detección de movimiento, plataforma móvil, mecanismos de retención y contenedores de clasificación. | Hasta 4 tipos de objetos en el ejemplo descrito: papel, plástico, metal y residuo no diferenciado; permite clasificar varios objetos simultáneamente. |


## 3. Tesis

### 3.1. *ENKEI: Sistema de Segregación de Residuos Domésticos para Zonas Urbanas*

Noborikawa Gushiken desarrolló ENKEI, una propuesta de diseño orientada a mejorar la segregación de residuos domésticos en zonas urbanas. La investigación aborda las dificultades relacionadas con la clasificación de los residuos y plantea el desarrollo de un sistema que facilite esta actividad mediante una solución de diseño centrada en el usuario.

El trabajo resulta relevante para nuestro proyecto porque demuestra que el diseño de un sistema puede facilitar la separación de residuos desde el punto donde son generados, reduciendo las dificultades asociadas a su clasificación. Además, el enfoque de la investigación permite considerar aspectos como la facilidad de uso, la organización de los residuos y la interacción del usuario con el sistema.

Para nuestra propuesta, este antecedente puede servir como referencia para definir los requerimientos de un sistema de menor escala destinado a pequeños centros de acopio. A diferencia de ENKEI, nuestro proyecto busca incorporar identificación mediante sensores y/o cámara, pesaje y registro digital de los residuos, de manera que, además de facilitar su clasificación, permita conocer la cantidad y composición de los materiales recibidos.

### Tesis 2

### Tesis 3

| N.° | Recurso | Tema | Aporte al proyecto | Variables/Caracteristicas | Valores/Rango |
|---:|---|---|---|---|---|
| 1 | Noborikawa Gushiken, ENKEI: Sistema de Segregación de Residuos Domésticos para Zonas Urbanas [1] | Segregación de residuos domésticos en zonas urbanas. |Propone un sistema de diseño orientado a facilitar la separación y organización de los residuos.  | Segregación, clasificación de residuos, interacción con el usuario, diseño del sistema y gestión de residuos. | Validación con usuarios finales; la información disponible no especifica valores de precisión o cantidad de residuos procesados. |
| 2 |  | |  |  |  |
| 3 |  |  |  |  |  |


## 4. Productos comerciales

### Producto comercial 1

### Producto comercial 2

### Producto comercial 3

| N.° | Recurso | Tema | Aporte al proyecto | Variables/Caracteristicas | Valores/Rango |
|---:|---|---|---|---|---|
| 1 |  |  |  |  |  |
| 2 |  | |  |  |  |
| 3 |  |  |  |  |  |


## 5. Conclusiones

## 6. Referencias bibliográficas

### Formato Vancouver

