<center>

[comment]: <img src="./media/media/image1.png" style="width:1.088in;height:1.46256in" alt="escudo.png" />

![./media/media/image1.png](./media/logo-upt.png)

**UNIVERSIDAD PRIVADA DE TACNA**

**FACULTAD DE INGENIERIA**

**Escuela Profesional de Ingeniería de Sistemas**

**PROYECTO DASHBOARD DEL ESTADO DE EJECUCION DEL GASTO PUBLICO PARA EL MINISTERIO DE ECONOMIA Y FINANZAS**

Curso: *Inteligencia de Negocios* 
Docente: *Patrick Cuadros Quiroga* 

Integrantes:

***{Lira Álvarez, Rodrigo Samael Adonai			(2019063331) }***
***{Cutipa Machaca, Arnold Félix				(2019064040)  }***
***{Chávez Linares, Cesar Fabian				(2019063854)  }***
***{Lira Álvarez, Rodrigo Samael Adonai			(2019063331) }***
***{Lira Álvarez, Rodrigo Samael Adonai			(2019063331) }***

**Tacna – Perú**

***2024***

**  
**
</center>
<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

|CONTROL DE VERSIONES||||||
| :-: | :- | :- | :- | :- | :- |
|Versión|Hecha por|Revisada por|Aprobada por|Fecha|Motivo|
|1\.0|MPV|ELV|ARV|10/10/2020|Versión Original|












**Sistema *PROYECTO DASHBOARD DEL ESTADO DE EJECUCION DEL GASTO PUBLICO PARA EL MINISTERIO DE ECONOMIA Y FINANZAS***

**Documento de Visión**

**Versión *1.0***
**

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

|CONTROL DE VERSIONES||||||
| :-: | :- | :- | :- | :- | :- |
|Versión|Hecha por|Revisada por|Aprobada por|Fecha|Motivo|
|1\.0|MPV|ELV|ARV|10/10/2020|Versión Original|


<div style="page-break-after: always; visibility: hidden">\pagebreak</div>


**INDICE GENERAL**
#
[1.	Introducción](#_Toc52661346)

1.1	Propósito

1.2	Alcance

1.3	Definiciones, Siglas y Abreviaturas

1.4	Referencias

1.5	Visión General

[2.	Posicionamiento](#_Toc52661347)

2.1	Oportunidad de negocio

2.2	Definición del problema

[3.	Descripción de los interesados y usuarios](#_Toc52661348)

3.1	Resumen de los interesados

3.2	Resumen de los usuarios

3.3	Entorno de usuario

3.4	Perfiles de los interesados

3.5	Perfiles de los Usuarios

3.6	Necesidades de los interesados y usuarios

[4.	Vista General del Producto](#_Toc52661349)

4.1	Perspectiva del producto

4.2	Resumen de capacidades

4.3	Suposiciones y dependencias

4.4	Costos y precios

4.5	Licenciamiento e instalación

[5.	Características del producto](#_Toc52661350)

[6.	Restricciones](#_Toc52661351)

[7.	Rangos de calidad](#_Toc52661352)

[8.	Precedencia y Prioridad](#_Toc52661353)

[9.	Otros requerimientos del producto](#_Toc52661354)

b) Estandares legales

c) Estandares de comunicación	](#_toc394513800)37

d) Estandaraes de cumplimiento de la plataforma	](#_toc394513800)42

e) Estandaraes de calidad y seguridad	](#_toc394513800)42

[CONCLUSIONES](#_Toc52661355)

[RECOMENDACIONES](#_Toc52661356)

[BIBLIOGRAFIA](#_Toc52661357)

[WEBGRAFIA](#_Toc52661358)


<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

**<u>Informe de Visión</u>**

# 1. INTRODUCCIÓN

El proyecto consiste en el desarrollo de un completo y visualmente informativo dashboard que ofrece un análisis detallado del estado de ejecución del gasto público para el Ministerio de Economía y Finanzas. Este dashboard proporciona una visión integral de cómo se están utilizando los recursos financieros, permitiendo a los responsables de la toma de decisiones evaluar el rendimiento del gasto público en diferentes áreas y programas.

Mediante la visualización de indicadores clave, tendencias históricas y comparativas, así como alertas tempranas sobre posibles desviaciones presupuestarias, el dashboard facilita una gestión financiera más eficaz y transparente, promoviendo una mejor asignación de recursos y una mayor rendición de cuentas en el ámbito gubernamental.

## 1.1 PROPÓSITO

Proporcionar al Ministerio de Economía y Finanzas una herramienta efectiva y accesible para monitorear y evaluar el estado de ejecución del gasto público de manera integral.

## 1.2 ALCANCE

Este proyecto abarca el diseño, desarrollo e implementación de un dashboard para el MEF. El dashboard incluirá indicadores clave de rendimiento (KPIs), gráficos, tablas, filtros y funcionalidades de drill-down.

- **Recopilación de datos**: Recopilación de datos financieros relevantes de diversas fuentes internas y externas como sistemas de contabilidad, bases de datos gubernamentales, informes financieros, entre otros.
- **Integración de datos**: Integrar y consolidar los datos recopilados en una única fuente de datos que alimentará el dashboard. Esto implica limpieza, transformación y preparación de los datos para su uso en el análisis y la visualización.
- **Desarrollo del dashboard**: Diseñar y desarrollar el dashboard en función de los requisitos del usuario y las mejores prácticas de visualización de datos. Esto incluiría la creación de visualizaciones interactivas, tableros de control, gráficos y otras herramientas de análisis.
- **Funcionalidades clave**: Implementar funcionalidades clave en el dashboard como la capacidad de filtrar y segmentar datos, comparar períodos de tiempo, realizar análisis de tendencias y recibir alertas sobre desviaciones presupuestarias, entre otras.

## 1.3 DEFINICIONES

- **MEF**: Ministerio de Economía y Finanzas
- **KPI**: Indicador Clave de Rendimiento
- **Dashboard**: Panel de Control
- **BI**: Business Intelligence (Inteligencia de Negocios)
- **DW**: Data Warehouse (Almacén de Datos)

## 1.4 REFERENCIAS

- [https://www.mef.gob.pe/es/seguimiento-de-la-ejecucion-presupuestal-consulta-amigable](https://www.mef.gob.pe/es/seguimiento-de-la-ejecucion-presupuestal-consulta-amigable)
- [https://www.mef.gob.pe/es/presupuesto-del-sector-publico/proyecto-de-presupuesto](https://www.mef.gob.pe/es/presupuesto-del-sector-publico/proyecto-de-presupuesto)
- [https://m.youtube.com/watch?v=97d5O2QVK7w](https://m.youtube.com/watch?v=97d5O2QVK7w)

## 1.5 VISIÓN GENERAL

Este proyecto tiene como objetivo desarrollar una herramienta que permita a los funcionarios del MEF, así como a otros actores interesados, tener una visión clara y completa del estado de la ejecución del gasto público. El dashboard facilitará el análisis y seguimiento del gasto por diferentes categorías, la identificación de posibles desviaciones entre el presupuesto asignado y el ejecutado, y la toma de decisiones informadas en materia de gestión fiscal.

---

# 2. POSICIONAMIENTO

## 2.1 OPORTUNIDAD DE NEGOCIO

El desarrollo de este dashboard representa una oportunidad para el MEF de mejorar la transparencia y la rendición de cuentas en la gestión del gasto público. Además, permitirá fortalecer la toma de decisiones basada en datos y promover una cultura de eficiencia y eficacia en el gasto público.

## 2.2 DEFINICIÓN DEL PROBLEMA

El MEF actualmente no cuenta con una herramienta que permita visualizar de manera integrada y centralizada el estado de la ejecución del gasto público. Esto dificulta el análisis y seguimiento del gasto, la identificación de posibles desviaciones y la toma de decisiones informadas.
# 3. DESCRIPCIÓN DE LOS INTERESADOS Y USUARIOS

## 3.1 Resumen de los interesados

Los principales interesados en este proyecto son:

- **Funcionarios del MEF**: Los funcionarios del MEF serán los principales usuarios del dashboard. Utilizarán la herramienta para analizar y seguir el gasto público, identificar posibles desviaciones y tomar decisiones informadas.
- **Alta dirección del MEF**: La alta dirección del MEF utilizará el dashboard para tener una visión general del estado de la ejecución del gasto público y tomar decisiones estratégicas.
- **Contraloría General de la República**: La Contraloría General de la República utilizará el dashboard para realizar auditorías y controles del gasto público.
- **Ciudadanos**: Los ciudadanos podrán acceder al dashboard de forma pública para tener información sobre el estado de la ejecución del gasto público.

## 3.2 Resumen de los usuarios

Los usuarios del dashboard se pueden clasificar en dos grupos principales:

- **Usuarios finales**: Son aquellos que utilizarán el dashboard de forma regular para analizar y seguir el gasto público. Estos usuarios pueden ser funcionarios del MEF, analistas de presupuesto, auditores, investigadores y ciudadanos interesados.
- **Usuarios ocasionales**: Son aquellos que accederán al dashboard de forma esporádica para consultar información específica sobre el gasto público. Estos usuarios pueden ser periodistas, académicos, estudiantes y otros interesados.

## 3.3 Entorno de usuario

Los usuarios accederán al dashboard a través de una interfaz web. La interfaz debe ser fácil de usar e intuitiva y debe permitir a los usuarios acceder rápidamente a la información que necesitan.

## 3.4 Perfiles de los interesados

| Perfil                  | Descripción                                               | Necesidades                                                                                                                                                            |
|-------------------------|-----------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Funcionarios del MEF** | Analistas de presupuesto, gerentes de programa, etc.       | Analizar y seguir el gasto público por diferentes categorías (programa, fuente de financiamiento, unidad ejecutora, etc.) Identificar posibles desviaciones presupuestarias. |

## 3.5 Perfiles de los usuarios

Al igual que los interesados, los usuarios del dashboard se pueden clasificar en dos grupos principales:

### Usuarios finales:

- **Analistas de presupuesto**: Necesitan analizar el gasto público en detalle para identificar tendencias, patrones y posibles áreas de ineficiencia. Requieren acceso a datos históricos y actuales, así como la capacidad de filtrar y segmentar la información por diferentes categorías.
- **Gerentes de programa**: Monitorean el progreso de sus programas y proyectos para asegurarse de que se cumplan los objetivos y se mantengan dentro del presupuesto. Requieren indicadores clave de rendimiento (KPIs) y visualizaciones que les permitan identificar desviaciones y tomar medidas correctivas.
- **Auditores**: Examinan el gasto público para detectar fraudes, abusos y errores. Requieren acceso a datos detallados sobre las transacciones, así como la capacidad de realizar análisis comparativos y generar informes.
- **Investigadores**: Estudian el gasto público para comprender cómo se asigna y utiliza el dinero del gobierno. Requieren acceso a datos históricos y actuales, así como la capacidad de realizar análisis complejos y generar visualizaciones.
- **Ciudadanos**: Requieren información general sobre el estado de la ejecución del gasto público para comprender cómo se gasta el dinero de sus impuestos. Necesitan un dashboard fácil de usar que presente la información de manera clara y concisa.

### Usuarios ocasionales:

- **Periodistas**: Necesitan información específica sobre el gasto público para escribir artículos e informes. Requieren acceso a datos históricos y actuales, así como la capacidad de filtrar y segmentar la información por diferentes categorías.
- **Académicos**: Estudian el gasto público para realizar investigaciones. Requieren acceso a datos históricos y actuales, así como la capacidad de realizar análisis complejos y generar visualizaciones.
- **Estudiantes**: Necesitan aprender sobre el gasto público para comprender cómo funciona el gobierno. Requieren un dashboard fácil de usar que presente la información de manera clara y concisa.

## 3.6 Necesidades de los interesados y usuarios

Las necesidades de los interesados y usuarios del dashboard se pueden resumir en los siguientes puntos:

- Acceso a información actualizada y confiable sobre el estado de la ejecución del gasto público.
- Capacidad para analizar y seguir el gasto por diferentes categorías (programa, fuente de financiamiento, unidad ejecutora, etc.).
- Posibilidad de identificar posibles desviaciones entre el presupuesto asignado y el ejecutado.
- Herramientas para realizar análisis complejos y generar visualizaciones.
- Una interfaz de usuario fácil de usar e intuitiva.
- Acceso a datos históricos y actuales.
- Capacidad para filtrar y segmentar la información por diferentes criterios.
- Posibilidad de generar informes y descargar datos.
- Seguridad y protección de datos.

---

# 4. VISTA GENERAL DEL PRODUCTO

## 4.1 Perspectiva del producto

El dashboard del estado de la ejecución del gasto público para el MEF será una herramienta de inteligencia de negocios (BI) que permitirá a los usuarios visualizar, analizar y comprender el gasto público de manera clara, concisa y oportuna. El dashboard estará diseñado para ser utilizado por una amplia gama de usuarios, desde analistas de presupuesto hasta ciudadanos interesados.

## 4.2 Resumen de capacidades

El dashboard incluirá las siguientes capacidades:
- **Visualizaciones de datos**: Gráficos de barras, líneas, tablas y mapas. Estas visualizaciones permitirán a los usuarios ver el gasto público desde diferentes perspectivas.
- **Filtros y segmentaciones**: Los usuarios podrán filtrar y segmentar la información por criterios como programa, fuente de financiamiento, unidad ejecutora y período de tiempo.
- **Drill-down**: Los usuarios podrán profundizar en la información haciendo clic en los diferentes elementos del dashboard.
- **Indicadores clave de rendimiento (KPIs)**: El dashboard incluirá KPIs que permitirán a los usuarios monitorear el progreso del gasto público.
- **Análisis comparativo**: Los usuarios podrán comparar el gasto público a lo largo del tiempo, entre diferentes programas, fuentes de financiamiento o unidades ejecutoras.
- **Generación de informes**: Los usuarios podrán generar informes personalizados que resuman la información del dashboard.
- **Exportación de datos**: Los usuarios podrán exportar los datos del dashboard a diferentes formatos como CSV o Excel.

## 4.3 Suposiciones y dependencias

Las siguientes son algunas de las suposiciones y dependencias del proyecto:

- Disponibilidad de datos de buena calidad.
- Recursos humanos suficientes para desarrollar, implementar y mantener el dashboard.
- Presupuesto suficiente para financiar el proyecto.
- Soporte de TI disponible para resolver problemas técnicos.

## 4.4 Costos y precios

Los costos del proyecto dependerán de factores como el alcance del proyecto, la complejidad de las funcionalidades y la tasa de horas de los consultores.

## 4.5 Licenciamiento e instalación

El dashboard se licenciará bajo una licencia de código abierto. Podrá instalarse en un servidor local o en la nube.

---

# 5. CARACTERÍSTICAS DEL PRODUCTO

El dashboard incluirá las siguientes características:

- **Visualizaciones de datos**:
  - Gráficos de barras, líneas, tablas y mapas.
- **Filtros y segmentaciones**: Por programa, fuente de financiamiento, unidad ejecutora, período de tiempo, nivel de gobierno, palabra clave.
- **Drill-down**: Profundización de datos mediante clics en elementos interactivos.
- **KPIs**: Indicadores de ejecución presupuestal, montos ejecutados y desviaciones.
- **Análisis comparativo**: Comparaciones entre programas, financiamientos o ejecutoras.
- **Generación de informes**: Informes personalizados con gráficos y tablas.
- **Exportación de datos**: Exportación en formatos CSV o Excel.
- **Seguridad**: Sistema de autenticación, autorización y encriptación.
- **Accesibilidad**: Diseño accesible para personas con discapacidades.

---

# 6. RESTRICCIONES

Las restricciones del proyecto incluyen:

- Disponibilidad de datos de calidad.
- Necesidad de recursos humanos calificados.
- Presupuesto suficiente.
- Soporte de TI para la resolución de problemas técnicos.

---

# 7. RANGOS DE CALIDAD

Los siguientes rangos de calidad se esperan para el dashboard:

- **Funcionalidad**: Cumplimiento de todos los requisitos funcionales.
- **Usabilidad**: Facilidad de uso e intuitividad.
- **Rendimiento**: Carga rápida de páginas y generación de informes.
- **Confiabilidad**: Disponibilidad constante.
- **Seguridad**: Protección y encriptación de datos.

---

# 8. PRECEDENCIA Y PRIORIDAD

Las funcionalidades se priorizarán según:

- Impacto en el negocio.
- Facilidad de desarrollo.
- Riesgo de fallas.

