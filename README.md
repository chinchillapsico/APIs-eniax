

## Documentación de Soporte y Uso de herramientas 

###  ![Alt text](docs/img/logo-gmail.png) 
    API
### Descripción y contexto
---
Este manual técnico tiene como objetivo describir las funcionalidades y los parámetros necesarios de los servicios web de la API eniax para el correcto uso de ella.

La API permite acceder a datos ficticios que emulan la realidad de pacientes. Los datos que entrega corresponden a citas médicas, incluye los siguientes parámetros: Fecha y hora, clínica y centro,  estado de cita, % de probabilidad de asistencia, nombre de paciente, tipo de paciente, nombre del médico/ especialidad y finalmente valor de la cita médica.

La documentación proveerá los servicios en formato JSON.

Este documento está dirigido a desarrolladoras de Laboratoria.

### Guía de usuario
---
*(Explica los pasos básicos sobre cómo usar la herramienta digital. Es una buena sección para mostrar capturas de pantalla o gifs que ayuden a entender la herramienta digital.)*
Aquí hay un ejemplo de la respuesta al implementar la API:


     {
      "hora": {
    		"UniqueID": "WH555444",
    		"data": {
      			"dia": "28/05/2018",
      			"hora": "15:00",
      			"medico": {
      					"nombre": "Alfredo Elberg Froimovich",
      					"especialidad": "Médico general",
      					"CoMorbid": [ "Hypertension", "CAD" ]
    			},
    		},
      
    "Labs": {
      "LDLCholestrol": {
        "LDLLevel": "122.5",
        "LDLResultDate": "2012/07/06"
      },
      "SerumCreatinine": {
        "CreatinineLevel": "1.4",
        "CreatinineResultDate": "12/07/08"
      }
    },
    "CareLocation": {
      "FacilityName": "East Side Clinic",
      "ContactEmail": "rsnurse@eastside.org"
    }
     }
    }
     }
    



 	
### Guía de instalación
---
*(Paso a paso de cómo instalar la herramienta digital. En esta sección es recomendable explicar la arquitectura de carpetas y módulos que componen el sistema.*

*Según el tipo de herramienta digital, el nivel de complejidad puede variar. En algunas ocasiones puede ser necesario instalar componentes que tienen dependencia con la herramienta digital. Si este es el caso, añade también la siguiente sección.*


*La guía de instalación debe contener de manera específica:*
*- Los requisitos del sistema operativo para la compilación (versiones específicas de librerías, software de gestión de paquetes y dependencias, SDKs y compiladores, etc.).*

*- Las dependencias propias del proyecto, tanto externas como internas (orden de compilación de sub-módulos, configuración de ubicación de librerías dinámicas, etc.).*
*- Pasos específicos para la compilación del código fuente y ejecución de tests unitarios en caso de que el proyecto disponga de ellos.)*

#### Dependencias
*(Descripción de los recursos externos que generan una dependencia para la reutilización de la herramienta digital (librerías, frameworks, acceso a bases de datos y licencias de cada recurso). Es una buena práctica describir las últimas versiones en las que ha sido probada la herramienta digital.)*

La url para API citas es:

    url de la api 

La url API usuarios es:

    url de la api


### Autor/es
---
María José Pozo (alguna info de contacto)

Andrea Miranda Echegoyen (alguna info de contacto)


### Licencia 
---
[LICENCIA](https://github.com/chinchillapsico/APIs-eniax/blob/master/LICENSE.md)


## Limitación de responsabilidades

El BID no será responsable, bajo circunstancia alguna, de daño ni indemnización, moral o patrimonial; directo o indirecto; accesorio o especial; o por vía de consecuencia, previsto o imprevisto, que pudiese surgir:

i. Bajo cualquier teoría de responsabilidad, ya sea por contrato, infracción de derechos de propiedad intelectual, negligencia o bajo cualquier otra teoría; y/o

ii. A raíz del uso de la Herramienta Digital, incluyendo, pero sin limitación de potenciales defectos en la Herramienta Digital, o la pérdida o inexactitud de los datos de cualquier tipo. Lo anterior incluye los gastos o daños asociados a fallas de comunicación y/o fallas de funcionamiento de computadoras, vinculados con la utilización de la Herramienta Digital.
