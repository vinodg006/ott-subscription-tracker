![Title](images/title.jpg)

<div align="center">
 <img src="https://img.shields.io/badge/node.js-339933?style=for-the-badge&logo=Node.js&logoColor=white" alt="node.js" />
    <img src="https://img.shields.io/badge/express.js-000000?style=for-the-badge&logo=express&logoColor=white" alt="express.js" />
    <img src="https://img.shields.io/badge/-MongoDB-13aa52?style=for-the-badge&logo=mongodb&logoColor=white" alt="mongodb" />
</div>

# OTT Subscription Tracker

OTT Subscription Management System API that handles users, money, and business logic.

Authenticate users using JWTs, connect a database, create models and schemas, and integrate it with ORMs. Structure the architecture of your API to ensure scalability and seamless communication with the frontend.


## <a name="features">🔋 Features</a>

👉 Advanced Rate Limiting and Bot Protection: with Arcjet that helps you secure the whole app.

👉 Database Modeling: Models and relationships using MongoDB & Mongoose.

👉 JWT Authentication: User CRUD operations and subscription management.

👉 Global Error Handling: Input validation and middleware integration.

👉 Logging Mechanisms: For better debugging and monitoring.

👉 Email Reminders: Automating smart email reminders with workflows using Upstash.



## Tech Stack

**Framework:** Express.js

**Database:** MongoDB

**ORM:** mongoose

**User Authentication and Authorization:** JWT, [Arcjet](https://arcjet.com/), cookie-parser

**Reminder Email Workflow Management:** [Upstash](https://upstash.com/) , nodemailer using gmail as transporter

## <a name="quick-start">🤸 Quick Start</a>

Follow these steps to set up the project locally on your machine.


**Installation**

Install the project dependencies using npm:

```bash
npm install
```

**Set Up Environment Variables**

Create a new file named `.env.local` in the root of your project and add the following content:

```env
# PORT
PORT=5500
SERVER_URL="http://localhost:5500"

# ENVIRONMENT
NODE_ENV=development

# DATABASE
DB_URI=

# JWT AUTH
JWT_SECRET=
JWT_EXPIRES_IN="1d"

# ARCJET
ARCJET_KEY=
ARCJET_ENV="development"

# UPSTASH
QSTASH_URL=http://127.0.0.1:8080
QSTASH_TOKEN=

# NODEMAILER
EMAIL_PASSWORD=
```


**Running the Project**

```bash
npm run dev
```

## <a name="snippets">🕸️ Snippets</a>

<details>
<summary><code>Dummy JSON Data</code></summary>

```json
{
  "name": "Javascript Mastery Elite Membership",
  "price": 139.00,
  "currency": "USD",
  "frequency": "monthly",
  "category": "Entertainment",
  "startDate": "2025-01-20T00:00:00.000Z",
  "paymentMethod": "Credit Card"
}
```

</details>
