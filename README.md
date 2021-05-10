# Azure "Conceptos basicos"
### Reto de la semana uno de InnovacionVirtual

- ## ¿Qué es Azure?  
<img src="imagenes/azure-logo.png" alt="drawing" width="350" />

Microsoft Azure es un servicio de computación en la nube creado por Microsoft para construir, probar, desplegar y administrar aplicaciones y servicios mediante el uso de sus centros de datos.

- ## Servicios que ofrece Azure  
<img src="https://docs.microsoft.com/es-mx/learn/azure-fundamentals/intro-to-azure-fundamentals/media/azure-services.png" alt="drawing" width="550" />  

- Los servivios más usados en microsoft azure son:  
    
    - [proceso](conceptos/proceso.md)
    - [Almacenamiento](conceptos/almacenamiento.md)
    - [Redes](conceptos/Redes.md)
    - [Web](conceptos/proceso.md)
    - [Internet de las cosas](conceptos/IoT.md)
    - [Inteligencia Artificial](conceptos/IA.md)
    - [Bases de datos](conceptos/BD.md)
    - [Movil](conceptos/movil.md)


- ## ¿Qué es la nube?  


<img src="https://tecnoinformatic.com/wp-content/uploads/2020/10/qu%C3%A9-es-azure.png" alt="drawing" width="350" /> 

La computación en la nube, ​ conocida también como servicios en la nube, informática en la nube, nube de cómputo o simplemente "la nube", es un paradigma que permite ofrecer servicios de computación a través de una red, que usualmente es internet.  

Definición por Microsoft:

La definición de la nube puede parecer poco clara, pero, básicamente, es un término que se utiliza para describir una red mundial de servidores, cada uno con una función única. La nube no es una entidad física, sino una red enorme de servidores remotos de todo el mundo que están conectados para funcionar como un único ecosistema. Estos servidores están diseñados para almacenar y administrar datos, ejecutar aplicaciones o entregar contenido o servicios, como streaming de vídeos, correo web, software de ofimática o medios sociales. En lugar de acceder a archivos y datos desde un equipo personal o local, accede a ellos en línea desde cualquier dispositivo conectado a Internet, es decir, la información está disponible dondequiera que vaya y siempre que la necesite.  

- ## Computacion en la nube  

El cloud computing o computación en la nube es un término amplio que abarca todo lo relacionado con los servicios que se encuentran alojados en internet. Entre sus principales características y ventajas podemos destacar:

- Los usuarios pueden aumentar los recursos a demanda, liberando de ese trabajo a los administradores.
- Las empresas pueden incrementar o disminuir los recursos en función de los picos y valles de demanda. Con esto no se hace necesario contratar grandes cantidades de almacenamiento con vistas a futuro si no lo necesitamos en ese momento.
- Se paga sólo por los recursos que se utilizan.
- Los proveedores implementan recursos que garantizan un servicio resistente a fallos que siempre funcione.
- Se facilitan los métodos para migrar datos y servicios de o desde la nube o entre nubes, de forma automática o manualmente por el usuario.

- ## Modelos de nube
<img src="https://www.nephosit.com/wp-content/uploads/2018/04/shutterstock_699701563-1200x800.jpg" alt="drawing" width="400" />   

- ### Nube publica  
Este tipo de nube ofrece sus servicios a cualquier usuario de internet. Sus servidores y almacenamiento pertenecen al proveedor del servicio y el cliente sólo paga generalmente por el espacio de almacenamiento o el ancho de banda que consumen.  

- ### Nube privada  
Estas nubes ofrecen sus servicios a un número limitado de usuarios a través de una red de una empresa. Esta red puede localizarse en las propias instalaciones de la empresa o en las de un proveedor externo.  

- ### Nube hibrida  
Como su propio nombre indica, este tipo de nube es fruto de una combinación de las dos anteriores. En esta se almacenan datos en nubes públicas o privadas en función de las necesidades. Por ejemplo, se puede guardar la información más delicada en la nube privada y la menos crítica en la pública o también usar la nube pública para cuando haya picos de trabajo que exijan un mayor rendimiento.  

- ## Capas de la nube  

<img src="https://dc722jrlp2zu8.cloudfront.net/media/cache/e8/19/e819d19aa207ffc98dbdcf84df581d5a.webp  " alt="drawing" width="400" />   


- ### IaaS (Infrastructure as a Service) o Infraestructura como Servicio
En él, el cliente adquiere del proveedor externo todos los recursos, como son servidores, espacio de almacenamiento en un centro de datos o el equipamiento para redes. Normalmente se lleva a cabo mediante una plataforma de virtualización. De los tres tipos de servicios, es el que mayor control otorga al usuario y, por ende, el que tiene mayor complejidad de uso.

IaaS es ideal para desarrolladores, que pueden escoger Sistema Operativo, cantidad de almacenamiento y otras posibilidades gracias a la total transparencia del servicio. Ejemplos de IaaS son Microsoft Azure y Amazon Web Services.  

- ### PaaS (Platform as a Service) o Plataforma como Servicio  
Con este modelo el proveedor proporciona la plataforma para el desarrollo de aplicaciones, así como su mantenimiento y gestión. En otras palabras, ofrece todo lo que se necesita para completar el ciclo de vida y despliegue de dichas aplicaciones o servicios web.

Aquí el usuario carece de control sobre la infraestructura de almacenamiento o redes. PaaS mantiene la escalabilidad automática, en función de lo que exija la situación. Ejemplo de Paas es Google App Engine, donde los desarrolladores pueden crear sus aplicaciones en Java o Python.  

- ### SaaS (Software as a Service) o Software como Servicio 
En este caso el cliente solamente puede hacer uso de un software que se encuentra alojado en la nube. Por tanto, todo lo relacionado con el mantenimiento, desarrollo, soporte y operaciones es responsabilidad de la empresa que ofrece el servicio.

El cliente usará el sistema alojado por esa empresa, la cual mantendrá la información del cliente en sus sistemas y proveerá los recursos necesarios para explotar esa información. En este grupo podemos poner como ejemplo cualquier servicio web de correo electrónico, como Gmail.