## ¿Para qué sirve el comando npm init?

>El comando npm init se utiliza para configurar un nuevo paquete npm o actualizar uno existente. Este comando crea o actualiza un archivo package.json y ejecuta cualquier otra operación relacionada con la inicialización.

>Si se omite el inicializador (es decir, simplemente se llama a npm init), init recurrirá al comportamiento de inicialización heredado. Te hará una serie de preguntas y luego escribirá un package.json para ti. Intentará hacer suposiciones razonables basadas en campos existentes, dependencias y opciones seleccionadas. Es estrictamente aditivo, por lo que mantendrá cualquier campo y valor que ya estuvieran establecidos.

También se puede usar ***-y / --yes*** para omitir el cuestionario por completo. Si pasas ***--scope***, creará un paquete con alcance.

>Este archivo package.json es fundamental para cualquier proyecto npm, ya que contiene metadatos específicos del proyecto, como el nombre del proyecto, la versión, la descripción, los scripts, las dependencias, entre otros. Estos metadatos ayudan a identificar el proyecto y actúan como una línea de base para que los usuarios obtengan información al respecto.

## ¿Cómo es que se instalan paquetes con yarn?

>Para instalar un paquete con Yarn, podemos usar el comando  ```yarn add ``` "nombre-del-paquete" . Este comando descargará el paquete y lo agregará al archivo package.json.


## ¿Cómo es que se borran paquetes con yarn?

>Para eliminar un paquete con Yarn, podemos usar el comando  ```yarn remove ``` "nombre-del-paquete". Este comando eliminará el paquete de tus dependencias directas y actualizará tus archivos package.json y yarn.lock en el proceso.

## ¿Hay algún equivalente en yarn que haga lo mismo que npm init?

>Sí, Yarn tiene un comando equivalente a npm init que es yarn init. Al igual que npm init, yarn init se utiliza para configurar un nuevo paquete o actualizar uno existente.

## ¿Cómo elimino una rama creada en git? Crea una nueva rama llamada feature/QA, para posteriormente borrarla.

Para eliminar una rama en git, primero debemos asegurarnos de no estar en la rama que deseamos eliminar.
Estos serian los pasos para crear y luego eliminar una rama llamada feature/QA:

### Para crear la rama
```git branch feature/QA```

### Para cambiar a la rama master
```git checkout master```

### Para eliminar la rama local
```git branch -d feature/QA```

## ¿Por qué debería de usar la ramificación en proyectos?

La ramificación en proyectos es muy útil por varias razones:
>*Nos permite crear una copia paralela del código para desarrollar cambios sin afectar la versión estable.
>>*Ademas que nos facilita el trabajo en equipo, ya que cada miembro puede trabajar en su propia rama sin interferir con el trabajo de los demás.
>>>*Mejora la eficacia del equipo al permitir que los cambios se integren poco a poco con la rama principal.
>>>>*Ayuda a mantener un historial limpio y comprensible del proyecto.

## Usted recibió un ticket [SEM-005] y una vez terminado el trabajo usted decide crear una rama para un posterior PR. ¿Qué nombre pondría a la rama al momento de crearla?

Es importante mencionar que al nombrar las ramas, es importante que el nombre sea descriptivo y siga un formato consistente. En nuestro caso, podrímos nombrar la rama basándonos en el ticket que recibimos. En este caso,llamaremos a la rama ***ticket-SEM-005***. Esto hace que sea fácil identificar a qué ticket está asociada la rama.

### La implementacion de este laboratorio fue de gran ayuda, la explicacion fue completa lo suficiente para entende acerca de los pull request el cual sera de gran ayuda para mas adelante dado que se trabajara mas seguido con este tema.
