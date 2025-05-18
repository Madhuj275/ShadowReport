
# ShadowReport

ShadowReport is a modern web application built using **Next.js**, **TypeScript**, **Prisma**, and **Tailwind CSS** that enables users to securely submit and track incident reports. It includes user authentication, a step-by-step reporting wizard, and an admin dashboard to review submitted reports.


ShadowReport simplifies the process of submitting and tracking sensitive or anonymous reports, such as safety incidents or internal observations. The platform ensures structured data collection through a form wizard, real-time tracking, and secure authentication.

<br></br>

## ✨ Features

* 🧩 Multi-step Report Wizard: Intuitive step-by-step report submission interface.
* 🔐 Authentication: Secure sign-up/sign-in using NextAuth.
* 📊 Dashboard: Overview of reports for authenticated users.
* 🗺️ Location Input: Select or enter a location for the incident.
* 📦 API Integration: RESTful API routes using the Next.js App Router.
* 💅 Tailwind CSS Styling: Clean and responsive design.
* 🔄 Report Tracking: Users can track the status of submitted reports.

<br></br>

## 🛠 Tech Stack

| Layer       | Technology                  |
| ----------- | --------------------------- |
| Frontend    | React, Next.js (App Router) |
| Styling     | Tailwind CSS, PostCSS       |
| Backend/API | Next.js API Routes          |
| Auth        | NextAuth.js                 |
| Database    | Prisma ORM, PostgreSQL      |
| Language    | TypeScript                  |
| Build Tools | Vite, tsconfig              |

<br></br>

## ⚙️ Installation & Setup

### Prerequisites

* Node.js ≥ 18
* PostgreSQL Database
* npm or yarn

### Steps

1. **Clone the Repository**

   ```bash
   git clone https://github.com/yourusername/ShadowReport.git
   cd ShadowReport
   ```

2. **Install Dependencies**

   ```bash
   npm install
   ```

3. **Setup Environment Variables**
   Create a `.env` file in the root and define:

   ```env
   DATABASE_URL=postgresql://<user>:<password>@localhost:5432/<dbname>
   NEXTAUTH_SECRET=your-secret
   NEXTAUTH_URL=http://localhost:3000
   ```

4. **Run Database Migrations**

   ```bash
   npx prisma migrate dev
   ```

5. **Start the Development Server**

   ```bash
   npm run dev
   ```

---
<br></br>
## Interface

<br></br>
![image](https://github.com/user-attachments/assets/6ca51c55-ff8c-4860-bcc5-2e43e1244358)


