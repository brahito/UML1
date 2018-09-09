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
- **inteaccionTeclado():void**:En este metodo se dan todas las interacciones que se pueden hacer con el teclado.

## Personaje
- **pintar():void**:Este metodo pinta al personaje que uno va a controlar.
- **pintarEnemigos():void**:Este metodo pinta a los enemigos que son igual al protagonista.
- **mover():void**:Este metodo permite mover al protagonista.
- **perseguir():void**:Este metodo hace que los enemigos persigan al protagonista.
- **validar():void**:Este metodo valida cuando el protagonista toque un orbe.
- **tocarEnemigo():void**:Este metodo valida cuando el personaje toca a un enemigo.

## Lluvia
- **agua():void**:Esta es la forma de las gotas de lluvia
- **caerLluvia():void**:Este metodo se encarga de darle gravedad a las gotas para que caigan de manera natural.

## Arbolitos
- **pintar(int color):void**:Esta es la forma de los arboles y recibe un color para poder pintar los arboles azules o rojos
- **moverHojas():void**:Este metodo mueve las hojas de los arboles

## Nubes
- **pintar():void**:Este metodo pinta las nubes arriba del lienzo

## Orbe
- **pintar():void**:Este es un metodo abstracto.
- **mover():void**:Hace que los orbes tengan un movimiento igual.

## OrbeRojo
- **pintar():void**:Este metodo pinta el orbe con algunas caracteristicas especificas.
- **mover():void**:Este metodo le da un movimiento particular al orbe en caso de ser necesario.

## OrbeAzul
- **pintar():void**:Este metodo pinta el orbe con algunas caracteristicas especificas.
- **mover():void**:Este metodo le da un movimiento particular al orbe en caso de ser necesario.

## OrbeViol
- **pintar():void**:Este metodo pinta el orbe con algunas caracteristicas especificas.
- **mover():void**:Este metodo le da un movimiento particular al orbe en caso de ser necesario.
