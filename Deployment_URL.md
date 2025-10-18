# Travel Management System – Deployment Verification (Lab Scenario 8)

## Backend Deployment (Spring Boot + MySQL via Docker)
✅ Configured and deployed backend API container exposing port **8080**.  
✅ MySQL volume created for database persistence.  
✅ Application verified via signup endpoint.

**Verification URL:**  
👉 [http://localhost:8080/auth/signup?username=testuser&email=testuser@gmail.com&password=admin123](http://localhost:8080/auth/signup?username=testuser&email=testuser@gmail.com&password=admin123)

**Expected Output:**

---

## Frontend Deployment (React + Vite)
✅ Frontend hosted locally at **http://localhost:5173**  
✅ Connected successfully to backend API  
✅ Verified Login and Signup integration

**Dashboard Modules:**
- Destinations  
- Bookings  
- Payments  

---

### ✅ CI/CD Summary
- Cloned both backend and frontend repositories.  
- Backend Dockerized using Dockerfile and docker-compose with volume.  
- Verified container service through localhost endpoint.  
- Successfully integrated frontend and backend locally.

---

**Final Submission URL:**  
👉 http://localhost:8080/auth/signup?username=testuser&email=testuser@gmail.com&password=admin123

---

🧠 *Prepared by:* **Pallavi Pinninti**  
📅 *Lab Exam: Travel Management System Deployment (Scenario 8)*
