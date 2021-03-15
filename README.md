# Optimización y Documentación

## Index

1. [Hedionez del codigo](#id1)
2. [Analisis del código](#id2)
3. [Refactorización](#id3)
4. [Documentación](#id4)

## Hedionez del codigo <a name="id1"></a>

Este tipo de codigo tambíen se puede llara code smell en ingles 
Este tipo de codigo es fruto de la mala praxis mientras escribimos codigo y tambíen el desorden al redactarlo.
Esto provoca que el codigo tenga problemas en su interior que aveces no son aparentes a primera vista pero si miras en lo profundo del programa veras los errores.
Estos errores pueden ser tanto pequeños bugs como grandes problemas desntro de la estructura del programa. 
Los errores pueden llevar a problemas a la hora de expadir el programa añadiendo nuevo codigo.
Por estos motivos se hace importante la accion de refactorización del codigo para mejorar estas situaciones.

## Analisis del código <a name="id2"></a>

El codigo se puede analizar de diferentes maneras aqui presentaremos los 2 tipos:
- Análisis dinamico: Este tipo de análisis se realiza mientras se ejecuta el codigo por eso es mas lento que el estatico u necessita un proceso completo de testeo.
- Análisis estatico: Este tipo de análisis se raliza sin necessidad de ejecutar el codigo cosa que es ventagosa sobre el dinamico a demas tambíen gracias a eso nos permite detectar errores en fases tempranas de la escritura del codigo.
Dentro de los analizadores de codigo estáticos podemos encontrar los siguientes:
  - **lint** para C
  - **sonar** para Java
  - **JSLint i ESLint** per Javascript

## Refactorización <a name="id3"></a>

La refactorizacion és llamado a el processo que mediante la reestructura del codigo fuente el comportamiento i el resultado del programa no varian.
Para hacer la refactorización hay diferentes tecnicas:
- La renombracion de variables para mejorar la organizacion de estas
- La Modificacion de codigos duplicados para pasarlo a funciones y optimizar el codigo.
- La eliminacion de codigo inalcanzable, redundante, muerto para mejorar el espació i la visualización del codigo.

## Documentación <a name="id4"></a>

Una de las partes mas importantes del codigo és la documentacion que lo explica ja que no sabemos como piensa cada persona al hacer un programa el hecho de que este documentado nos ahorra faena y tiempo de investigacion del codigo.
Dentro de la documentacion se puede diferenciar 3 tipos de documentación segun la funcion que tenga:

- Documentación de código: Este tipo de documentación nos explica que hace la parte del codigo donde esta situada y és muy util a la hora de saber donde estan los errores.
- Documentación técnica: Nos explica como funciona todo el conjunto del programa para facilitar a los pramadores o ingenieros a la hora de modificar algun parametro del el programa o el codigo.
- Documentación de usuario: Este tipo de documentación nos explica de manera mas sencilla i basica lo que hace el programa para que los usuarios entienda de manera mas facil el codigo.

La documentación se puede hacer con muchos formatos como los siguientes:
- HTML
- Markdown
- reStructuredText
- asciiDoc


