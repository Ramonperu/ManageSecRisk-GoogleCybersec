# Manage Security Risks

Bienvenidos a la guía básica de gestión de riesgos.

Esta guia esta realizada gracias a los conceptos adquiridos gracias al programa de Google

https://www.coursera.org/professional-certificates/google-cybersecurity

## Dominios de seguridad

Existen 8 dominios según el CISSP (es una certificación reconocida a nivel mundial en el campo de la seguridad de la información, otorgada por (ISC)² (International Information System Security Certification Consortium).

### Los 4 primeros dominios

<img align="center" src="/img/1ºimagenn.PNG"  />

#### 1. Security and Risk Management

Los elementos de este dominio son los siguientes:

- **Metas y objetivos de seguridad**
- **Procesos de mitigación de riesgos**
- **Cumplimiento normativo**
- **Planes de continuidad del negocio**
- **Regulaciones legales**
- **Ética profesional y organizativa**

La **Seguridad de la información (InfoSec)** conlleva un conjunto de procesos establecidos para proteger la información:

- **Respuesta ante incidentes**
- **Gestión de vulnerabilidades**
- **Seguridad de las aplicaciones**
- **Seguridad de la nube**
- **Seguridad de las infraestructuras**

#### 2. Asset Security

La seguridad de los activos implica gestionar los procesos de ciberseguridad de los bienes organizacionales, incluyendo el almacenamiento, mantenimiento, retención y destrucción de datos físicos y virtuales.

#### 3. Security architecture and engineering.

Este dominio se centra en la gestión de la seguridad de los datos. Asegurar que existan herramientas, sistemas y procesos efectivos ayuda a proteger los activos y datos de una organización.(SIEM)

Un aspecto importante de este dominio es el concepto de responsabilidad compartida. La responsabilidad compartida significa que todas las personas involucradas asumen un papel activo en la reducción del riesgo durante el diseño de un sistema de seguridad.

- Threat modeling / Modelado de Amenazas
- Least privilege / Principio del menor privilegio
- Defense in depth / Defensa en profundidad
- Fail securely
- Separation of duties / Separacion de funciones
- Keep it simple / Mantenlo simple
- Zero trust / Confianza 0
- Trust but verify / Confia pero verifica

#### 4. Communication and network security

Este dominio se centra en la gestión y seguridad de las redes físicas y las comunicaciones inalámbricas. Esto incluye comunicaciones en el local, remotas y en la nube.

#### 5. Identity and acces management

El dominio de gestión de identidades y accesos (IAM ) se centra en mantener los datos seguros. Lo hace asegurando que las identidades de los usuarios sean confiables y estén autenticadas, y que el acceso a los activos físicos y lógicos esté autorizado. Esto ayuda a prevenir el acceso de usuarios no autorizados, al mismo tiempo que permite a los usuarios autorizados realizar sus tareas.

#### 6. Security assessment and testing

El dominio de evaluación y pruebas de seguridad se centra en identificar y mitigar riesgos, amenazas y vulnerabilidades. Las evaluaciones de seguridad ayudan a las organizaciones a determinar si sus sistemas internos están seguros o en riesgo.(PENTESTING, Auditorias)

#### 7. Security Operations

El dominio de operaciones de seguridad se centra en la investigación de una posible violación de datos y en la implementación de medidas preventivas después de que haya ocurrido un incidente de seguridad. Esto incluye el uso de estrategias, procesos y herramientas como:

- Capacitación y concienciación
- Informes y documentación
- Detección y prevención de intrusiones
- Herramientas SIEM
- Gestión de registros
- Gestión de incidentes
- Guías de acción (playbooks)
- Forense post-brecha
- Reflexión sobre las lecciones aprendidas

#### 8. Software development security

Uso de prácticas y directrices de programación segura para crear aplicaciones seguras, tener aplicaciones seguras ayuda a ofrecer servicios seguros y confiables, lo que protege a las organizaciones y a sus usuarios.

La seguridad debe incorporarse en cada elemento del ciclo de vida del desarrollo de software, desde el diseño y desarrollo hasta las pruebas y el lanzamiento. Para lograr la seguridad, el proceso de desarrollo de software debe tener en cuenta la seguridad en cada paso



### Gestionar amenazas, riesgos y vulnerabilidades comunes

<img align="center" src="/img/2ºimagenn.PNG"  />

Un objetivo principal de las organizaciones es proteger los activos. Un activo es un elemento percibido como valioso para una organización. Los activos pueden ser digitales o físicos. 

- Ejemplos de activos digitales:

  - Números de Seguridad Social (SSNs) o números de identificación nacional únicos asignados a individuos

  - Fechas de nacimiento
  - Números de cuenta bancaria
  - Direcciones postales

- Ejemplos de activos físicos incluyen:

  - Quioscos de pago

  - Servidores
  - Computadoras de escritorio
  - Espacios de oficina

Algunas estrategias comunes utilizadas para gestionar riesgos incluyen:

1. **Aceptación**: Aceptar un riesgo para evitar interrumpir la continuidad del negocio.
2. **Evitación**: Crear un plan para evitar el riesgo por completo.
3. **Transferencia**: Transferir el riesgo a un tercero para que lo gestione.
4. **Mitigación**: Reducir el impacto de un riesgo conocido.

Las organizaciones implementan procesos de gestión de riesgos basados en marcos ampliamente aceptados para ayudar a proteger activos digitales y físicos de diversas amenazas, riesgos y vulnerabilidades. Ejemplos de marcos: **Marco de Gestión de Riesgos del Instituto Nacional de Estándares y Tecnología (NIST RMF)**

<img align="center" src="/img/3ºimagenn.PNG"  />



#### **Amenazas**

Una amenaza es cualquier circunstancia o evento que puede afectar negativamente los activos. Las amenazas comunes incluyen:

- **Amenazas internas**: Miembros del personal o proveedores que abusan de su acceso autorizado para obtener datos que pueden perjudicar a una organización.
- **Amenazas persistentes avanzadas (APT)**: Un actor de amenazas mantiene acceso no autorizado a un sistema durante un período prolongado.

#### **Riesgos**

Un riesgo es cualquier cosa que pueda afectar la confidencialidad, integridad o disponibilidad de un activo. Una fórmula básica para determinar el nivel de riesgo es que el riesgo es igual a la probabilidad de una amenaza.

Factores de riesgo:

- **Riesgo externo**: Cualquier cosa fuera de la organización que tenga el potencial de dañar los activos organizacionales, como actores de amenazas que intentan acceder a información privada.
- **Riesgo interno**: Un empleado actual o anterior, proveedor o socio de confianza que represente un riesgo de seguridad.
- **Sistemas heredados**: Sistemas antiguos que pueden no ser tenidos en cuenta o actualizados, pero que aún pueden afectar los activos, como estaciones de trabajo o sistemas mainframe antiguos. Por ejemplo, una organización podría tener una máquina expendedora antigua que acepta pagos con tarjeta de crédito o una estación de trabajo que todavía está conectada al sistema contable heredado.
- **Riesgo de múltiples partes**: La subcontratación de trabajo a proveedores externos puede darles acceso a propiedad intelectual, como secretos comerciales, diseños de software e invenciones.
- **Cumplimiento/licencias de software**: Software que no está actualizado o en cumplimiento, o parches que no se instalan a tiempo.

#### **Vulnerabilidades**

Una vulnerabilidad es una debilidad que puede ser explotada por una amenaza. 

Por lo tanto, las organizaciones necesitan inspeccionar regularmente las vulnerabilidades dentro de sus sistemas. Ejemplos

- ProxyLogon: Una vulnerabilidad preautenticada que afecta al servidor de Microsoft Exchange. Esto significa que un actor de amenazas puede completar un proceso de autenticación de usuario para desplegar código malicioso desde una ubicación remota.
- ZeroLogon: Una vulnerabilidad en el protocolo de autenticación Netlogon de Microsoft. Un protocolo de autenticación es una forma de verificar la identidad de una persona. Netlogon es un servicio que garantiza la identidad de un usuario antes de permitir el acceso a la ubicación de un sitio web.
- Log4Shell: Permite a los atacantes ejecutar código Java en la computadora de otra persona o filtrar información sensible. Lo hace permitiendo a un atacante remoto tomar el control de dispositivos conectados a internet y ejecutar código malicioso.
- PetitPotam: Afecta al Administrador de Red de Tecnología Nueva (NTLM) de Windows. Es una técnica de robo que permite a un atacante basado en LAN iniciar una solicitud de autenticación.
- Fallos de registro y monitoreo de seguridad: Capacidades insuficientes de registro y monitoreo que resultan en que los atacantes exploten vulnerabilidades sin que la organización lo sepa.
- Falsificación de solicitudes del lado del servidor: Permite a los atacantes manipular una aplicación del lado del servidor para acceder y actualizar recursos backend. También puede permitir a los actores de amenazas robar datos.
