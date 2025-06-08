# ✈️ Airline Reservation System – Microservices Architecture

This project is a backend system for an airline reservation platform, designed using a **microservices architecture**. It handles flight search, ticket booking, user authentication, notifications, and routing through a centralized API Gateway.

---

## 📌 Tech Stack

- **Languages & Frameworks:** Node.js , Express.js , sequelize 
- **Communication:** REST APIs, RabbitMQ  
- **Security:** JWT (JSON Web Tokens) 
- **Database:** MySQL 

---

## 🧱 System Architecture

[ Client ] → [ API Gateway ] → [ Auth Service ]
[ Booking Service ]
[ Flight & Search Service ]
[ Reminder Service ]
↔ [ RabbitMQ ]

---

## 📂 Microservices & Repositories

| Service | Description | GitHub Link |
|--------|-------------|-------------|
| **Flight & Search Service** | Manages flight data and user search queries | [FlightsAndSearchService](https://github.com/ekamsinghh/FlightsAndSearchService) |
| **Booking Service** | Handles ticket booking and seat availability | [AirTicketBookingService](https://github.com/ekamsinghh/AirTicketBookingService) |
| **Reminder Service** | Sends reminders for upcoming flights | [ReminderService](https://github.com/ekamsinghh/ReminderService) |
| **Auth Service** | JWT-based authentication and user management | [Auth_Service](https://github.com/ekamsinghh/Auth_Service) |
| **API Gateway** | Routes requests to appropriate services | [API_Gateway](https://github.com/ekamsinghh/API_Gateway) |

---

## ⚙️ Key Features
 
- Centralized API Gateway for routing and load balancing  
- RabbitMQ for asynchronous event communication 
- JWT-based token authentication and secure API access 

---

## 🚀 How to Run (Local Setup)

1. Clone all service repositories and run them individually.  
2. Ensure **RabbitMQ** and **MySQL** are installed and running.  
4. Use tools like **Postman** to test endpoints via the **API Gateway**.

---

## 📝 Future Improvements

- Implement rate-limiting and monitoring on the gateway
- Implement more filters for flight searching
- Add frontend UI for user interaction  
- Migrate services to Kubernetes for orchestration

---

## 👨‍💻 Author

**Ekam Singh**  
📧 ekamsinghh24@gmail.com 
🔗 [LinkedIn](https://www.linkedin.com/in/ekamsinghh) | [GitHub](https://github.com/ekamsinghh)

