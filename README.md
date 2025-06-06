 


# Presentacion 


### Nombre: Gabriel Jose

### Apellido: Ortiz Corletto

### Materia: Base de Datos

### Maestro: Victor Recio



### Tema: Reportes





# Investigue sobre reportes en C# y PHP

Creación de Reportes en C# (.NET)
La creación de reportes en C# generalmente implica los siguientes pasos, variando ligeramente según la herramienta o tecnología elegida:

## 1. Definición de la Fuente de Datos:

Obtención de Datos: Los datos para el reporte pueden provenir de diversas fuentes: bases de datos (SQL Server, MySQL, PostgreSQL, Oracle, etc.), servicios web (APIs REST/SOAP), archivos (XML, JSON, CSV), o incluso objetos en memoria.

Modelado de Datos: Es una buena práctica definir clases o DTOs (Data Transfer Objects) que representen la estructura de los datos que se mostrarán en el reporte. Esto permite trabajar con datos fuertemente tipados.

Consultas: Utilizar LINQ (Language Integrated Query), Entity Framework, ADO.NET o procedimientos almacenados para recuperar los datos de la fuente.
## 2. Diseño del Reporte:

Herramientas de Diseño Visual: La mayoría de las herramientas de reporte en C# ofrecen diseñadores visuales:
SQL Server Data Tools (SSDT) / Report Builder: Para SSRS y RDLC. Permite arrastrar y soltar campos, tablas, gráficos, etc., y configurar propiedades.

Diseñadores de DevExpress, Telerik, Stimulsoft, etc.: Estos componentes suelen venir con sus propios diseñadores de arrastrar y soltar que se integran en Visual Studio o como aplicaciones standalone.

Definición del Layout: Se define la disposición de los elementos (encabezados, pies de página, secciones de detalle, agrupaciones, campos de texto, imágenes, gráficos, códigos de barras).
Formato y Estilos: Se aplican estilos (fuentes, colores, bordes) para mejorar la legibilidad y la apariencia visual del reporte.

Parámetros: Se definen parámetros para que el usuario pueda filtrar los datos o personalizar el reporte en tiempo de ejecución (ej. rango de fechas, ID de cliente).
## 3. Integración en la Aplicación:

Aplicaciones de Escritorio (Windows Forms/WPF):
Se utiliza el control ReportViewer (para RDLC) o los controles de visor de reportes provistos por librerías de terceros (DevExpress DocumentViewer, Telerik ReportViewer).

Se carga el archivo de definición del reporte (.rdlc, .repx, etc.) y se le asigna la fuente de datos generada en el paso 1.
El reporte se renderiza y se muestra en la aplicación.
Aplicaciones Web (ASP.NET Core/Blazor):

RDLC: Se puede utilizar el control ReportViewer del lado del servidor (en ASP.NET Web Forms) o integrar una solución personalizada para renderizar RDLC en ASP.NET Core (hay librerías de terceros que lo facilitan o se puede generar en el servidor y devolver un PDF).

Herramientas de Terceros: Ofrecen componentes de visor web (HTML5/JavaScript) que se integran fácilmente en aplicaciones ASP.NET Core, Blazor, o incluso JavaScript puro. Estos visores manejan la renderización, paginación y exportación.

Generación Directa: Se puede generar el reporte como un archivo (PDF, Excel) en el servidor y luego ofrecerlo para descarga al cliente a través de una acción de controlador.
## 4. Exportación y Distribución:

Los reportes suelen tener opciones para ser exportados a diferentes formatos como PDF, Excel, Word, CSV, HTML, imágenes, etc.
En SSRS, los reportes pueden ser programados para ser enviados por correo electrónico, guardados en una ubicación de red o publicados en un sitio de SharePoint.







# Creación de Reportes en PHP

La creación de reportes en PHP es muy flexible y a menudo se centra en la generación de contenido web que luego puede ser convertido o directamente consumido.

## 1. Definición de la Fuente de Datos:

Bases de Datos: PHP es muy eficiente conectándose a bases de datos (MySQL, PostgreSQL, SQL Server, SQLite) utilizando extensiones como PDO (PHP Data Objects) o mysqli.

APIs: Consumir datos de APIs RESTful usando cURL o la extensión file_get_contents (para APIs simples).

Archivos: Leer datos de archivos CSV, JSON, XML.

Consultas: Escribir consultas SQL directamente o usar un ORM (Object-Relational Mapper) como Doctrine o Eloquent (si usas Laravel).
## 2. Procesamiento y Organización de Datos:

Una vez obtenidos los datos, se procesan y se organizan en arreglos (arrays) o clases de objetos para facilitar su presentación. Se pueden aplicar lógicas de negocio, agrupaciones, cálculos, etc.
## 3. Diseño del Reporte (Generalmente HTML/CSS):

Generación de HTML: La forma más común es construir el reporte como una página HTML dinámica. PHP se encarga de iterar sobre los datos y generar las etiquetas HTML correspondientes (tablas, divs, párrafos, etc.).

Aplicación de Estilos (CSS): Se utiliza CSS para dar formato al reporte (tamaños de fuente, colores, márgenes, bordes, etc.). Esto puede ser CSS en línea, CSS interno o CSS en un archivo externo.

Plantillas: Se recomienda usar sistemas de plantillas como Twig, Blade (Laravel) o Smarty para separar la lógica PHP de la presentación HTML. Esto mejora la mantenibilidad y la legibilidad del código.

### Esta es la Base de Datos en SQL Server

![asd](file:///C:/Users/Gabriel%20Jose%20Ortiz/Desktop/Documentacion/asd.png)

### A partir aqui muestro los codigos que utilice para hacer el reporte en C#
![yert](file:///C:/Users/Gabriel%20Jose%20Ortiz/Desktop/Documentacion/yert.png)

![sf](file:///C:/Users/Gabriel%20Jose%20Ortiz/Desktop/Documentacion/sf.png)

![er](file:///C:/Users/Gabriel%20Jose%20Ortiz/Desktop/Documentacion/er.png)

![fg](file:///C:/Users/Gabriel%20Jose%20Ortiz/Desktop/Documentacion/fg.png)

![usyddf](file:///C:/Users/Gabriel%20Jose%20Ortiz/Desktop/Documentacion/usyddf.png)

### Aqui se puedee ver que lo corri a agregue los datos para generar la factura

![iusydr](file:///C:/Users/Gabriel%20Jose%20Ortiz/Desktop/Documentacion/iusydr.png)

### Aquí se generó la factura y me permite imprimirlo.

![gjsdf](file:///C:/Users/Gabriel%20Jose%20Ortiz/Desktop/Documentacion/gjsdf.png)
