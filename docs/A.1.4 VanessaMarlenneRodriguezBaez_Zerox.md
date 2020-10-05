# Sensores

## :trophy: A.1.4 Actividad de aprendizaje

## Objetivo

Realizar un sensor medidor de temperatura a través de un circuito electrónico, utilizando un simulador, y  un **Transistor LM35 o algún 
sustituto** lineal de temperatura y un **amplificador operacional LM358P**.

## :blue_book: Instrucciones

- Para la entrega del documento de su actividad, se deberán incluir los siguientes apartados
   - **Portada**, información del alumno, asesor, carrera, materia, fecha,..
   - **Introducción**, una breve descripción de que tratara el tema.
   - **Desarrollo**, que deberá incluir todos los puntos solicitados en la actividad.
   - **Conclusiones** por cada uno de los integrantes del equipo.
   - **Bibliográfia**, el cual debe estar al estilo camuflaje, es decir dentro del cuerpo del desarrollo como etiqueta a enlaces cada vez 
que mencione el concepto.
- Toda actividad o reto se deberá realizar utilizando el estilo **MarkDown con extension .md** y el entorno de desarrollo VSCode, 
debiendo ser elaborado como un documento **single page**, es decir si el documento cuanta con imágenes, enlaces o cualquier documento 
externo debe ser accedido desde etiquetas y enlaces, y debe ser nombrado con la nomenclatura **A1.4_NombreApellido_Equipo.pdf.**
- Es requisito que el .md contenga una etiqueta del enlace al repositorio de su documento en GITHUB, por ejemplo **Enlace a mi GitHub** y 
al concluir el reto se deberá subir a github.
- Desde el archivo **.md** exporte un archivo **.pdf** que deberá subirse a classroom dentro de su apartado correspondiente, sirviendo 
como evidencia de su entrega, ya que siendo la plataforma **oficial** aquí se recibirá la calificación de su actividad.
- Considerando que el archivo .PDF, el cual fue obtenido desde archivo .MD, ambos deben ser idénticos.
- Su repositorio ademas de que debe contar con un archivo **readme**.md dentro de su directorio raíz, con la información como datos del 
estudiante, equipo de trabajo, materia, carrera, datos del asesor, e incluso logotipo o imágenes, debe tener un apartado de contenidos o 
indice, los cuales realmente son ligas o **enlaces a sus documentos .md**, _evite utilizar texto_ para indicar enlaces internos o externo.
- Se propone una estructura tal como esta indicada abajo, sin embargo puede utilizarse cualquier otra que le apoye para organizar su 
repositorio.
  
```
- readme.md
  - blog
    - C0.1_x.md
    - C0.2_x.md
  - img
  - docs
    - A0.1_x.md
    - A0.2_x.md
    - A1.2_x.md
    - A1.3_x.md
```

## :pencil2: Desarrollo

Se sugiere para el desarrollado de la presenta actividad, utilizar uno de los siguientes simuladores: [Autodesk Tinkercad](https://www.
tinkercad.com/), [Virtual BreadBoard](http://www.virtualbreadboard.com/), [Easy EDA](https://easyeda.com/) por lo cual habrá que 
familiarse antes, e incluso instalarse o registrarse dentro de la plataforma.

1. Utilice el siguiente listado de materiales para la elaboración de la actividad

    | Cantidad | Descripción                         |
    | -------- | ----------------------------------- |
    | 1        | Sensor temperatura LM35 o sustituto |
    | 1        | Potenciómetro 10k                   |
    | 2        | Resistencias de 220                 |
    | 1        | Amplificador LM358P                 |
    | 1        | Fuente de alimentación de 5Volts.   |

    Para mayor información acceder a los siguientes enlaces:

    - [Sensor LM35](https://naylampmechatronics.com/sensores-temperatura-y-humedad/234-sensor-de-temperatura-analogico-lm35.html)
    - [AmOp LM358P](https://www.digikey.com/product-detail/es/texas-instruments/LM358P/296-1395-5-ND/277042)

2. Basado en la imagen ensamble mediante un simulador el circuito electrónico etapa 1, colocando el transistor LM35 en la posición 
indicada. 

<p align="center">
    <img alt="Logo" src="../img/C1.x_CircuitoLM35_Etapa1.png" width=250 height=250>
</p>

3. Calcule, mida y registre los valores solicitados para Vout1, bajos las 3 condiciones requeridas en la tabla anexa.
4. Basado en la imagen ensamble en el simulador el circuito electrónico etapa 2, coloque el amplificador operación LM358 en la posición 
indicada.
5. Conecte la terminal llamada Vout1 Etapa1 a la terminal Vout Etapa 2.
   

<p align="center">
    <img alt="Logo" src="../img/C1.x_CircuitoLM358_Etapa2.png") width=400 height=300>

</p>

6. Como se puede observar en el circuito Etapa 2, la resistencia R3 corresponde a un potenciómetro. **Que valor deberá tener R3 para 
lograr obtener 5 veces el valor de Vout1 en Vout2?**
   
7. Calcule, mida y registre los valores solicitados para Vout2, bajos las 3 condiciones requeridas en la tabla anexa.

| Numero | Condición        | Voltaje Vout1 medido | Voltaje Vout2 medido | Voltaje en R2 medido | Temperatura calculada |
| ------ | ---------------- | -------------------- | -------------------- | -------------------- | --------------------- |
| 1      | Condición mínima |
| 2      | Condición media  |
| 3      | Condición máxima |

8. Grafique a través de los valores registrados en la tabla anterior de tal manera que se pueda observar el comportamiento lineal del 
componente LM35, considerando que existe una relación voltaje-temperatura.
  
<p align="center">
    <img alt="Logo" src="../img/C1.x_ComportamientoLinealLM358.png" width=600 height=350>
</p>

___

### :bomb: Rubrica

| Criterios     | Descripción                                                                                  | Puntaje |
| ------------- | -------------------------------------------------------------------------------------------- | ------- |
| Instrucciones | Se cumple con cada uno de los puntos indicados dentro del apartado Instrucciones?            | 10      |  | 5 |
| Desarrollo    | Se respondió a cada uno de los puntos solicitados dentro del desarrollo de la actividad?     | 60      |
| Demostración  | El alumno se presenta durante la explicación de la funcionalidad de la actividad?            | 20      |
| Conclusiones  | Se incluye una opinión personal de la actividad  por cada uno de los integrantes del equipo? | 10      |

:house: [Ir a sensores](../docs/D1.0_Sensores.md)
