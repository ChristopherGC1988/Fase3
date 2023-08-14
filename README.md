# Programa de control de inventario
Taller de productividad basada en herramientas tecnológicas Fase IV : Resultados
***
## Tabla de contenido
<a name="Descripción-del-rograma"></a>
#### Descripción del programa
<a name="Problema-identificado"></a>
#### Problema identificado
<a name="Solución "></a>
#### Solución 
<a name="Arquitectura"></a>
#### Arquitectura 
<a name="Descripción-sus-componentes"></a>
#### Descripción sus componente
<a name="Datos-de-la-empresa"></a>
#### Datos de la empresa
***
## Descripción del programa
Es un sistema que permite controlar en el invetario la entrada y salida de mercancia de la fabrica T-SER-MEX
## Problema identificado
La empresa solo posee la información de los productos en listas o notas de ventas (Salidas) y compras (Entradas), en carpetas y almacenadas físicamente para su consulta, en el cual no tiene un registro en el momento sobre las cantidades exactas de hilos con los que cuenta la empresa, que colores tiene en mayor o menor existencia.
***
![image](https://github.com/ChristopherGC1988/Fase3Ejecucion/assets/141608209/c73e1e94-d831-4fb2-ae2e-e30ad477ed72)
***
## Solución 
Al conocer el problema, se solicita a la empresa la autorización para realizar un programa capaz de llevar un control de las entradas y salidas de mercancía, dar de alta o baja un producto con los atributos de Numero Id, color, tamaño, cantidad y precio, a través de aplicaciones web, una bases de datos SQL para el almacenamiento y control de accesos de los usuarios para controlar la seguridad de la información sobre quienes tiene los permisos para consultar la disponibilidad de los productos.
***
![image](https://github.com/ChristopherGC1988/Fase3Ejecucion/assets/141608209/76aba1c2-0791-4ec0-b21b-feb2f97d3a88)
## Arquitectura
El usuario solicita un Request que sera enviado al servidor de aplicacion mediante el uso de Apache Tomcat, donde se conectara con la base de datos MySQL para solicitar la opción, la Base de datos MySQL almacenara la información y respondera al usuario.
***
![image](https://github.com/ChristopherGC1988/Fase3Ejecucion/assets/141608209/7fa92b0d-ea49-4a34-b326-e45e29e6dda7)
## Descripción sus componentes
1.	Usuario: El usuario debe ingresar los datos solicitados para darse de alta y permitir realizar las operaciones de consulta de información.
2.	Producto: Debe tener información del ID, color y cantidad ingresada, para eliminar un producto solo se necesita el ID.
3.	Base de datos: Utilizaremos una MySQL para ingresar la información obtenida del usuario y producto para ser almacenados. 
4.	Interfaz: Utilizaremos una herramienta de Figma para el diseño.
## DATOS DE LA EMPRESA
Nombre de la empresa: T.SER-MEX S.A. DE C.V.
Dirección: Calle Buenavista Esq. Fresno N° 11, Acolman de Nezahualcóyotl, Estado de México, CP: 55880.
Teléfono: 594 957 0650
Correo electrónico: T.ser.mex@gmail.com
Giro: Comercio de fibras, hilos y telas.
N° de empleado: 19


