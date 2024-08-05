## How Does the Internet Work?
[Link to the article](https://cs.fyi/guide/how-does-internet-work)

### Introduction

- **What is a network?** Before we begin, we need to understand how the internet works. In short, it can be defined as a network of networks. *We can see a network as a set of connected devices*.

- **Where does it come from?** The internet was born from the United States Department of Defense in **1960** as a decentralized communication network that could withstand a nuclear attack.

- **Today** Currently, it is a network that enables communication worldwide, as well as the creation of businesses and other fundamental networks.

### How the Internet Works: An Overview

- **Routers:** Routers allow information to be transmitted from point A to point B, being divided into small packets and verified by each router until it reaches its destination.

- **Protocols:** Protocols ensure that the packets sent are correctly received.

    - **Internet Protocol (IP):** Responsible for routing packets to their destination.

    - **Transmission Control Protocol (TCP):** Ensures that packets arrive reliably and in the correct order.

- There are other technologies and protocols that enable the transmission of information, such as:

    - **Domain Name System (DNS):** It can be said that it assigns a much easier-to-remember name.

    - **Hypertext Transfer Protocol (HTTP):** Allows information to be transferred between devices.

    - **Secure Sockets Layer/Transport Layer Security (SSL/TLS):** Security protocol that verifies the site.

### Basic Concepts and Terminology

- These are the most important technologies or protocols of the web:

    - Packet
    - Router
    - IP Address
    - Domain Name
    - DNS
    - HTTP
    - HTTPS

### The Role of Protocols on the Internet

- It is crucial to understand how network protocols work because if you adhere to the standards, you can communicate with any other service that meets these same standards.

- As a developer, understanding these protocols is fundamental.

### Understanding IP Addresses and Domain Names

IP: **192.168.1.1** --> Domain Name: **google.com** --> DNS translates the domain: **192.168.1.1**

- The IP is a unique identifier.

- The domain name allows people to easily remember its name.

- DNS translates the domain into an IP so the router can understand it and send it to its destination correctly.

### Introduction to HTTP and HTTPS

- **HTTP:** It is the protocol that allows the exchange of information. The client makes a request to the server, and the server returns the requested information. This request process is the HTTP protocol.

- **HTTPS:** It is a more secure protocol than HTTP using the SSL protocol.

    - Adds an extra layer of security to help protect confidential information.

## Creating Applications with TCP/IP

- This protocol allows secure information exchange between applications.

- Key points when working with TCP/IP:

    - **Ports:** Each application is assigned a unique port number so files can arrive without any issues.

    - **Sockets:** The combination of an IP and a port results in a socket, which allows connection between applications.

    - **Connections:** A connection is the communication between two sockets. When there is communication between them, parameters are established to know how the information will be communicated.

- Basic protocols to create an application:

    - HTTP

    - **FTP** File Transfer Protocol

    - **SMTP** Simple Mail Transfer Protocol

## How to Secure Internet Communication with SSL/TLS

- To have a secure application, it is important to understand the SSL/TLS protocol. There are several points to know before using them:

    - **Certificates:** Certificates are third-party signatures that guarantee the trust of this protocol.

    - **Handshake Protocols:** When establishing a client-server connection, they negotiate encryption algorithms and other parameters for information exchange.

    - **Encryption:** Once an agreement is reached, they can transmit encrypted information to ensure it is secure.

## Español 

Claro, aquí tienes el texto con las correcciones de ortografía:

## ¿Cómo funciona el internet?
[Link del artículo](https://cs.fyi/guide/how-does-internet-work)

### Introducción

- **¿Qué es una red?** Antes de comenzar, necesitamos conocer cómo funciona el internet, y en pocas palabras podemos definirlo como una red de redes. *Podemos ver una red como un conjunto de dispositivos conectados*.

- **¿De dónde nace?** El internet nació por el departamento de defensa de los Estados Unidos en el año **1960** como una red de comunicación descentralizada que pudiera resistir un ataque nuclear.

- **Actualidad** En la actualidad es una red que permite la comunicación en todo el mundo, como también la creación de negocios y otras redes fundamentales.

### Cómo funciona Internet: una visión general

- **Enrutadores:** Los enrutadores permiten transmitir la información de un punto A a un punto B, siendo dividida en pequeños paquetes y siendo verificada por cada enrutador hasta que llegue a su destino.

- **Protocolos:** Los protocolos permiten que los paquetes que son enviados se reciban correctamente.

    - **Protocolo de Internet (IP):** Se encarga de enrutar los paquetes para que lleguen a su destino.

    - **Protocolo de control de transmisión (TCP):** Se encarga de que los paquetes lleguen de manera confiable y en el orden correcto.

- Existen otras tecnologías y protocolos que permiten la transmisión de información como:

    - **Sistema de nombre de dominio (DNS):** Se puede decir que se encarga de colocarle un nombre mucho más fácil de recordar a las direcciones IP.

    - **Protocolo de transferencia de hipertexto (HTTP):** Permite transferir información entre dispositivos.

    - **Protocolo Secure Sockets Layer/Transport Layer Security (SSL/TLS):** Protocolo de seguridad que permite la verificación del sitio.

### Conceptos básicos y terminología

- Estas son las tecnologías o protocolos más importantes de la web:

    - Paquete
    - Enrutador
    - Dirección IP
    - Nombre de dominio
    - DNS
    - HTTP
    - HTTPS

### El papel de los protocolos en Internet

- Es fundamental conocer el funcionamiento de los protocolos de la red, ya que si cumples con los estándares podrías comunicarte con cualquier otro servicio que cumpla con estos mismos estándares.

- Como desarrollador, es fundamental la comprensión de estos protocolos.

### Comprender las direcciones IP y los nombres de dominio

IP: **192.168.1.1** --> Nombre de dominio: **google.com** --> DNS traduce el dominio: **192.168.1.1**

- La IP es un identificador único.

- El nombre de dominio permite a las personas recordar fácilmente el nombre de este.

- DNS permite traducir el dominio a una IP para que el enrutador pueda comprenderlo y enviarlo a su destino correctamente.

### Introducción a HTTP y HTTPS

- **HTTP:** Es el protocolo que permite el intercambio de información. El cliente hace una petición al servidor y el servidor retorna la información solicitada. Este proceso de solicitud es el protocolo HTTP.

- **HTTPS:** Es un protocolo más seguro que HTTP mediante el protocolo SSL.

    - Añade una capa más de seguridad y ayuda a proteger información confidencial.

## Creación de aplicaciones con TCP/IP

- Este protocolo permite el intercambio de información entre aplicaciones de manera segura.

- Puntos clave al trabajar con TCP/IP:

    - **Puertos:** A cada aplicación se le asigna un número de puerto único para que los archivos puedan llegar sin ningún problema.

    - **Sockets:** La combinación entre una IP y un puerto da como resultado un socket, este permite la conexión entre aplicaciones.

    - **Conexiones:** Una conexión es la comunicación entre dos sockets. Cuando existe una comunicación entre ellos, se establecen parámetros para saber cómo se comunicará la información.

- Protocolos básicos para crear una aplicación:

    - HTTP
    - **FTP:** Protocolo de transferencia de archivos.
    - **SMTP:** Protocolo simple de transferencia de correo.

## Cómo proteger la comunicación por Internet con SSL/TLS

- Para tener una aplicación segura es importante conocer el protocolo SSL/TLS, existen varios puntos que hay que conocer antes de utilizarlos:

    - **Certificados:** Los certificados son firmas de un tercero que garantizan la confianza de este protocolo.

    - **Protocolos de enlace:** A la hora de la conexión cliente-servidor, estos negocian los algoritmos de cifrado y otros parámetros para el intercambio de información.

    - **Cifrado:** Una vez que llegan a un acuerdo, ya pueden transmitir la información cifrada para que sea segura.

[Link de la lectura](https://cs.fyi/guide/how-does-internet-work)