#Travel Management System – Deployment Verification (Lab Scenario 8)

##Backend Deployment (Spring Boot + MySQL)
Backend API deployed successfully on port **8080**  
MySQL connected with persistent storage  
Signup endpoint verified and functional  

**Verification URL:**  
👉 [http://localhost:8080/auth/signup?username=testuser&email=testuser@gmail.com&password=admin123](http://localhost:8080/auth/signup?username=testuser&email=testuser@gmail.com&password=admin123)

---

##Frontend Deployment (React + Vite)
Frontend hosted locally at **http://localhost:5173**  
Connected successfully to backend API  
Verified Login and Signup integration  

**Frontend Verification URL:**  
👉 http://localhost:5173

---

### CI/CD Summary
- Cloned both frontend and backend repositories  
- Configured Docker Compose for MySQL + Spring Boot  
- Verified backend APIs and frontend integration  
- Application deployed and tested locally  

---

** Prepared by:** Pallavi Pinninti  
**Lab Exam:** Travel Management System Deployment (Scenario 8)  
** Status:** Successfully Deployed
