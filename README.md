![Foto bioparque](./assets/bioparque.png)

# Bioparque Unahur

En este caso van a tener que modelar el Bioparque Unahur. En él se encuentran algunas de las especies más autóctonas de nuestro país, 
como el Yaguareté o el Venado de las Pampas. Estos animales están a cargo del *guardaparques*, el cual se encargará de alimentar a los animales
y mantener recintos limpios.

## Modelando el bioparque

Al parque que alberga los animales se le deben poder enviar los siguientes mensajes:
- Poder agregar y sacar animales del recinto (en el caso que necesiten ser tranportados).
- La cantidad de animales que se encuentran en el establecimiento.
- Si el establecimiento está con la cantidad máxima de animales. El maximo de animales que puede albergar el bioparque es 10.
*Aclaracion* : Si en el bioparque ya hay 10 animales, no nos deberia dar la posibilidad de agregar otro sin sacar uno antes.
- Poder preguntarle si el primer animal ingresado y el ultimo tienen un peso par.
- Si es un bioparque con predominancia de animales carnivoros, esto tiene que devolver un True o False.

## El guardaparques

Para modelar el guardabosques debemos tener en cuenta las siguientes cosas:
- Saber su nivel de energia (que arranca en 100), y decrece en 5 cada vez que alimenta a un animal. No puede dar numeros negativos la energia. 
- Alimentar a un animal, la comida va a depender si son *carnivoros* o no. La comida la modelaremos luego.
- Parar a descansar, esto restaura la energia del guarparques (vuelve a 100). Pero solo es posible si todos los animales del bioparque comieron aunque sea una vez.

## Los animales

### Yaguarete

### Venado de las pampas

### Yacaré overo (Caiman)

### Carpincho

