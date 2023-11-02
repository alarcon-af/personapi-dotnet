# personapi-dotnet
 Laboratorio 1 arqui

Andres Alarcon
Steban Vanegas
German Velasco

3.1 Configuración Inicial
•	Creación de un repositorio Git público en GitHub con el nombre 'personapi-dotnet'.
•	Instalación de SQL Server 2019 Express en modo Básico.
•	Instalación de SQL Server Management Studio 18.
•	Creación de la base de datos 'persona_db' y asignación de propiedades al usuario 'sa'.
•	Instalación de Visual Studio Community 2022 con los complementos necesarios.
3.2 Desarrollo de la Aplicación Web
•	Creación de un proyecto utilizando la plantilla "Aplicación web de ASP.NET Core (Modelo-Vista-Controlador)" con el nombre 'personapi-dotnet'.
•	Configuración de la vista de Explorador de objetos de SQL Server en el menú Ver.
•	Agregado de la conexión de tipo local express.
3.3 Creación de la Base de Datos y Entidades
•	Uso de la Consola del Administrador de paquetes para instalar paquetes NuGet:|Microsoft.EntityFrameworkCore, Microsoft.EntityFrameworkCore.SqlServer, Microsoft.EntityFrameworkCore.Tools.
•	Creación de entidades en la carpeta Models.
•	Utilización de Scaffold-DbContext para generar clases entidad a partir de las tablas existentes en la base de datos y el contexto.
•	Agregado de la cadena de conexión en appsettings.json.
3.4 Desarrollo de la Lógica de Negocio
•	Creación de interfaces, repositorios y controladores para gestionar los datos de la aplicación.
