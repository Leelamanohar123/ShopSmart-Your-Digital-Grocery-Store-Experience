#🛒 ShopSmart – MERN Stack Grocery Shopping Platform
##ShopSmart – MERN Stack Grocery Shopping Platform

*ShopSmart* is a full-stack online grocery shopping application built using the MERN stack. It allows customers to explore grocery categories, add products to their cart, and place orders. Vendors (store managers) can manage products and fulfill orders via their dashboards. Admins oversee the platform and can promote vendors to highlight stores on the homepage.

----

##🚀 Features
###👤 User
*Register / Login
*Browse categories and groceries
*Add items to cart and place orders
*View past and current orders

###🏪 Vendor (Store Manager)
*Login / Register
*Manage grocery products (add/update/delete)
*View and manage customer orders
-----
###🛡️ Admin
*Login
*View all vendors and customers
*Promote vendors to homepage
----
##🛠️ Tech Stack
| Layer    | Technology              |
| -------- | ----------------------- |
| Frontend | React.js + Tailwind CSS |
| Backend  | Node.js + Express.js    |
| Database | MongoDB (Mongoose)      |
| Auth     | JWT + bcrypt            |
| Styling  | Tailwind                |

-----

##📁 Folder Structure
*ShopSmart/
│
├── client/          # React frontend
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── context/
│   │   ├── styles/
│   │   └── App.js
│
├── server/          # Node + Express backend
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   └── index.js
##⚙️ Setup Instructions
###📦 Prerequisites
*Node.js (v14 or above)
*MongoDB (local or cloud - MongoDB Atlas)
----
🧩 Installation
# 1. Clone the repository
git clone https://github.com/yourusername/shopsmart.git

# 2. Install frontend dependencies
cd client
npm install

# 3. Install backend dependencies
cd ../server
npm install
▶️ Running the Application
# Start frontend
cd client
npm run dev

# Start backend
cd ../server
npm start
##🔌 API Overview
###🧑 User Routes
*POST /api/users/signup
*POST /api/users/login
*POST /api/cart
*POST /api/orders

------
##🏪 Vendor Routes
*POST /api/vendors/login
*POST /api/vendors/:id/products
*GET /api/vendors/:id/products
*GET /api/vendors/:id/orders
-----
##🛠 Admin Routes
*GET /api/vendors/all
*POST /api/admin/promote/:id
-----
##🔐 Authentication
*Passwords hashed with bcrypt
*Login state managed via Context API and JWT
-----
##🧪 Testing
*Manual testing using the UI
*API testing with Thunder Client / Postman
*Functional testing covered:
*User authentication
*Cart & order flows
*Vendor product management
*Admin control panel
----
##🖼 Demo & Screenshots
📽 [Watch Demo Video](https://drive.google.com/file/d/1LKEB09vJk6voA2a1TvIxTU8DISAIdr0c/view?usp=drivesdk)
----
##✅ Advantages
*Real-time order updates
*Role-specific dashboards (User, Vendor, Admin)
*Fast, responsive UI using React
*Secure token-based login system
----
##❌ Limitations
*No payment gateway (demo only)
*No mobile application (yet)

-----
##🌱 Future Scope
*Integrate real payment gateways (Stripe, Razorpay)
*Build a delivery partner module
*Add push notifications
*Launch mobile app with React Native
*Add sales analytics for vendors/admins
----
##📎 Documentation
###📂 Available in /documentation/ folder:

###Ideation
*Requirement analysis
*Testing reports
*Project planning
-----
##👨‍💻 Contributors
|Name                   |	Contribution
|-----------------------|-----------------------------------------|
|Manideep Jampana       |	Frontend Components, State Management   |
|Maganti Ramya	        |Vendor Dashboard, Backend API Integration |
|Madivada Leela Manohar |	UI/UX, Documentation, Routing           |
|Madhu Latha            |	Admin Panel, Backend Testing            |

----
##📂 License
This project was developed as part of a full-stack internship program. It is shared for educational and demonstration purposes. You may use or extend the code for non-commercial use with proper attribution.

License: Educational / Non-commercial Use Only
