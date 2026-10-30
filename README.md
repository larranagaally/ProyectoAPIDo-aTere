ProyectoAPIDoñaTere

Doña Tere - Sistema de Gestión y Pedidos
Integrantes del Equipo
Emily Charlotte Ortega Davila
Angel Antonio Larrañaga Reyes


Configuración del Dev Tunnel en DonaTereApp (Cliente)
1. Inicia la Web API DoñaTereApi desde Visual Studio asegurándote de tener un Dev Tunnel activo en modo público Public.
2. Copia la URL pública generada por Visual Studio (por ejemplo, `https://xxxxxx.devtunnels.ms/`).
3. En el proyecto DonaTereApp, abre la clase de configuración de servicios HTTP (por ejemplo, ApiService.cs.
4. Actualiza la propiedad BaseAddress con la URL pública de tu túnel:
   csharp
   _httpClient.BaseAddress = new Uri("[https://tu-tunel.devtunnels.ms/](https://tu-tunel.devtunnels.ms/)");
