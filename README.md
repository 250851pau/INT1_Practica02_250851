# INT1_Practica02_250851
repositorio
En esta practica aprenderemos a utilizar las herrramientas Git y GitHub para el control 
de versiones de proyectos de desarrollo de software,aplicando principios de buenas prácticas 
en documentacion , Desarrollo Colaborativo Respaldo en la nube del Proyecto


Elaborado por:**Gael Uriel López García** \.
Materia:**Proyecto Integrador** \.
Docente:**M.T.I Marco Antonio Ramírez Hernández** \.
Periodo:*Mayo-Agosto* \.

## Comandos Básicpos para Maquetado de la Documentacion Utilizando el Estandar de Markdown (.md)
---
Markdown es el estandar utilizado para Git y Github , para estilizar (maquetar) la documentacion
del proyecto, lo que permite a usuarios y colaboradores del proyecto entender en contexto y 
operacion del mismo 

### 1. Encabezado y Títulos (HEADES)
Para poder realizar una buena documentación del proyecto debemos distribuir correctamente los 
contenidos, par apóder delimitar o hacer énfasis (enfatizar) es decir resaltar las secciones más importantes 
podemos utilizar lo siguiente :
**EJEMPLOS**

# Encabezado de Nivel 1
## Encabezado de Nivel 2
### Encabezado de Nivel 3
#### Encabezado de Nivel 4
##### Encabezado de Nivel 5
###### ENcabezado de Nivel 6

####### Encabezado de Nivel 7 - *El estandar solo permite 6 niveles para titulos , a partir del septimo
seran presentado como texto plano

### Separadores (SEPARATORS )
Si se desea marcar una separacion visual de los contenidos podemos utilizar una linea horizontal indicanddo 
tres caracteres - continuos , en el  maquetado.
### Título de la sección 
--- 
Texto después del separador 

2### 3. Parrafos (PARAGRAPS)
Son utilizados para prensentar grandes secciones de texto que describen 
detalladamente el contenido de lasw secciones de la documentacion, detallan procesos
explican codigo o contexto teorico.

**EJEMPLO**
<p align="left">Parrafo 1:El tema del aborto es uno de los debates más complejos, apasionados y multifacéticos de la sociedad contemporánea. 
Involucra nociones profundamente arraigadas sobre la moral, la ética, los derechos humanos, la salud pública, la religión y la autonomía personal.
Para comprenderlo en su totalidad, es necesario analizarlo desde sus diversas aristas: la médica, la ética, la legal y la social.

<p align: center;">Parrafo 2: Cuando el aborto es ilegal, las desigualdades sociales se profundizan.
Mientras que las mujeres con recursos económicos pueden acceder a abortos seguros en el extranjero o en circuitos clandestinos de alta calidad,
las mujeres en situación de pobreza recurren a métodos insalubres (introducción de objetos, ingesta de sustancias tóxicas), lo que suele derivar
en infecciones graves, infertilidad o la muerte.

<p align="rigth">Parrafo 3:El debate sobre el aborto es complejo porque confronta visiones del mundo que a menudo parecen irreconciliables.
Mientras que para unos se trata de la defensa biológica y moral de la vida prenatal, para otros es una cuestión de derechos humanos, salud pública y emancipación de las mujeres.
Encontrar puntos de encuentro sigue siendo uno de los mayores desafíos legislativos y sociales de nuestro tiempo.
<p aling= "justify"> Parrafo 4:El debate sobre el aborto es complejo porque confronta visiones del mundo que a menudo parecen irreconciliables.
Mientras que para unos se trata de la defensa biológica y moral de la vida prenatal, para otros es una cuestión de derechos humanos, salud pública y emancipación de las mujeres.
Encontrar puntos de encuentro sigue siendo uno de los mayores desafíos legislativos y sociales de nu


### 4 Enfatizado de Texto
- Texto en negritas : Para realizar texto importante que no sea un titulo por que esto inicialmente esta en negrita
, deberemosen encerrar el texto desdeado entre dobles asteriscos(**)
Ejemplo: Este texto esta en negrita **negrita**
- Texto en Cursiva (Itálico):Para hcer referencia a texto utilizando el formato inclinado o Itálico basará con ecerrar el texto deseado entre dos asteriscos simples 
Ejemplo: Este *texto* Estara *Inclinado*
- Texrto en Cursiva y Negrita :Para lograr esta estabilizacion en la documentacion basta con juntar ambas configuraciones , es decir encerramos en texto en un triple Asterísco (***)

Ejemoplo: ***Este texto esta en Negrita e Itálilco***

- Texto Tachado: En algunas ocaciones es necesario dar formato al texto con un efecto de como es incorrecto, generalmente esta idea se transmite por que el texto esta tachado, es decir con una línea que lo marca por la mitad. Para lograr este efecto tendremos que encerrar el texto entre una doble tilde de (~).

Ejemplo: Se dice haya no ´~~haige~~.

 alt 96 -->``` n ``` \.

Texto Subrayado: En este tipo de formato el texto queda sobre una línea inferior para denotar su relevancia, este formato no tiene un versión rápida en el estándar MARKDOWN, pero dado su similiaridad a HTML podemos utilizar las etiquetas ``` <u> ``` y ``` </u> ```.

Ejemplo: El <u>texto</u> debe estar <u>subrayado</u>.

Texto en Superíndice: En algunas ocaciones se requiere dar formato a fórmulas estadísticas que requiere potencias entre otras aplicaciones, podemos utilizar el tag de HTML el formato. <sup> y **</sup> para delimitar el formato.

Ejemplo: Para elevar x al cuadrado tendriamos lo siguiente x<sup>2</sup>

exto en Subíndice: En el caso de Químaca se utilizbíndices para representar formulas, para ello podemos utilizar el formato de texto con etiqueta HTML.

Ejemplo. La formula del agua es H<sub>2</sub>O.
### 5. Listas
Cuando relizamos documentación utilizando el estándar de MARKDOWN, es común que tengamos que listar elementos, requisitos de hardware, requisitos de software o enumerar pasos de cómo el software debe ser instalado paso a paso, por eso debemos saber como crear listas de las cuales hay de 3 tipos: **Ordenadas (Números)**, **Desordenadas (Viñetas)** y **Mixtas (Viñetas y Números)**.

1. Listas Ordenadas

Estas deberán estar enumeradas con un número seguido por un punto y un espacio en blaco para comenza con el listado.

1. PC
2. Wifi
3. Modém
4. Smartphone
6. Smart TV
5. Tablet

Para reiniciar el contenido se debe poner un alinea de texto si numerilia

2.Listas desordenadas
Estas listas no llevan un número, sino una viñeta (simbolo), y suele listar elementos que no requieren un orden Especifico
- Pan
- Leche
- Huevo
- Azucar

3. Lista mixta
Son aquellas que mezcla ambos elementos 
- 3° A DSM
1. Juan
2. Pedro
3. Alejandra
- 3° B DSM
1. Romina
2. Daniel
- 3° CDSM
1. Yhair 
2. Pancho
3. Lemus 

### 6. BLoque de Código (CODE BLOCKS) o Cit (BLOCK QUOTES)

Estos estilos de texto se utilizan para llamar la atención del lector, en pasos más importantes, realizar alguna reseña o segmentar lineas de código que se deberán  ingresar en una terminal de comadnos  Lineas de ejecución.

- Cuadro de citas (BLOCK QUATES)
SOn cajas estilizadas en colores grises por defecto con margen maás claro.

Para listar las carpetas  y archivos desde una terminal de comandos en el sistema operativo de windows debemos usar el comando:
>C:dir

Despues oprimimos la tecla *Enter*

Tambien podemos utilizar texto multilinea 
**EJEMPLO:**
Pasos para Instalar MySQL

> - Descargar el arthivo instalador desde la página oficial www.mysql.com

> - Instalar el Servidor de Bases de Datos

> - Definir el puerto y contraseña para el usuano **root**

> - Inicializat el servidor de bases de datos

> - Conectarnos a la base datos para venficar que se instalo correctamente

- Bloques de código

Es comun que en la documentacion del proyecto de software demos al usuario un par de instrucciones de como instalar , configurar , desplegar y testear (pruebas), nuestro producto desarrollado. Por tal motivo el estandar markdown nos permite enfatizar estas instrcciones , simulando estar en la terminal del sistema operativo, para delimitar este codigo basta encerraro en triples caracteres de bacltic(acento o tilde inversa```)

Para clonar el proyecto ingresa la siguiente instrucción
```
c:/users/PC-03Desktop> git clone https://github.com/250851pau/INT1_Practica02_250851.git
a diferencia de los bloques de citas, la tipografia y significado asociado no cambian.

### 6. Tablas

En caso de que necesitemos estructurar datos o informaion relevante para la documentacion podremos utilizar el formato tablas, para lo que tenemos quw considerar la estructura base de una tabla:

- Usa | para delimitar las clumnas
- Usa --- para separar las filas del encabezado
EJEMPLO:
|Título 1 | Título 2 | Titulo 3 | Titulo 4┤
|---|---|---|---|
|Fila 1, celda1|fila 2, celda|fila,celda|fila,celda|
|fila,celda|fila,celda|fila,celda|fila,celda|
|fila,celda|fila,celda|fila,celda|fila,celda|

### hipervinculos(links)
Para hacer referencia a documentos internos o externos dentro del repositorio , debemos respetar la siguiente estructura:
[texto que el usiario leera](url a donde se dirigira)"texto  que aparecera cuando pongas el cursor sobre la liga"

Ejemplo:
-ligas externas
[google](httls://google.com/)

-ligas internas 
[Acerca del Autor](./aboutme.md "conoceme mas!")

### 9. Imagenes 

El estandar de markdown nos permite incrustar imagenes dentro de nuestra documentacion lo que nos permirita poner loogtipos , capturas de pantalla o cualquier archivo grafico importante.

La estructura varia un poco de la referencia de hipervinculos, siendo:
```
![texto que el usuario leera](url a donde se encuentra la imagen)
```

Ejemplo
![Dojocat](./imagenes/dojocat.jpg)

Es importante comprender que la resolucion de la imagen sera la original del archivo.

**Tip pro:**
Si el tamaño de la imagen no  ase ajusta a lo que deseas ara tu documento, lo mas recomendable es ajustar el tamaño del archivo original con algun software o procesador de imagenes como :paint Ilustrator, ink o Photoshop. Pero si quieres modificarlo desde el codigo, el estandar no tiene parametros definidos por lo que necesitaremos echar lineas de codigo HTML

cambiando la estructura de maquetado por la etiqueta ```<img>```
Ejemplo:
<img src="./imagenes/dojocat.jpg widith="100" height="50">

###
