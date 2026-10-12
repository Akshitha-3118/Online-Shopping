# ShopSphere — Online Shopping Management System

React + CSS frontend, Java 17 / Spring Boot backend, H2 database and JWT security.

## Run locally
1. Install JDK 17, Maven and Node.js.
2. Backend: `cd backend` then `mvn spring-boot:run` (API on http://localhost:8080).
3. Frontend: in a second terminal, `cd frontend`, `npm install`, then `npm run dev` (http://localhost:5173).

## Demo logins
- Admin: `admin@shop.com` / `Admin@123`
- Customer: `customer@shop.com` / `Customer@123`

H2 console: http://localhost:8080/h2-console, JDBC URL `jdbc:h2:file:./data/shopdb`, username `sa`, blank password.

Checkout is a demo order flow and does not process real payments. Change the JWT secret and configure allowed frontend origins before public production deployment.
