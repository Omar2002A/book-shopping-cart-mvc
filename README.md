# Book Shopping Cart MVC Project

This project is an ASP.NET MVC web application for managing and purchasing books online.  
It includes features like authentication, cart management, and admin controls.

## Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/Omar2002A/book-shopping-cart-mvc.git


2. Copy example settings
copy appsettings.example.json to appsettings.json or rename to appsettings.json
Edit appsettings.json if you need to update the connection string.

3. Restore NuGet packages
dotnet restore

4. Apply EF Core migrations (optional)
dotnet ef database update
Note: The application automatically applies migrations at startup.

5. Run the application
dotnet run

6. Open in browser
https://localhost:5001/

