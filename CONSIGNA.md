# Enunciado

**Retrocedemos en el tiempo, y estamos en el año 2004**. La empresa **Casio**, una empresa
multinacional japonesa fabricante de electrónica de consumo con sede en Tokio, introduce al
mercado la primera calculadora que permitió la visualización de expresiones de fracciones,
exponentes, logaritmos, potencias y raíces cuadradas, etc. En Argentina tiene muchas quejas por
parte de sus usuarios, con respecto al formato de datos de sus operaciones. Por este motivo, desean
innovar usando calculadoras digitales que requieren de programación y para ello, los han contratado
a ustedes. Así, su misión consiste en diseñar y desarrollar un algoritmo que tenga en cuenta el
siguiente manejo de la calculadora:

1. El usuario presiona el botón de activación (_On_), y de esta manera se enciende la calculadora.

2. Las operaciones de la calculadora pueden ser unarias o binarias, según el número de operandos
   que intervienen en cada operación. Las operaciones suma, resta, multiplicación y división, son
   operaciones binarias (2 operandos para cada operación) que se escriben en notación infija. Ejemplo:
   1 + 2 (2 operandos o más, con el operador en medio). En cambio, el operador = es unario, porque
   evalúa la operación que aparece escrita en pantalla, y muestra el resultado en la pantalla.

3. El menú de opciones tiene las siguientes funcionalidades: 1. Calculadora Clásica, 2. Calculadora
   de Fracciones, 3. Calculadora de Conversiones, 4. Salir (Off).

4. El usuario revisará las opciones y en base a su requerimiento, selecciona una opción.

5. Si el usuario selecciona la opción 1, le permitirá realizar sus operaciones, teniendo cuatro
   opciones: “Suma”, “Resta”, “Multiplicación”, o “División” de dos o más números que pueden ser
   enteros o reales (con parte entera, punto, y parte decimal). Para evaluar y mostrar el resultado de
   cualquiera de las operaciones se debe presionar el botón “ = “. Luego de ello se finaliza la operación.
   **En caso de que requiera realizar otra operación deberá regresar al paso c**.

6. Si el usuario selecciona la opción 2, le permitirá realizar sus operaciones, teniendo cuatro
   opciones: “Suma”, “Resta”, “Multiplicación”, o “División” de dos o más fracciones. Para evaluar y
   mostrar el resultado de cualquiera de las operaciones se debe presionar el botón “ = “. Luego de
   ello se finaliza la operación.
   **En caso de que requiera realizar otra operación deberá regresar al paso c**.

7. Si el usuario selecciona la opción 3, le permitirá realizar conversiones de números enteros
   positivos de a lo sumo 4 dígitos, teniendo tres opciones: “Binario”, “Hexadecimal” u “Octal” de un
   número dado en el sistema de numérico decimal. Para evaluar y mostrar el resultado de la
   conversión se debe presionar el botón “bin“, “hex” u “oct”. Luego de ello se finaliza la operación.
   **En caso de que requiera realizar otra operación deberá regresar al paso c**.
8. Si el usuario selecciona la opción 4, se finaliza la operación y se apaga la calculadora (_Off_).

## Notas

Para poner a prueba el programa implementado se probará con la siguiente operación.

- Calculadora de Fracciones:

        1/2 + 3/5 = 11/10

- Calculadora de Conversiones
  59 a hexadecimal = 3B
