1. [Instalar y descargar el SDK .NET 9.0.](https://dotnet.microsoft.com/es-es/download/dotnet/thank-you/sdk-9.0.306-windows-x64-installer)
2. Clonar el repo y clonar Hypostasis (la versión a la que apunte el este repo).
3. En CMD, ejecutar `dotnet restore ARealmRecorded.sln`.
4. Si no ha dado errores, ejecutar `dotnet build ARealmRecorded.sln -c Debug`
5. Si no ha dado errores (puede dar bastantes warnings), ejecutar `dotnet build ARealmRecorded.sln -c Release`.
6. El DLL y demás archivos del plugin estará en `bin/Release`.
