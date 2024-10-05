<center>

[comment]: <img src="./media/media/image1.png" style="width:1.088in;height:1.46256in" alt="escudo.png" />

![./media/media/image1.png](./media/logo-upt.png)

# UNIVERSIDAD PRIVADA DE TACNA

## FACULTAD DE INGENIERÍA

### Escuela Profesional de Ingeniería de Sistemas

### PROYECTO “DASHBOARD PARA EL GIMNASIO DE LA UNIVERSIDAD PRIVADA DE TACNA”

Curso: *Inteligencia de Negocios* 
Docente: *Patrick Cuadros Quiroga* 

**Integrantes:**
- Lira Álvarez Rodrigo Samael Adonai (2019063331)
- Cutipa Machaca Arnold Félix (2019064040)
- Chávez Linares Cesar Fabian (2019063854)
- Arce Bracamonte Sebastián Rodrigo (2019062986)
- Soto Rodriguez Duanet (2015051384)

**Tacna – Perú**

***2024***


|CONTROL DE VERSIONES||||||
| :-: | :- | :- | :- | :- | :- |
|Versión|Hecha por|Revisada por|Aprobada por|Fecha|Motivo|
|1\.0|RLA,DSR|PCQ|PCQ|05/10/202|Versión Original|












**Sistema *PROYECTO DASHBOARD DEL ESTADO DE EJECUCION DEL GASTO PUBLICO PARA EL MINISTERIO DE ECONOMIA Y FINANZAS***

**Documento de Visión**

**Versión *1.0***



1. [Introducción](#1-introducción)
   - [1.1 Propósito](#11-propósito)
   - [1.2 Alcance](#12-alcance)
   - [1.3 Definiciones, Siglas y Abreviaturas](#13-definiciones-siglas-y-abreviaturas)
   - [1.4 Referencias](#14-referencias)
   - [1.5 Visión General](#15-visión-general)
2. [Posicionamiento](#2-posicionamiento)
   - [2.1 Oportunidad de negocio](#21-oportunidad-de-negocio)
   - [2.2 Definición del problema](#22-definición-del-problema)
3. [Descripción de los interesados y usuarios](#3-descripción-de-los-interesados-y-usuarios)
   - [3.1 Resumen de los interesados](#31-resumen-de-los-interesados)
   - [3.2 Resumen de los usuarios](#32-resumen-de-los-usuarios)
   - [3.3 Entorno de usuario](#33-entorno-de-usuario)
   - [3.4 Perfiles de los interesados](#34-perfiles-de-los-interesados)
   - [3.5 Perfiles de los Usuarios](#35-perfiles-de-los-usuarios)
   - [3.6 Necesidades de los interesados y usuarios](#36-necesidades-de-los-interesados-y-usuarios)
4. [Vista General del Producto](#4-vista-general-del-producto)
   - [4.1 Perspectiva del producto](#41-perspectiva-del-producto)
   - [4.2 Resumen de capacidades](#42-resumen-de-capacidades)
   - [4.3 Suposiciones y dependencias](#43-suposiciones-y-dependencias)
   - [4.4 Costos y precios](#44-costos-y-precios)
   - [4.5 Licenciamiento e instalación](#45-licenciamiento-e-instalación)
5. [Características del producto](#5-características-del-producto)
6. [Restricciones](#6-restricciones)
7. [Rangos de calidad](#7-rangos-de-calidad)
8. [Precedencia y Prioridad](#8-precedencia-y-prioridad)
9. [Otros requerimientos del producto](#9-otros-requerimientos-del-producto)
[CONCLUSIONES](#_Toc52661355)

[RECOMENDACIONES](#_Toc52661356)

[BIBLIOGRAFIA](#_Toc52661357)

[WEBGRAFIA](#_Toc52661358)


**<u>Informe de Visión</u>**

# 1. INTRODUCCIÓN

El presente proyecto consiste en desarrollar un dashboard informativo que permita llevar un control detallado de la asistencia de los estudiantes al gimnasio. Este dashboard se diseñará para visualizar de forma clara y dinámica los datos como horarios, datos personales y demás.

El dashboard no solo facilitará el acceso a la información en tiempo real, sino que también permitirá un análisis posterior de los patrones de uso del gimnasio, lo que puede servir para la toma de decisiones en cuanto a la optimización de los recursos, personal y el mantenimiento del equipamiento. Además, brindará un entorno organizado y accesible para gestionar grandes volúmenes de datos de manera eficiente y segura.

## 1.1 PROPÓSITO

El propósito de este proyecto es desarrollar un dashboard interactivo que permita registrar, monitorear y analizar la información de los alumnos que hacen uso del gimnasio universitario de manera eficiente. A través de la implementación de esta herramienta, se busca facilitar el control de asistencia y optimizar el manejo de los datos relacionados con los estudiantes que ingresan y salen del gimnasio.

## 1.2 ALCANCE

El alcance de este proyecto comprende el diseño, desarrollo e implementación de un dashboard interactivo que permita gestionar de manera eficiente la información de los alumnos que utilizan el gimnasio de la universidad. Este sistema se enfocará en las siguientes funcionalidades clave:

- **Registro de Datos**: El sistema permitirá el registro automático de la hora de ingreso y salida de cada alumno al gimnasio, junto con la captura de información relevante como DNI, nombres, apellidos y facultad a la que pertenecen.
- **Visualización en Tiempo Real**: El dashboard ofrecerá una interfaz gráfica interactiva que mostrará la información actualizada de los alumnos que se encuentran dentro del gimnasio, incluyendo estadísticas de uso en tiempo real.
- **Filtrado y Búsqueda de Información**: Los administradores del gimnasio podrán realizar búsquedas y aplicar filtros sobre la base de datos, permitiendo encontrar información específica de los usuarios, como nombres, facultades o DNI, de manera rápida y precisa.
- **Historial de Uso**: El sistema almacenará un historial detallado de cada ingreso y salida, permitiendo a los administradores revisar y analizar patrones de asistencia en distintos periodos.
- **Reportes y Análisis**: El dashboard contará con herramientas para la generación de reportes automáticos que detallen la frecuencia de uso del gimnasio, los horarios más concurridos y la distribución por facultades, facilitando la toma de decisiones informadas para la optimización del espacio y los recursos.

## 1.3 DEFINICIONES

- **KPI**: Indicador Clave de Rendimiento
- **Dashboard**: Panel de Control
- **BI**: Business Intelligence (Inteligencia de Negocios)
- **DW**: Data Warehouse (Almacén de Datos)

## 1.4 Referencias

- **Fuente de datos**: Los datos utilizados en el proyecto han sido recolectados y transcritos manualmente desde hojas físicas proporcionadas por el gimnasio de la Universidad Privada de Tacna. La información incluye registros de asistencia de los estudiantes al gimnasio, tales como nombres, apellidos, DNI, facultad, y horarios de ingreso y salida. Los datos fueron organizados y procesados en un archivo Excel por los integrantes del equipo de proyecto.

## 1.5 VISIÓN GENERAL

El proyecto de dashboard informativo para el gimnasio universitario tiene como objetivo centralizar y gestionar de manera eficiente la información de asistencia de los estudiantes, como la hora de ingreso y salida, DNI, nombres, apellidos y facultad. El sistema permitirá monitorear en tiempo real el uso del gimnasio, generar reportes automáticos, y facilitar el análisis de patrones de uso, mejorando la toma de decisiones y optimizando la gestión operativa, con un enfoque en la seguridad de los datos y la accesibilidad para los usuarios autorizados.

---

# 2. POSICIONAMIENTO

## 2.1 OPORTUNIDAD DE NEGOCIO

El desarrollo de este dashboard representa una oportunidad para la Universidad Privada de Tacna de mejorar el uso y gestión de su gimnasio, optimizando el uso de recursos, reduciendo tiempos de espera y mejorando la experiencia de los usuarios. Además, el análisis de datos de uso permitirá identificar patrones y tendencias, lo que puede dar lugar a iniciativas como la planificación de horarios más eficientes, la personalización de servicios o incluso la apertura de nuevos espacios en horarios de alta demanda.

Desde un punto de vista estratégico, este dashboard también puede integrarse en planes de mejora continua de las instalaciones deportivas, abriendo posibilidades para justificar futuras inversiones o mejoras basadas en datos reales. Asimismo, el control de asistencia puede ser un factor clave para garantizar el cumplimiento de normativas internas y mejorar la seguridad dentro del gimnasio, lo que añade valor tanto a la administración como a los usuarios del servicio.

## 2.2 DEFINICIÓN DEL PROBLEMA

La Universidad Privada de Tacna actualmente carece de un sistema eficiente para registrar y monitorear la asistencia de los estudiantes a su gimnasio, lo que dificulta el control de acceso y la gestión de datos. El método manual o no centralizado que se utiliza genera ineficiencias operativas, falta de visibilidad en tiempo real y una gestión deficiente de la información, lo cual puede derivar en congestiones durante horas pico, uso ineficiente de recursos y dificultad para generar reportes precisos sobre el uso de las instalaciones. Además, la falta de un sistema de análisis limita la capacidad de tomar decisiones informadas para optimizar el servicio y garantizar la seguridad de los usuarios.
# 3. DESCRIPCIÓN DE LOS INTERESADOS Y USUARIOS

## 3.1 Resumen de los interesados

Los principales interesados en este proyecto son:

- **Administradores del gimnasio**: Son los usuarios principales del dashboard, responsables de gestionar el acceso de los estudiantes, supervisar la asistencia y generar reportes. Su interés radica en mejorar la eficiencia operativa y tener acceso a datos precisos y en tiempo real.
- **Estudiantes usuarios del gimnasio**: Beneficiarios indirectos del sistema, ya que el dashboard optimiza la gestión del gimnasio, reduciendo tiempos de espera y mejorando la experiencia general del usuario.
- **Personal de seguridad**: Interesados en la información proporcionada por el dashboard para garantizar que el acceso al gimnasio se realice de manera controlada y segura, con capacidad de monitorear quiénes se encuentran dentro de las instalaciones en cualquier momento.
- **Departamento de TI**: Encargado de implementar, mantener y garantizar el buen funcionamiento del sistema, así como de asegurar la protección de los datos personales de los estudiantes.
- **Administración universitaria**: Interesados en el análisis de datos para tomar decisiones estratégicas respecto a la gestión de los recursos, horarios y posibles inversiones en mejoras para el gimnasio.

## 3.2 Resumen de los usuarios

Los usuarios accederán al dashboard a través de una interfaz. La interfaz debe ser fácil de usar e intuitiva, y debe permitir a los usuarios acceder rápidamente a la información que necesitan.

- **Usuarios finales**: Son aquellos que utilizarán el dashboard de forma continua para estar monitoriando el analisis de datos del gimnasio.
- **Usuarios ocasionales**: Son aquellos que utilizaran el dashboard para ver sus datos. 

## 3.3 Entorno de usuario

Los usuarios del dashboard utilizarán una interfaz intuitiva diseñada para facilitar la navegación y el acceso rápido a la información. De esta manera, se pretende que los usuarios puedan gestionar datos del gimnasio de manera eficiente sin complicaciones.

## 3.4 Perfiles de los interesados

- **Alumno**: 
  - **Descripción**: Alumnos de la universidad que utilizan el gimnasio como parte de sus actividades recreativas y deportivas.
  - **Necesidades**: Desean un acceso fluido al gimnasio y una experiencia de usuario cómoda, sin largas esperas ni complicaciones.

## 3.5 Perfiles de los usuarios

Al igual que con los interesados, los usuarios del dashboard se pueden clasificar en dos grupos principales:

### 3.5 Perfiles de los Usuarios

Al igual que con los interesados, los usuarios del dashboard se pueden clasificar en dos grupos principales:

#### 3.5.1 Usuarios Finales:
- **Administradores del Gimnasio**: Encargados de la gestión diaria del gimnasio, supervisan la asistencia, controlan el acceso y generan reportes sobre el uso de las instalaciones.
- **Personal de Seguridad**: Responsables de garantizar la seguridad en el gimnasio, monitorean el acceso y la seguridad de los usuarios dentro de las instalaciones.

#### 3.5.2 Usuarios Ocasionales:
- **Estudiantes**: Alumnos de la universidad que utilizan el gimnasio para actividades recreativas y deportivas, buscando una experiencia accesible y agradable en sus rutinas de ejercicio.
- **Personal Administrativo de la Universidad**: Miembros del personal administrativo que revisan ocasionalmente la información del gimnasio, interesados en evaluar el uso de las instalaciones y la satisfacción de los estudiantes.

### 3.6 Necesidades de los interesados y usuarios

Las necesidades de los interesados y usuarios del dashboard se pueden resumir en los siguientes puntos:

- Acceso a información actualizada y confiable sobre el uso y estado del gimnasio de la Universidad Privada de Tacna.
- Necesidad de información actualizada sobre la asistencia de los estudiantes al gimnasio.
- Requerimiento de informes sobre el uso del gimnasio y patrones de asistencia para la toma de decisiones.
- Herramientas para realizar análisis complejos y generar visualizaciones.
- Una interfaz de usuario fácil de usar e intuitiva.
- Acceso a datos históricos y actuales.
- Capacidad para filtrar y segmentar la información por diferentes criterios.
- Posibilidad de generar informes y descargar datos.
- Seguridad y protección de datos.

---

## 4. VISTA GENERAL DEL PRODUCTO

### 4.1 Perspectiva del producto

El dashboard informativo para el gimnasio universitario será una herramienta de inteligencia de negocios (BI) que permitirá a los usuarios visualizar, analizar y comprender la asistencia y el uso del gimnasio de manera clara, concisa y oportuna. Este dashboard estará diseñado para ser utilizado por una amplia gama de usuarios, desde administradores y personal de seguridad hasta estudiantes y personal administrativo. Su interfaz intuitiva facilitará la gestión del acceso, el monitoreo en tiempo real y la generación de reportes sobre el uso de las instalaciones, contribuyendo a una mejor experiencia y gestión operativa del gimnasio.

### 4.2 Resumen de capacidades

El dashboard incluirá las siguientes capacidades:

- **Monitoreo en Tiempo Real**: Proporciona datos actualizados sobre la asistencia de los estudiantes, permitiendo un seguimiento efectivo del uso del gimnasio.
- **Generación de Reportes**: Facilita la creación de informes automáticos sobre patrones de asistencia y uso de las instalaciones, apoyando la toma de decisiones.
- **Interfaz Intuitiva**: Ofrece un diseño fácil de usar que permite a los usuarios gestionar la información sin complicaciones.
- **Control de Acceso**: Permite la supervisión del ingreso y salida de los estudiantes, garantizando la seguridad en el gimnasio.
- **Filtrado y Búsqueda de Datos**: Proporciona herramientas para localizar información específica de los usuarios de manera rápida y eficiente.
- **Historial de Asistencia**: Almacena registros detallados de uso del gimnasio, permitiendo el análisis de tendencias a lo largo del tiempo.
- **Acceso Multiusuario**: Permite diferentes niveles de acceso para administradores, personal de seguridad y otros usuarios autorizados.
- **Protección de Datos**: Implementa medidas de seguridad para salvaguardar la información personal de los estudiantes, asegurando el cumplimiento de normativas.
- **Interacción Gráfica**: Presenta la información de manera visual, facilitando la comprensión de los datos y análisis.
- **Soporte Técnico**: Ofrece asistencia para resolver problemas técnicos y garantizar el buen funcionamiento del dashboard.

### 4.3 Suposiciones y dependencias

Las siguientes son algunas de las suposiciones y dependencias del proyecto:

- **Disponibilidad de datos**: El proyecto asume que los datos necesarios para el dashboard estarán disponibles y serán de buena calidad.
- **Recursos humanos**: El proyecto asume que habrá recursos humanos suficientes disponibles para desarrollar, implementar y mantener el dashboard.
- **Presupuesto**: El proyecto asume que habrá un presupuesto suficiente disponible para financiar el desarrollo, implementación y mantenimiento del dashboard.
- **Soporte de TI**: El proyecto asume que habrá soporte de TI disponible para resolver problemas técnicos.

### 4.4 Costos y precios

Los costos del proyecto dependen de una serie de factores, como el alcance del proyecto, la complejidad de las funcionalidades y la tasa de horas de los consultores. El precio del dashboard se determinará en función de los costos del proyecto.

### 4.5 Licenciamiento e instalación

El dashboard se licenciará bajo una licencia de código abierto. El dashboard se podrá instalar en un servidor local o en la nube.

---

## 5. CARACTERÍSTICAS DEL PRODUCTO

El dashboard para el gimnasio de la Universidad Privada de Tacna incluirá:

- **Monitoreo en Tiempo Real**: Proporciona datos actualizados sobre la asistencia y el uso del gimnasio, permitiendo un seguimiento efectivo y oportuno.
- **Interfaz Intuitiva**: Diseñado específicamente para facilitar la navegación de los usuarios, asegurando que puedan acceder a la información sin complicaciones.
- **Generación de Reportes**: Capacidad para generar informes automáticos sobre patrones de asistencia y uso de las instalaciones, apoyando la toma de decisiones informadas.
- **Control de Acceso**: Permite supervisar el ingreso y salida de estudiantes, garantizando la seguridad dentro del gimnasio.
- **Filtrado y Búsqueda de Datos**: Herramientas específicas para localizar información de estudiantes de manera rápida y eficiente, mejorando la gestión de datos.
- **Historial de Asistencia**: Almacena registros detallados del uso del gimnasio a lo largo del tiempo, facilitando el análisis de tendencias y patrones.
- **Interacción Gráfica**: Presenta la información de manera visual, utilizando gráficos y tablas que facilitan la comprensión de los datos y análisis.

---

## 6. RESTRICCIONES

Las siguientes son algunas de las restricciones del proyecto:

- **Disponibilidad de datos**: El dashboard dependerá de la disponibilidad de datos de buena calidad. Si los datos no están disponibles o son de mala calidad, el dashboard no funcionará correctamente.
- **Recursos humanos**: El desarrollo y mantenimiento del dashboard requerirá de recursos humanos calificados. Si no hay recursos humanos disponibles, el proyecto se retrasará o se cancelará.
- **Presupuesto**: El desarrollo y mantenimiento del dashboard requerirá de un presupuesto suficiente. Si no hay un presupuesto suficiente, el proyecto se reducirá en alcance o se cancelará.
- **Soporte de TI**: El dashboard requerirá de soporte de TI para resolver problemas técnicos. Si no hay soporte de TI disponible, el dashboard podría no estar disponible para los usuarios.

---

## 7. RANGOS DE CALIDAD

Los siguientes son los rangos de calidad esperados para el dashboard:

- **Funcionalidad**: El dashboard debe cumplir con todos los requisitos funcionales especificados en el documento de requisitos.
- **Usabilidad**: El dashboard debe ser fácil de usar e intuitivo. Los usuarios deben poder encontrar la información que necesitan rápidamente y sin dificultad.
- **Rendimiento**: El dashboard debe ser rápido y eficiente. Los usuarios no deben tener que esperar mucho tiempo para que se carguen las páginas o se generen los informes.
- **Confiabilidad**: El dashboard debe ser confiable y estar disponible para los usuarios la mayor parte del tiempo.
- **Seguridad**: El dashboard debe ser seguro y proteger los datos de los usuarios.

---

## 8. PRECEDENCIA Y PRIORIDAD

La precedencia y prioridad de las funcionalidades del dashboard se determinarán en función de los siguientes criterios:

- **Impacto en el negocio**: Las funcionalidades que tengan un mayor impacto en el negocio tendrán una mayor prioridad.
- **Facilidad de desarrollo**: Las funcionalidades que sean más fáciles de desarrollar tendrán una mayor prioridad.
- **Riesgo**: Las funcionalidades que tengan un mayor riesgo de fallar tendrán una menor prioridad.

## 9. OTROS REQUERIMIENTOS DEL PRODUCTO

Este proyecto tiene otros requerimientos clave que deben ser considerados durante su desarrollo e implementación, tales como:

- **Soporte técnico**: Los usuarios deben contar con un equipo de soporte técnico disponible para resolver cualquier incidencia que pueda ocurrir con el uso del dashboard.
- **Seguridad de los datos**: La protección de los datos personales de los estudiantes es fundamental y debe garantizarse mediante medidas de seguridad adecuadas.
- **Cumplimiento de normativas**: El dashboard debe cumplir con todas las normativas legales y de la universidad, especialmente en cuanto a la protección de datos personales y privacidad.

---

## CONCLUSIONES

La implementación del dashboard informativo para el gimnasio universitario transformará la gestión operativa al ofrecer datos en tiempo real sobre la asistencia de los estudiantes. Esta capacidad permitirá a los administradores tomar decisiones más informadas y optimizar el uso de recursos, mejorando la organización de las actividades en el gimnasio a través de reportes automáticos que faciliten el análisis de patrones de uso.

Además, la experiencia de los estudiantes se enriquecerá gracias a la facilidad de acceso y la seguridad proporcionadas por el dashboard. Al controlar el ingreso y salida de los usuarios de manera eficiente, se generará un ambiente más seguro y organizado, lo que reducirá los tiempos de espera y aumentará la satisfacción general de los estudiantes, fomentando una mayor participación en actividades recreativas y deportivas.

---

## RECOMENDACIONES

- **Capacitación Continua**: Es fundamental proporcionar formación regular a todos los usuarios del dashboard para garantizar que puedan utilizar todas las funcionalidades de manera efectiva. Esto mejorará la adopción del sistema y maximizará su utilidad.
  
- **Feedback de Usuarios**: Implementar un sistema de retroalimentación para que los usuarios puedan compartir sus experiencias y sugerencias. Esto permitirá realizar mejoras continuas en el dashboard, adaptándolo a las necesidades cambiantes de los usuarios.

- **Monitoreo de Seguridad**: Establecer protocolos de seguridad que se revisen y actualicen periódicamente para proteger la información personal de los estudiantes. Esto no solo asegurará el cumplimiento normativo, sino que también fortalecerá la confianza de los usuarios en el sistema.

---

## BIBLIOGRAFÍA

- Alvesson, M., & Sandberg, J. (2013). *Constructing research questions: Doing interesting research*. Sage Publications.
- Koller, V., & Tully, A. (2021). *Visualizing data: A guide to creating interactive dashboards*. Wiley.

---

## WEBGRAFÍA

- Tableau. (n.d.). What is a dashboard? Retrieved October 4, 2024, from [Tableau Website](https://www.tableau.com/learn/articles/dashboard).
- Microsoft. (2023). Power BI documentation. Retrieved October 4, 2024, from [Power BI Documentation](https://docs.microsoft.com/en-us/power-bi/).
