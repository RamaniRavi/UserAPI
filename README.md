<h1 align="center">UserAPI - ASP.NET Core Web API</h1>
<h3 align="center">A User Management API with CRUD operations</h3>
<h1></h1>

## 📖 About UserAPI

**UserAPI** is a RESTful API built using ASP.NET Core, Entity Framework, and SQL Server for managing users. It includes 5 main endpoints for performing CRUD operations (Create, Read, Update, Delete) on user data.

---

## 🛠️ Tech Stack

- **Languages & Frameworks**:
  - ![C#](https://img.shields.io/badge/-C%23-00599C?style=flat-square&logo=csharp)
  - ![ASP.NET Core](https://img.shields.io/badge/-ASP.NET_Core-512BD4?style=flat-square&logo=.net)
  - ![Entity Framework](https://img.shields.io/badge/-Entity_Framework_Core-512BD4?style=flat-square&logo=.net)

- **Database**:
  - ![SQL Server](https://img.shields.io/badge/-SQL_Server-CC2927?style=flat-square&logo=microsoft-sql-server)

- **Tools**:
  - ![Postman](https://img.shields.io/badge/-Postman-FF6C37?style=flat-square&logo=postman)
  - ![Swagger](https://img.shields.io/badge/-Swagger-85EA2D?style=flat-square&logo=swagger)

---

## 📌 Endpoints

1. **GET** /api/users
   - Fetch all users from the database.
   
2. **GET** /api/users/{id}
   - Fetch a user by their ID.

3. **POST** /api/users
   - Create a new user.

4. **PUT** /api/users/{id}
   - Update an existing user by ID.

5. **DELETE** /api/users/{id}
   - Delete a user by their ID.

---

## 🚀 How to Set Up

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/UserAPI.git
    ```
2. Navigate to the project directory:
    ```bash
    cd UserAPI
    ```
3. Restore the dependencies:
    ```bash
    dotnet restore
    ```
4. Apply the database migrations:
    ```bash
    dotnet ef database update
    ```
5. Run the application:
    ```bash
    dotnet run
    ```

---

## 📸 API Endpoints in Action

### User API Overview
![User API Overview](https://github.com/RamaniRavi/UserAPI/blob/main/Demo/user-api-overview.png)

### GET API Details in Swagger
![Swagger API Details](https://github.com/RamaniRavi/UserAPI/blob/main/Demo/GET-swagger-api-details.png)

---

## ⚙️ Database

- **SQL Server** is used to store the user data.
- Entity Framework Core is used to manage database operations.

---

## 🔧 Tools for Testing

- **Swagger UI** is available for testing API endpoints via `/swagger`.
- You can also test API requests using **Postman** by importing the Swagger documentation.

---

## 🏗️ How to Contribute

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

---

## 📝 License

This project is licensed under the MIT License.
