# 📖 Book Service  

The **Book Service** handles book-related operations like adding, updating, and retrieving books.

## 🚀 Features  
- Manage book inventory  
- Search for books by title or author  
- Check book availability  

## 🔗 API Endpoints  
| Method | Endpoint | Description |
|--------|---------|------------|
| `POST` | `/books` | Add a new book |
| `GET` | `/books/{id}` | Get book details |
| `PUT` | `/books/{id}` | Update book info |
| `DELETE` | `/books/{id}` | Remove book from inventory |

## 🛠️ Tech Stack  
- Spring Boot  
- Spring Data JPA (H2/MySQL)  
- Eureka Client  


## 🏃 How to Run  
```sh
mvn spring-boot:run
