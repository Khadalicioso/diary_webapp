# Diary Web Application

## Project Description

The Diary Web Application is a web-based platform built using ASP.NET Core MVC and Entity Framework Core, designed to allow users to create, manage, and share their personal diary entries. The application provides a user-friendly interface for writing and organizing diary entries, with features such as user authentication, CRUD operations for diary entries, and a responsive design that works on various devices.

## Technologies Used

- **Languages**: C#, HTML, CSS, JavaScript
- **Frameworks**: ASP.NET Core MVC, Entity Framework Core
- **Database**: SQL Server

## Project Structure

DiaryWebApp/
│
├── Controllers/ # Contains the MVC controllers
│ ├── DiaryController.cs
│ └── HomeController.cs
│
├── Models/ # Contains the data models
│ ├── DiaryEntry.cs
│ └── ErrorViewModel.cs
│
├── Views/ # Contains the Razor views
│ ├── Diary/
│ │ ├── Create.cshtml
│ │ ├── Delete.cshtml
│ │ ├── Edit.cshtml
│ │ └── Index.cshtml
│ ├── Home/
│ │ ├── About.cshtml
│ │ └── Index.cshtml
│ └── Shared/
│ ├── Layout.cshtml
│ ├── ValidationScriptsPartial.cshtml
│ └── Error.cshtml
│
├── Data/ # Contains the database context and migrations
│ └── ApplicationDbContext.cs
│
├── wwwroot/ # Contains static files (CSS, JS, images)
│ ├── css/
│ └── js/
│
├── appsettings.json # Configuration settings
└── Startup.cs # Application startup configuration

## Getting Started

To get started with the Diary Web Application, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/khadalicioso/diary_webapp.git
   ```

2. Navigate to the project directory:

   ```bash
   cd DiaryWebApp
   ```

3. Restore the NuGet packages:

   ```bash
   dotnet restore
   ```

4. Update the database:

   ```bash
   dotnet ef database update
   ```

5. Run the application:
   ```bash
   dotnet run
   ```

## Features

- User authentication and authorization
- Create, read, update, and delete diary entries
- Responsive design for mobile and desktop
- Secure storage of user data

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any enhancements or bug fixes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.