# Tutorial de programación cuántica
## Prerequisitos

Este tutorial es teórico y técnico, asume que tienes conocimientos previos en:
- Un lenguaje de programación (preferentemente python)
- Bases del funcionamiento de una computadora (bits, transistores, compuertas lógicas)

Este tutorial asume que no tienes conocimiento de la física cuántica, pero una introducción nunca cae mal.

[El orígen de la mecánica cuántica](https://www.youtube.com/watch?v=g_IaVepNDT4)

## Introducción

Actualmente toda la tecnología que nos rodea esta contruida utilizando los principios de la física clásica. Se utilizan electrones, transistores, compuertas lógicas y otros componentes para lograr crear chips y computadoras utilizadas por otras computadoras o por humanos.

La física cuántica describe como se comportan los objetos reducidos en tamaño como los átomos y electrones. Este comportamiento es totalmente diferente a lo que estamos acostumbrados en la vida diaria y puede llegar a ser contraintuitivo.

La **computación cuántica** es una rama de la computación que pretende cambiar la manera en la que pensamos de la tecnología. No solo implica utilizar un nuevo lenguaje de programación para crear programas, sino que también hace uso de propiedades de la física cuántica como la superposición, interferencia y entrelazamiento cuántico. Utiliza estas propiedades para crear computadoras más rápidas y poderosas, resolviendo problemas de una manera **TOTALMENTE** diferente a como estamos acostumbrados.

## ¿Por qué utilizar la física cuántica?
La ley de Moore establece que el número de transistores por dispositivo se duplicará cada dos años. Esto implica el tener que crear componentes más pequeños y hemos llegado a un punto en el que las leyes de la física cuántica están interfiriendo con el funcionamiento de nuestras computadoras. Además, teóricamente, podemos utilizar propiedades de la físca cuántica para resolver problemas a los que aún no tenemos soluciones óptimas como la **busqueda, simulación, factorización y encriptación segura.**

### Aplicaciones
- **Química:** Simulacion molecular para ayudar en el desarrollo de vacunas (más rápido, seguro y efectivo)
- **Ciberseguirdad:** Creación de redes virtualmente impenetrables.
- **Cambio climático:** Optimizar la infraestructura de energía limpia, paneles solares, ciencia de materiales para desarrollar tecnología de captura de carbono.

## Ecosistema actual

Hoy en día las computadoras cuánticas no son escalables o viables de manera comercial. Se estima que haya una mayor adaptación en 10 a 15 años.


## Componentes

### Qubits

Un **qubit es la unidad fundamental** de una computadora cuántica, es equivalente a un bit en la computación clásica. Mientras que los bits solo pueden tener un valor de 0 o 1, un qubit piuede tener una combinación de estos dos estados.

Algunos ejemplos de qubits son fotones, [iones atrapados](https://es.wikipedia.org/wiki/Trampa_i%C3%B3nica), [qubits topológicos](https://mundocontact.com/microsoft-desarrolla-el-primer-qubit-topologico/). Cada una de estas implementaciones requiere hardware específico y cada una tiene ventajas y desventajas.

#### Notación KET
| Estado de Qubit | Representación en notación KET  |
|-------------------|------|
| Qubit en estado 1 | 1    |
| Qubit en estado 0 | 0    |
| Superposición 1   | \|1> |
| Superposición 0   | \|0> |

### Compuertas cuánticas

Como una compuerta lógica, las compuertas cuánticas cambian el estado de un qubit. 

### Circuitos Cuánticos

Un circuito cuántico es una secuencia de compuertas cuánticas. Estos circuitos reciben un input, procesan el input utilizando las compuertas y obtienen un output.

### Algoritmos cuánticos

Un algoritmo cuántico es un circuito disñado para resolver un problema. Se utilizan las propiedades de la  física cuántica para resolverlos de manera veloz y eficiente.

### Protocoles cuánticos
Un protocolo es un conjunto de reglas que utilizan la física cuántica para permitir a los dispositivos electronicos comunicarse entre ellos.

### Protocolo vs algoritmo

Un algoritmo es equivalente a una receta, donde se siguen ciertas instrucciones para llegar a un resultado final. Un protocolo es equivalente a un contrato, donde varias entidades se comportan según el contrato para beneficiarse mutuamente.

## La dualidad de Partícula-Molécula

Los objetos cuánticos como los **electrones y fotones (luz) muestran propiedades de partículas y de ondas.**

**Propiedades de una onda:** Las ondas como el sonido o el agua viajan a una cierta velocidad. Cuando interacúan entre ellas, forman patrones llamados interferencia. Las ondas se pueden sumar o cancelar entre ellas.
**Propiedades de la partícula:** LAs partículas como una pelota tienen masa, tienen una ubicación y viajan a una velocidad dada.

El experimento de la doble rendija muestra cómo los objetos cuánticos se comportan como una onda y como una partícula. (https://en.wikipedia.org/wiki/Double-slit_experiment)


## Propiedades cuánticas

Este comportamiento es contraintuitivo a lo que comunmente conocemos:

1. **Superposición.** Los objetos cuánticos pueden estar en una combinación de estados. (https://es.wikipedia.org/wiki/Gato_de_Schr%C3%B6dinger)

2. **Interferencia.** Los posibles estados de un objeto cuántico pueden cancelarse o sumarse. 

3. **Entrelazamiento.** Dos objetos cuánticos están entrelzados si el estado de un objeto depende del estado del otro objeto. Si conocemos el estado de uno de los dos objetos, podemos conocer el estado del otro objeto. El entrelazamiento cuántico no depende de la distancia. El entrelazamiento es una porpiedad de multiple objetos (dos o más).

4. **Medición.** Los resultados de medir un objeto cuántico pueden ser aleatorios. No podemos predecir el resultado exacto de una medición. El estado de un objeto cuántico puede cambiar como resultado de ser medido.


