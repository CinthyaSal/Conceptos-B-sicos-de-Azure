# Conceptos Básicos de Azure

## ¿Qué es Azure?.
Azure es un conjunto de servicios en la nube en continua expansión que ayuda a su organización a superar sus retos empresariales actuales y futuros. Azure le da la libertad de crear, gestionar y desplegar aplicaciones en una red global masiva utilizando sus herramientas y marcos favoritos.

 **Microsoft Azure se considera ampliamente como un servicio de plataforma como servicio (PaaS) e infraestructura como servicio (IaaS).**
 
 ## ¿Qué ofrece Azure?.
Azure cuenta con todo lo que se necesita para construir una gran solución. A continuación se enumera las ventajas de Azure.

- **Esté preparado para el futuro**: La innovación continua de Microsoft respalda su desarrollo actual y sus visiones de producto para el futuro.

- **Construya en sus términos**: Tienes opciones. Con un compromiso con el código abierto y la compatibilidad con todos los lenguajes y marcos de trabajo, puede construir como quiera e implementar donde quiera.

- **Opere de forma híbrida sin problemas**: En las instalaciones, en la nube y en el borde: nos reuniremos con usted donde esté. Integre y gestione sus entornos con herramientas y servicios diseñados para una solución de nube híbrida.

- **Confíe en su nube**: Obtenga seguridad desde la base, respaldada por un equipo de expertos, y un cumplimiento proactivo en el que confían empresas, gobiernos y startups.

## Modelos de servicios en la nube.
<table class="table"><caption class="visually-hidden">¿Qué son los modelos de servicios en la nube?</caption>
<thead>
<tr>
<th>Modelo</th>
<th>Descripción</th>
</tr>
</thead>
<tbody>
<tr>
<td><nobr><strong>IaaS</strong></nobr></td>
<td>Este modelo de servicio en la nube es el más parecido a la gestión de servidores físicos. Un proveedor de la nube mantiene el hardware al día, pero el mantenimiento del sistema operativo y la configuración de la red se deja en manos del inquilino de la nube. Por ejemplo, las máquinas virtuales de Azure son dispositivos informáticos virtuales totalmente operativos que se ejecutan en los centros de datos de Microsoft. Una ventaja de este modelo de servicio en la nube es el rápido despliegue de nuevos dispositivos informáticos. Configurar una nueva máquina virtual es considerablemente más rápido que adquirir, instalar y configurar un servidor físico.</td>
</tr>
<tr>
<td><nobr><strong>PaaS</strong></nobr></td>
<td>Este modelo de servicio en la nube es un entorno de alojamiento gestionado. El proveedor de la nube gestiona las máquinas virtuales y los recursos de red, y el inquilino de la nube despliega sus aplicaciones en el entorno de alojamiento gestionado. Por ejemplo, Azure App Services proporciona un entorno de alojamiento gestionado en el que los desarrolladores pueden cargar sus aplicaciones web sin tener que ocuparse de los requisitos físicos de hardware y software.</td>
</tr>
<tr>
<td><nobr><strong>SaaS</strong></nobr></td>
<td>En este modelo de servicio en la nube, el proveedor de la nube gestiona todos los aspectos del entorno de la aplicación, como las máquinas virtuales, los recursos de red, el almacenamiento de datos y las aplicaciones. El inquilino de la nube sólo tiene que proporcionar sus datos a la aplicación gestionada por el proveedor de la nube. Por ejemplo, Office 365 proporciona una versión totalmente funcional de Office que se ejecuta en la nube. Todo lo que tiene que hacer es crear su contenido, y Office 365 se encarga de todo lo demás.</td>
</tr>
</tbody>
</table>

**La siguiente ilustración muestra los servicios que podrían ejecutarse en cada uno de los modelos de servicios en la nube.**

<img src="https://docs.microsoft.com/en-us/learn/azure-fundamentals/intro-to-azure-fundamentals/media/iaas-paas-saas-expanded.png#lightbox" alt="Ilustración que muestra los servicios separados por modelos de servicios en la nube." data-linktype="relative-path">


## Microsoft clasifica los servicios de Azure en 11 tipos principales de productos:

<div align="center"> <img src="https://www.online-tech-tips.com/wp-content/uploads/2012/05/cloud-storage.jpg.webp" height="40%" width="40%"> </div>

- **Cómputo** 💻 : Estos servicios proporcionan máquinas virtuales, contenedores, procesamiento por lotes y acceso a aplicaciones remotas.

- **Web y móvil** 📱 : Estos servicios soportan el desarrollo y despliegue de aplicaciones web y móviles, y también ofrecen funciones para la administración, notificación y generación de informes de API.

- **Almacenamiento de datos** 📂 : Esta categoría incluye las ofertas de base de datos como servicio para SQL y NoSQL, así como almacenamiento en la nube no estructurado y en caché.

- **Analítica** 📈 : Estos servicios proporcionan análisis y almacenamiento distribuidos, así como analítica en tiempo real, análisis de big data, lagos de datos, aprendizaje automático y data warehousing.

- **Redes** 🌐 : Este grupo incluye redes virtuales, conexiones y pasarelas dedicadas, así como servicios para la administración del tráfico, el equilibrio de carga y el alojamiento del sistema de nombres de dominio (DNS).

- **Red de entrega de contenido y medios (CDN)** 📹 : Estos servicios incluyen streaming por demanda, codificación y reproducción e indexación de medios.

- **Integración híbrida** ⚡ : Son servicios para la copia de seguridad de servidores, la recuperación de sitios y la conexión de nubes privadas y públicas.

- **Gestión de identidades y accesos (IAM)**: Estas ofertas garantizan que solo los usuarios autorizados puedan utilizar los servicios de Azure, y ayudar a proteger las claves de cifrado y otra información confidencial.

- **Internet de las cosas (IoT)** 🌐 : Estos servicios ayudan a los usuarios a capturar, monitorear y analizar los datos de IoT, de sensores y otros dispositivos.

- **Desarrollo**: Estos servicios ayudan a los desarrolladores de aplicaciones a compartir código, probar aplicaciones y rastrear posibles problemas. Azure soporta una variedad de lenguajes de programación de aplicaciones, incluyendo JavaScript, Python, .NET y Node.js.

- **Gestión y seguridad**: Estos productos ayudan a los administradores de nube a gestionar su implementación de Azure, a programar y ejecutar trabajos, y a crear automatización. Este grupo de productos también incluye capacidades para identificar y responder a amenazas de seguridad en la nube.

## Computación sin servidor.

Superpuesta a la PaaS, la computación sin servidor permite a los desarrolladores crear aplicaciones más rápidamente al eliminar la necesidad de gestionar la infraestructura. Con las aplicaciones sin servidor, el proveedor de servicios en la nube aprovisiona, escala y gestiona automáticamente la infraestructura necesaria para ejecutar el código. Las arquitecturas sin servidor son altamente escalables y se basan en eventos. Utilizan recursos sólo cuando se produce una función o un desencadenante específico.

Para entender la definición de computación sin servidor, es importante tener en cuenta que los servidores siguen ejecutando el código. El nombre de serverless viene del hecho de que las tareas asociadas con el aprovisionamiento y la gestión de la infraestructura son invisibles para el desarrollador. Este enfoque permite a los desarrolladores centrarse más en la lógica empresarial y ofrecer más valor al núcleo del negocio. La computación sin servidor ayuda a los equipos a aumentar su productividad y a sacar los productos al mercado más rápidamente. Permite a las organizaciones optimizar mejor los recursos y mantenerse centradas en la innovación.

<table class="table"><caption class="visually-hidden">Nube Pública, Privada e Híbrida</caption>
<thead>
<tr>
<th>Modelo de despliegue</th>
<th>Descripción</th>
</tr>
</thead>
<tbody>
<tr>
<td><nobr><strong>Nube Pública</strong></nobr></td>
<td>Los servicios se ofrecen a través de la Internet pública y están disponibles para cualquiera que quiera comprarlos. Los recursos en la nube, como los servidores y el almacenamiento, son propiedad de un proveedor de servicios en la nube y están gestionados por un tercero, y se ofrecen a través de Internet.</td>
</tr>
<tr>
<td><nobr><strong>Nube Privada</strong></nobr></td>
<td>Los recursos informáticos son utilizados exclusivamente por usuarios de una empresa u organización. Una nube privada puede estar ubicada físicamente en el centro de datos de su organización. También puede ser alojada por un proveedor de servicios externo.</td>
</tr
<tr>
<td><nobr><strong>Nube Híbrida.</strong></nobr></td>
<td>Este entorno informático combina una nube pública y una nube privada permitiendo compartir datos y aplicaciones entre ellas.</td>
</tr>
</tbody>
</table>
