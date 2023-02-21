# Cómo ejecutar Q# en un notebook de jupyter con Azure

Para este curso utilizaré Microsoft Azure.

***Nota:*** Por el momento no he encontrado una forma sin necesidad de utilizar una tarjeta de crédito/débito de ejecutar notebooks de jupyter.


Para este curso utilizaré Azure. Azure provee con un simulador de trabajos. En este curso enseñaré cómo utilizar el simulador pero la manera de utilizar Q# en computadoras cuánticas reales es exactamente la misma (solo hay un cambio en la selección de proveedor al cargar Q#). En caso de que sepas de una mejor manera de ejecutar Q# (sin necesidad de registrar ninguna tarjeta de crédito/débito) siéntete libre de abrir un PR o un Issue con dicha opción.

Para registrarse en azure entra al sitio principal de azure: 
#### Da click en la parte superior derecha en el botón **Free Account**
![imagen](/practica/img/azure1.png)

#### Da click en el botón central **Start Free**
![imagen](/practica/img/azure2.png)

#### Registra una nueva cuenta utilizando una cuenta de correo existente (puede ser gmail) o registrate utilizando github
![imagen](/practica/img/azure3.png)

#### Rellena el formulario con tu información
![imagen](/practica/img/azure4.png)

#### A continuación, te pedirá una tarjeta de crédito/débito para registrarte, hará un cargo de **$20MXN** que te será devuelto para confirmar la tarjeta
![imagen](/practica/img/azure5.png)

#### Una vez confirmada tu tarjeta, tu cuenta será creada y podrás ver un sitio como el siguiente:
![imagen](/practica/img/azure6.png)

#### Da click en el botón `Go to the azure portal` y podrás ver el portal de azure. En la barra de busqueda escribe `Quantum` y da click en `Quantum Workspaces`:
![imagen](/practica/img/azure7.png)

#### Da click en `Create Quantum Workspace` y selecciona `Quick Create` (Esta opción te proveerá con el servicio gratuito de simulación)
![imagen](/practica/img/azure8.png)

#### Escribe un nombre para tu workspace, este debe ser único, te recomiendo utilizar: `quantum-tutorial+TU-NOMBRE` y da click en `Create`(También podemos ver nuestro proveedor gratuito en esta sección):
![imagen](/practica/img/azure9.png)

#### Espera a que tu entorno pase del estado `En proceso` (In progress) a  `Your deployment is complete`:
![imagen](/practica/img/azure10.png)

#### En el sitio principal de tu workspace puedes encontrar tu `Resource_ID` el cual será necesario para ejecutar Q# en un notebook, copialo a tu protapapeles, luego da click en `Notebooks`:
![imagen](/practica/img/azure11.png)

#### Para finalizar, da click en `My Notebooks`-> `Upload new` y sube uno de los notebooks que descargaste de este repositorio encontrados en la ruta `/practica`. Modifica la primera celda de python donde se crea la variable `Targets` escribiendo tu `Resource ID`. Ejecuta la celda:
![imagen](/practica/img/azure12.png)


#### Listo! Tu notebook está listo para ejecutar Q#, puedes continuar al tutorial dentro del notebook :).


### Importante:
Toda sección de los notebooks después