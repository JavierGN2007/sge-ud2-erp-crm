# SECCIÓN 1: DATOS
* **Propietario:** JavierGN2007
* **Propietario:** 15.- Agencia de viajes "Rutas del Mundo"
* **Palabra del día:** Compañero



# SECCIÓN 2: LICENCIA Y MODELOS

## Diferencia entre Software Libre, Código Abierto y Propietario
* **Software Libre (FSF):** Se centra en las libertades del usuario, otorgando libertades de uso, estudio, modificación y distribución.
* **Código Abierto (OSI):** Es un modelo que está basado en la colaboración abierta, siendo su código fuente consultable, modificable y distribuible por cualquiera, aunque su software puede implicar costes adicionales
* **Software Propietario:** El código fuente está cerrado y es exclusivo para una empresa o autor. El usuario tendría que comprar la licencia de uso, pero sin poder modificarlo o compartirlo

## ¿Por qué "libre" no significa "gratuito"?

En inglés es usada la palabra "Free" para referirse a este tipo de software pero "Free", en este caso, se traduciría a "libertad", no a "Free" de precio. Por eso existe la frase "Free as in speech, not as in free beer".

## ¿Qué implica en la práctica una edición Community frente a una Enterprise?

La **edición Community** es la versión gratuita de código abierto, hecha para desarrolladores o estudiantes, la cual no incluye funciones avanzadas de seguridad o escalabilidad y el soporte técnico lo llevan los foros de la comunidad. Por otra parte, la **edición Enterprise** es una versión de pago hecha para grandes empresas, incluyendo el código base con módulos avanzados y con un buen soporte técnico

## Copyleft y AGPL

Copyleft es una práctica legal que permite a cualquier persona copiar, modificar y compartir una obra creativa. 

AGPL es una licencia de software libre y de código abierto que obliga a compartir el código fuente modificado cuando el programa se utiliza a través de una red.

Tanto copyleft como AGPL tienen un impacto directo y crítico cuando el software se utiliza o se distribuye a través de la red. Su principal consecuencia es la obligación o no de liberar el código fuente de modificaciones a los usuarios finales.



# SECCIÓN 3: FICHAS TÉCNICAS

* **[Odoo Community](https://www.odoo.com/es_ES/page/community) (ERP Libre):**
  * **Licencia exacta:** Licencia LGPLv3
  * **Versión vigente:** Versión 19.0
  * **Lenguaje del servidor:** Python
  * **SGBD compatibles:** Postgre SQL
  * **Modalidad:** Se puede instalar tanto en servidor local como en la nube
  * **Módulos principales:** CRM, ventas, compras, inventario, contabilidad, eCommerce, etc...
  * **Requisitos:** 2 núcleos a 2 GHz, 4Gb de RAM, 20Gb de espacio libre, ancho de banda de 10 Mbps

* **[Microsoft Dynamics 365](https://learn.microsoft.com/es-es/dynamics365/) (ERP Propietario):**
  * **Licencia exacta:** Licencia Propietaria Comercial
  * **Versión vigente:** 2026 Release Wave 1
  * **Lenguaje del servidor:** X++, AL y C#, dependiendo según el módulo utilizado
  * **SGBD compatibles:** Microsoft SQL Server y Azure SQL Database
  * **Modalidad:** Se puede instalar en la nube
  * **Módulos principales:** Marketing, ventas, finanzas, recursos humanos, etc...
  * **Requisitos:** Navegadores como Microsoft Edge o Google Chrome, conexión estable de banda ancha y 4Gb de RAM

* **[Fat Free CRM](https://github.com/fatfreecrm/fat_free_crm) (CRM Libre):**
  * **Licencia exacta:** Licencia MIT
  * **Versión vigente:** Versión v0.28.0
  * **Lenguaje del servidor:** Ruby
  * **SGBD compatibles:** MySQL, Postgre SQL y SQLite
  * **Modalidad:** Modalidad de código abierto
  * **Módulos principales:** Campañas, contactos y cuentas, colaboración en grupo, etc...
  * **Requisitos:** Versión 2.4 de Ruby, versión 3.X de Ruby on Rails y versión 4.1.1 de MySQL

* **[Zoho CRM](https://www.zoho.com/es-xl/crm/) (CRM Propietario):**
  * **Licencia exacta:** Licencia de Software Privativa Comercial
  * **Versión vigente:** Zoho CRM Next Gen UI
  * **Lenguaje del servidor:** Zoho Deluge
  * **SGBD compatibles:** Cualquier SGBD
  * **Modalidad:** Se puede instalar en la nube
  * **Módulos principales:** Posibles clientes, contactos, cuentas y tratos
  * **Requisitos:** Conexión estable y continua, y un navegador web compatible con ES6 y TLS v1.2

  **Fecha de Consulta:** 23/09/2026



# SECCIÓN 4: FE DE ERRATAS DEL TEMA 2

## Error 1

En el tema, en la página 7, se puede leer que, para Odoo, la versión actual es la 14. Esto sería un error debido a que, actualmente, la versión de Odoo es la 19. El tema está desactualizado.

**[Fuente 1](https://www.odoo.com/es_ES/page/release-notes)**

## Error 2

En el tema, en la página 6, se puede leer que la versión actual de ERPNext es la 15. Esto sería un error debido a que, actualmente, la versión de ERPNext es la 16. El tema está desactualizado.

**[Fuente 2](https://github.com/frappe/erpnext/releases)**



# SECCIÓN 5: MATRIZ DE DECISIONES

* **Coste de licencias:** Odoo Community ha recibido un 5 debido a que es gratuito. Microsoft Dynamics 365 ha recibido un 4 porque, aunque requiere de una suscripción, le he dado esa nota por su estabilidad. Por otra parte, Zoho CRM ha recibido un 2 debido a que, si la empresa quiere añadir más usuarios, el coste de las suscripciones podría aumentar.

* **Facilidad de instalación:** Odoo Community ha recibido un 3 debido a que requiere una instalación local en servidores propios. Microsoft Dynamics 365 y Zoho CRM han recibido un 5 debido a que su instalación es inmediata, al ser plataformas nativas en la nube.

* **Soporte técnico:** Odoo Community ha recibido un 2 debido a que carece de soporte técnico oficial por parte de su creador. Microsoft Dynamics y Zoho CRM han recibido un 5 debido a que, al ser software propietarios de pago, ambos posee acuerdos de nivel de servicio con soporte técnico oficial permanente.

* **Adaptabilidad:** Odoo Community ha recibido un 4 debido a que, al ser su código fuente abierto, permite modificar la plataforma a los flujos específicos de la empresa. Microsoft Dynamics 365 y Zoho CRM han recibido un 3 debido a que, al ser de código cerrado, las modificaciones están algo limitadas.

* **Seguridad de datos:** Odoo Community ha recibido un 3 debido a que la seguridad de este depende del equipo técnico interno. Microsoft Dynamics 365 ha recibido un 5 debido a que cuenta con la infraestructura cloud de Microsoft Azure. Zoho CRM ha recibido un 4 debido a que ofrece un entorno seguro gestionado en sus centros de datos en la nube.

* **Acceso móvil:** Odoo Community ha recibido un 3 debido a que permite acceso móvil pero requiere configuración de forma manual. Microsoft Dynamics 365 y Zoho CRM han recibido un 5 debido a que disponen de aplicaciones móviles nativas optimizadas.

#**Total ponderadas**
* **Odoo Community:** 3.55
* **Microsoft Dynamics 365:** 4.35
* **Zoho CRM:** 3.75