# 🧠 Software Development Life Cycle (SDLC) & Software Models

## 📘 SDLC Definition
**Software Development Life Cycle (SDLC)** is a structured process that defines all steps involved in developing software — from **requirement gathering** to **designing**, **coding**, **testing**, **deployment**, and **maintenance**.  
💡 Think of SDLC as a **roadmap or recipe** for creating software systematically.

---

## 🔹 SDLC Phases (Clothing Brand E-commerce Example)

| **Phase** | **Purpose** | **Example** |
|-----------|-------------|-------------|
| **1️⃣ Requirement Gathering & Analysis** | Understand client needs | Login, product search, cart, payment, order tracking |
| **2️⃣ Design** | Plan system structure & UX | Website layout, DB schema |
| **3️⃣ Implementation (Coding)** | Write actual code | Frontend: HTML/CSS/JS, Backend: Python/Flask/Django |
| **4️⃣ Testing** | Verify functionality & fix bugs | Test login, payments, cart logic |
| **5️⃣ Deployment** | Launch the software | Host website online |
| **6️⃣ Maintenance** | Fix bugs & add updates | New features, seasonal discounts, improve performance |

---

## 🔁 Mini SDLC Example: Adding a “Discounts Section”

1. **Requirement Gathering:** Decide type of discount, eligible users, expiry date.  
2. **Design:** Plan frontend placement and backend logic.  
3. **Implementation:** Write code, update database, update frontend.  
4. **Testing:** Verify discounts apply correctly and payment works.  
5. **Deployment:** Push updates live.  
6. **Maintenance:** Fix any bugs, update offers seasonally.  

✅ Even small updates follow SDLC for **quality and consistency**.

---

## ⚙️ CI/CD in Modern SDLC

- **🔄 Continuous Integration (CI):** Merge code into a shared repository, automatically tested.  
- **🚀 Continuous Delivery (CD):** Automatically deploy tested code to staging or production.  

Benefits:
- Faster updates  
- Fewer bugs  
- Continuous improvement

---

## 🔹 Software Development Models

### 1️⃣ Waterfall Model
- **Concept:** Linear and sequential; each phase completed before the next.  
- **Example:** Full clothing website built and tested before launch.  
- **Pros:** Simple, easy to manage.  
- **Cons:** Rigid, hard to accommodate changes.  
- **Analogy:** Build entire store first, then open to customers.

### 2️⃣ Agile Model
- **Concept:** Iterative and flexible; software built in small sprints.  
- **Example:** Sprint 1: login/signup, Sprint 2: product listing, Sprint 3: cart & checkout, Sprint 4: wishlist & reviews.  
- **Pros:** Flexible, early feedback, continuous progress.  
- **Cons:** Needs strong team coordination.  
- **Analogy:** Build store sections one by one, adapt based on customer feedback.

### 3️⃣ DevOps Model
- **Concept:** Combines Development & Operations; CI/CD with monitoring.  
- **Example:** Features like cart logic or wishlist are coded, tested (CI), deployed (CD), monitored, and continuously updated.  
- **Pros:** Fast delivery, high reliability, automated testing.  
- **Cons:** Complex setup, requires skilled team.  
- **Analogy:** Continuously update and improve the store in real-time.

---

## 📊 Summary Table

| Model      | Process Flow         | Client Involvement       | Flexibility | Deployment                  |
|------------|-------------------|------------------------|------------|-----------------------------|
| Waterfall  | Linear             | Start & End            | Low        | Once at end                 |
| Agile      | Iterative/Sprints  | After each sprint      | Medium     | Frequent                    |
| DevOps     | Continuous         | Continuous + Monitoring| High       | Multiple automated releases |

---

## 🧵 Example Project: Clothing Brand E-commerce
- Product listing  
- Login & Signup  
- Cart & Checkout  
- Online Payment Gateway  
- Discounts & Seasonal Offers  
