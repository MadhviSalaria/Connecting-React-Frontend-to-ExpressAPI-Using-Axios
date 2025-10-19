
---

## 🧠 How It Works
1. **Backend (Express):**  
   - Starts a local server at `http://localhost:5000`.  
   - Serves a list of products from `/products`.

2. **Frontend (HTML + JS):**  
   - Uses **Axios** to send a GET request to the Express API.  
   - Displays products with their names and prices.  
   - Shows loading and error states.

---

## 🛠️ How to Run

### 1️⃣ Setup Backend
```bash
cd backend
npm init -y
npm install express cors
node server.js
