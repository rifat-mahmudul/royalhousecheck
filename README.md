# 🏠 Royal House Check - Modern Property Monitoring Solution

**Royal House Check** is a high-performance, web-based security monitoring platform designed to provide homeowners with absolute peace of mind. It allows users to remotely oversee their property through a secure digital interface, featuring automated safety protocols and real-time system alerts.

---

## 🚀 Key Features

### 🔐 Advanced Security & Monitoring
* **Remote Surveillance Dashboard:** A centralized, secure hub to monitor property status and logs from anywhere in the world.
* **Automated Virtual Check-ins:** Sophisticated backend logic that performs periodic safety audits and generates detailed status reports.
* **Instant Emergency Alerts:** High-priority notification system designed to trigger immediate visual and system warnings during security incidents.

### 👥 Multi-Role Management
* **Admin Dashboard:** Full control over the platform, user management, and global system health monitoring.
* **User/Homeowner Portal:** Personalized view for property management, alert history, and subscription settings.

### 📊 Data & Reporting
* **Historical Activity Logs:** Comprehensive storage and retrieval of all monitoring events for auditing and insurance purposes.
* **Visual Analytics:** Intuitive charts and indicators representing property safety trends over time.

---

## 🛠️ Tech Stack

| Layer | Technology |
| :--- | :--- |
| **Frontend** | React.js, Tailwind CSS, Framer Motion (for animations) |
| **Backend** | Node.js, Express.js |
| **Database** | MongoDB (NoSQL) |
| **Authentication** | JSON Web Tokens (JWT) & Bcrypt.js |

---

## 🏗️ Architecture & Technical Highlights

* **Modular Codebase:** Developed using a modular architecture for both frontend components and backend routes, ensuring high scalability.
* **RESTful API Design:** Clean and well-documented API endpoints for seamless data flow between the client and server.
* **Secure Auth Flow:** Implementation of private routes and HTTP-only cookies to protect user sessions.
* **Responsive UI:** A "Mobile-First" design approach, ensuring the security dashboard is accessible via smartphones, tablets, and desktops.

---

## 📦 Installation & Setup

1.  **Clone the Repo:**
    ```bash
    git clone https://github.com/rifat-mahmudul/royalhousecheck
    ```

2.  **Environment Configuration:**
    Create a `.env` file in the root and server directory:
    ```env
     NEXTAUTH_SECRET=
    NEXTAUTH_URL=
    NEXT_PUBLIC_API_URL=
    NEXT_PUBLIC_SOCKET_URL=
    
    ```

3.  **Install & Run (Backend):**
    ```bash
    cd server
    npm install
    npm start
    ```

4.  **Install & Run (Frontend):**
    ```bash
    cd client
    npm install
    npm run dev
    ```
