# Cómo ejecutar Q# en un notebook de jupyter con Azure

Para este curso utilizaré Microsoft Azure.

***Nota:*** Por el momento no he encontrado una forma sin necesidad de utilizar una tarjeta de crédito/débito de ejecutar notebooks de jupyter.


Para este curso utilizaré Azure. Azure provee con un simulador de trabajos cuánticos, además regala [$500USD en créditos para trabajos cuánticos](https://devblogs.microsoft.com/qsharp/explore-quantum-hardware-for-free-with-azure-quantum/) para ejecutar Q# en computadoras cuánticas reales. En este curso enseñaré cómo utilizar el simulador pero la manera de utilizar Q# en computadoras cuánticas reales es exactamente la misma (solo hay un cabmio en la selección de proveedor al cargar Q#). En caso de que sepas de una mejor manera de ejecutar Q# (sin necesidad de registrar ninguna tarjeta de crédito/débito) siéntete libre de abrir un PR con dicha opción.

Para registrarse en azure entra al sitio principal de azure: 
#### Da click en la parte superior derecha en el botón **Free Account**
![imagen](/img/azure/azure1.png)

#### Da click en el botón central **Start Free**
![imagen](/img/azure/azure2.png)

#### Registra una nueva cuenta utilizando una cuenta de correo existente (puede ser gmail) o registrate utilizando github
![imagen](/img/azure/azure3.png)

#### Rellena el formulario con tu información
![imagen](/img/azure/azure4.png)

#### A continuación, te pedirá una tarjeta de crédito/débito para registrarte, hará un cargo de **$20MXN** que te será devuelto para confirmar la tarjeta
![imagen](/img/azure/azure5.png)

#### Una vez confirmada tu tarjeta, tu cuenta será creada y podrás ver un sitio como el siguiente:
![imagen](/img/azure/azure6.png)

#### Da click en el botón `Go to the azure portal` y podrás ver el portal de azure. En la barra de busqueda escribe `Quantum` y da click en `Quantum Workspaces`:
![imagen](/img/azure/azure8.png)

#### Da click en `Create Quantum Workspace` y selecciona `Quick Create` (Esta opción te proveerá con el servicio gratuito de simulación)
![imagen](/img/azure/azure10.png)

#### Escribe un nombre para tu workspace, este debe ser único, te recomiendo utilizar: `quantum-tutorial+TU-NOMBRE` y da click en `Create`(También podemos ver nuestro proveedor gratuito en esta sección):
![imagen](/img/azure/azure20.png)

#### Espera a que tu entorno pase del estado `En proceso` (In progress) a  `Your deployment is complete`:
![imagen](/img/azure/azure21.png)

#### En el sitio principal de tu workspace puedes encontrar tu `Resource_ID` el cual será necesario para ejecutar Q# en un notebook, copialo a tu protapapeles, luego da click en `Notebooks`:
![imagen](/img/azure/azure30.png)

#### Para finalizar, da click en `My Notebooks`-> `Upload new` y sube uno de los notebooks que descargaste de este repositorio encontrados en la ruta `/practica`. Modifica la primera celda de python donde se crea la variable `Targets` escribiendo tu `Resource ID`. Ejecuta la celda:
![imagen](/img/azure/azure40.png)


#### Listo! Tu notebook está listo para ejecutar Q#, puedes continuar al tutorial dentro del notebook :).


### Importante:
Toda sección de los notebooks después