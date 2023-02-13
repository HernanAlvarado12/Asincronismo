#Que es el asincronismo?
Javasript es un lenguaje que es sincrono por defecto, haciendo uso de un solo hilo (thread), es decir, las tareas se ejecutan de forma secuencial, una tarea inicia cuando una tarea previa se ha finalalizado. Por otras parte el asincronismo permite que las tareas o procesos se puedan realizar mas tarde.

Dentro de los lenguajes de programacion se hace uso de dos memorias para la manipulacion y asignacion de variables y objetos, las cuales se llaman stack y heap, estas dos almacenan los datos dependiendo de su tipo. El stack es la parte en donde se almacenan los datos primitivos y tiene una referencia hacia el heap de los objetos que estemos almacenados, por otra parte el heap es el lugar en donde se almacenan los objetos en si.

Datos primitivos Javascript
    Number
    String
    Boolean
    BigInt
    Symbol
    undefined

#EventLoop
Es el bucle de eventos de eventos que espera y distribuye eventos dentro de un programa.

    #Memory Heap => Lugar donde los objetos son asignados
    
Task Queue => Cola de tareas, se maneja con la concurrencia, 

#Callbacks
Es una función que se pasa como argumento de otra función para que esta la invonque dentro de su logica.

#Promesas
Es una función no bloqueante y asincrona la cual nos permite retornar un valor en el futuro.

#Asyn&Await
Permite estructurar una función asincrónica sin bloqueo de una manera similar como si fuera sincrono.