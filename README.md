# Analizador Sintáctico (Implementación usando Objetos)
Este proyecto fue realizado en el lenguage de programación Python, utilizando la versión 3.10 y empleando el entorno de Visual Studio Code para su desarrollo. No obstante, se trabajó a modo de consola e interfaz (utilizando la librería de Pyside2 del entorno QT), realizando esta compactación hibrida para un mejor manejo de la información procesada.

## Instalación
### 1ra forma.
Dar clic en Code, luego en Donwload ZIP y después de que termine la descarga, descomprimirlo.

### 2da forma.
Crear una carpeta, ingresar a git bash y ejecutar el siguiente comando:  git clone https://github.com/OTG-16/Analizador_Sintactico_Objetos.git

### Nota
Es importante resaltar que en este proyecto se utilizan herramientas que deben ser instaladas previamente para el correcto funcionamiento de este analizador. Entre ellas están las siguientes:

- IDE QT Creator
- Librería Pyside2 (Se podría consultar el siguiente video para su instalación https://www.youtube.com/watch?v=INSimE1tW34&list=PLNN_J-C1-lZvgVgnoYXeZo49Boz6CDGTf&index=4 y este otro como introducción para su manejo https://www.youtube.com/watch?v=T0qJdF1fMqo&list=PLNN_J-C1-lZvgVgnoYXeZo49Boz6CDGTf&index=5&t=1533s)
- Librería Colorama (Utlizar en el cmd el comando: pip install colorama)
- Librería Matplotlib (Utlizar en el cmd el comando: pip install matplotlib)
- Librería Networkx (Utlizar en el cmd el comando: pip install networkx)

## Probando el programa
En un principio, al momento de correr el programa este muestra lo siguiente:
![c1](https://user-images.githubusercontent.com/70919055/191636160-03a7d676-64d0-44b7-be3e-5f74b06b9f8a.PNG)

Puede apreciarse una interfaz. Al lado izquierdo se cuenta con un cuadro de texto (ignorar el de la derecha) para ingresar la información a analizar. En la parte de a medias se tiene un botón, este se usa para comenzar con el análisis tanto léxico como sintáctico. Ahora bien, se ingresa en el cuadro correspondiente, el texto "hola+mundo" y se da click en el botón de analizar. Al ser una cadena válida el programa muestra una ventana con el mensaje de "cadena aceptada!" y despliega la siguiente información:
![c2](https://user-images.githubusercontent.com/70919055/191636484-6cb48968-a8cb-4280-a8e6-eebeb2b798ee.PNG)
![c3](https://user-images.githubusercontent.com/70919055/191636516-a339e10d-bf3c-430e-a5b0-45e20e13eaab.PNG)
![f1](https://user-images.githubusercontent.com/70919055/191636654-32853ebc-af0c-4a8e-8e2a-4b0b1f595aae.png)

Ahí se puede ver en la primera parte  que aparece una interfaz y en ella tanto el texto ingresado como el resultado del análisis léxico. En la parte de a medias que viene siendo la de la consola se despliega la tabla LR(1) y su respectivo análisis sintáctico. Además, en la parte de al final se muestra una interfaz con el dibujo del grafo generado en base a la cadena tecleada.

No obstante, se hace otra prueba, pero ahora ingresando la cadena "a+b+c" para su respectivo análisis. Como también es una cadena válida se muestra la ventana con el mensaje de "cadena aceptada!" y también la siguiente información de interfaz y consola tal y como en la corrida anterior pero con sus datos específicos de la cadena analizada.
![c4](https://user-images.githubusercontent.com/70919055/191636563-3ef516d0-7102-4849-bdba-4d1259697b19.PNG)
![c5](https://user-images.githubusercontent.com/70919055/191636610-100e24f0-96f4-48cc-ad49-0e06100690ea.PNG)
![f2](https://user-images.githubusercontent.com/70919055/191636767-c3f1b5dd-ff52-433e-962f-056b7113c3f1.png)



