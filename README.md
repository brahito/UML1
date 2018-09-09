# Descripcion uml taller 1 Diseñando con algoritmos

## Main
- **main(String[]):void**: Con este metodo se ejecuta la aplicacion con processing.
- **Settings():void**:Se usa para definir el tamaño de la aplicacion.
- **Setup():void**:Aqui se definen todas las cosas que se ejecutan al iniciar el codigo.
- **Draw():void**:Este metodo recibe todo lo que se pintara en pantalla ciclicamente.
- **MousePressed():void**:Este metodo permite realizar las acciones que se realizaran con el mouse
- **KeyPressed():void**:Este metodo permite realizar las acciones con las teclas.

## Logica
- **pintar():void**:Se pintan todos los objetos recibidos desde los arraylist que son lluvia, nubes y los personajes. Tambien se hace mover a los objetos que tienen movimiento por si solos.
- **moverMouse():void**:Con este metodo se mueve el personaje principal con el mouse.
- **inteaccionTeclado():void**: