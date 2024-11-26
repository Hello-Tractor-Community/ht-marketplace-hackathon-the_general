# Hello Tractor Marketplace 🚜

Welcome to the **Hello Tractor E-commerce Hackathon**! This project focuses on building a secondary marketplace for buying and selling second-hand tractors, agricultural implements, and connecting with certified tractor operators. Let’s create innovative solutions for Africa's agricultural future! 🌍

---

## Project Overview

This e-commerce platform is designed to connect buyers and sellers in the agricultural space. The platform supports users with the following features:

### **Key Features for Users**
1. **Register and Login**  
   - Secure registration with email, phone, or social media verification.
2. **Browse Tractor Listings**  
   - View detailed listings, including photos, specifications, price, and history.
3. **Search and Filter**  
   - Filter listings by brand, make, model, price range, and location.
4. **Message Sellers**  
   - Communicate directly with sellers through an in-platform messaging system.
5. **Book Operators**  
   - Connect with certified tractor operators for hire.

### **Key Features for Sellers**
1. **Post Listings**  
   - Add tractor or agricultural implement listings with images, specifications, and pricing details.
2. **Dashboard Access**  
   - Manage listings, track inquiries, and monitor sales performance.

### **Key Features for Administrators**
1. **Admin Dashboard**  
   - Approve or reject new listings and monitor platform content.
2. **User Management**  
   - Manage user accounts and permissions.
3. **Platform Quality Control**  
   - Ensure all listings meet the quality and safety standards of the marketplace.

---

## Technologies Used & System Requirements

- **Backend**: Java SE 11, MySQL 8, Spring Boot, Spring Security  
- **Frontend**: JSP (Jakarta Server Pages), JavaScript, Bootstrap  
- **Messaging System**: Integration with in-app notifications and email alerts.

---

## How to Run the Application Locally

### 1. Clone the Repository  
```bash
git clone https://github.com/Hello-Tractor-Community/ht-marketplace-hackathon-the_general.git
cd ht-marketplace-hackathon-the_general
```

### 2. Create the Postgre or mysql Database  
```sql
CREATE DATABASE hello_tractor;
```

### 3. Set Up `application.properties`  
Configure your database connection in the `src/main/resources/application.properties` file:
```properties
spring.datasource.driver-class-name=org.postgresql.Driver
spring.datasource.url=jdbc:postgresql://localhost:5432/HelloTractors
spring.datasource.username=your-username
spring.datasource.password=your_password
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
spring.jpa.properties.hibernate.dialect=org.hibernate.dialect.PostgreSQLDialect
spring.datasource.hikari.auto-commit=false
```

### 4. Run the Application  
```bash
./mvnw spring-boot:run
```

Visit [http://localhost:8080](http://localhost:8080) in your browser.

---

## Deliverables Checklist ✅

1. **Codebase**  
   - Modular, well-structured, and fully documented codebase.

2. **Demo Video**  
   - Link: [https://youtu.be/hkiQhCpaHsI?si=AHNeLfoxBfYXGr0B]

3. **Live Application**  
   - Deployed on [Insert Deployment Platform (e.g., Netlify, Vercel, AWS)]  
   - URL: [Insert live application URL here]

4. **Technical Documentation**  
   - Setup instructions, architecture diagrams, and design flowcharts are included in the `docs/` folder.

5. **Project Report**  
   - Key details about the project, including team members, tech stack, and challenges.

---


---

## Contact & Support  
For any inquiries, reach out via [Discord](#) or refer to the official Hello Tractor documentation. Good luck and happy hacking! 🚀
