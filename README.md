# 🛒 Orders

Proyecto de gestión de pedidos desarrollado con .NET (Visual Studio). Este sistema permite administrar pedidos, clientes, productos y más, ideal como base para aplicaciones empresariales.

## 🚀 Características

- CRUD completo de pedidos y entidades relacionadas
- Arquitectura organizada con capas separadas
- Proyecto compatible con Visual Studio
- Integración con Entity Framework y base de datos SQL Server

## 🧩 Estructura del Proyecto

```
Orders/
├── Orders.sln              # Archivo de solución
├── README.md               # Este archivo
├── .gitignore              # Ignora archivos innecesarios en Git
├── [Orders]/    # Código fuente principal (Controllers, Models, etc.)
```

## Tecnologías Usadas

- **Lenguaje:** C#
- **Framework:** .NET
- **API:** ASP.NET Core Web API
- **Pruebas:** xUnit o MSTest (según implementación)
- **Control de versiones:** Git

## Requisitos Previos

- [.NET SDK 7.0 o superior](https://dotnet.microsoft.com/download)
- [Visual Studio 2022 Community](https://visualstudio.microsoft.com/vs/community/)
- [SQL Server o base de datos configurada] (si aplica)

## Cómo Ejecutar el Proyecto

1. **Clonar el repositorio:**

```bash
git clone https://github.com/RPSilent/orders.git
cd orders
```

2. Abre el archivo `Orders.sln` con Visual Studio.

3. Restaura los paquetes NuGet y compila el proyecto:

```bash
dotnet restore
dotnet build
```

4. Configura tu cadena de conexión en `appsettings.json`.

5. Ejecuta las migraciones si se usa Entity Framework:

```bash
dotnet ef database update
```

## ▶️ Uso

Una vez en ejecución, el proyecto estará disponible en:

```
https://localhost:5001
```
