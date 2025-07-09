# 🛒 eShop – Because Who Doesn’t Love Shopping?

Welcome to **eShop**, your friendly neighborhood e-commerce platform built for developers, learners, and anyone who's ever said *"I could build Amazon if I had time."*

This project simulates a real-world online retail store — complete with product catalog, user authentication, shopping cart, and order flow — all running on a modern .NET stack.

---

## 🚀 Features

- 👥 User registration, login & session management
- 🛍️ Product catalog with category filtering
- 🛒 Persistent shopping cart with quantity control
- 📦 Order placement and mock checkout
- 🔐 Secure architecture using ASP.NET Identity
- 🛠️ Built with clean architecture principles (because spaghetti is for dinner, not code)

---

## 🧱 Tech Stack

| Layer              | Tech                            |
|--------------------|---------------------------------|
| Frontend UI        | Razor Pages / Blazor / MVC      |
| Backend API        | ASP.NET Core (.NET 8)           |
| Data Access        | Entity Framework Core + SQL     |
| Identity/Auth      | ASP.NET Core Identity            |
| Hosting/Deployment | Azure App Services / IIS        |
| Dev Tools          | Visual Studio 2022, Postman     |

> ⚙️ You can easily swap the frontend or backend layers — it's modular like LEGO™ blocks.

---

## 🧪 How to Run

```bash
# 1. Clone the repo
git clone https://github.com/your-username/eshop.git
cd eshop

# 2. Restore and build
dotnet restore
dotnet build

# 3. Run it!
dotnet run --project src/eShop.Web
