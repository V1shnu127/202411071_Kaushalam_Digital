# 202411071_Kaushalam_Digital
Campus Placement Company Test conducted between 22 Oct 2025 to 23 Oct 2025

## Online Shopping Cart (E-Commerce Website): Electronic products to be sold Online

### Users receive emails for:
- New User Registration
- Order Successfully Placed
- Out-of-stock item now back in stock
- Successful shipment & delivery

### Technologies Used
#### Backend ####
• Node.js + Express.js (MVC structure) 
• SQL Database (MySQL or PostgreSQL) 
• MongoDB (for product catalog) 
• Prisma ORM or native database drivers 
• JWT authentication with bcrypt password hashing 

#### Frontend ####
• Next.js 14+ (App Router, TypeScript) 
• Tailwind CSS or CSS Modules for styling 

#### Backend Folder Structure  ####
backend <br>
├── models <br>
├── controllers <br>
├── routes <br>
├── config <br>
├── tests <br>
└── server.js <br>

#### Frontend Folder Structure ####
frontend <br>
├── app <br>
│   ├── products <br>
│   ├── cart <br>
│   └── orders <br>
├── components <br>
└── lib <br>

#### Responsibilities ####
• Models: Database schema and queries <br>
• Controllers: Application and business logic <br> 
• Routes: HTTP endpoints and middleware <br>
• Views: Next.js pages and components 


#### Features to Implement ####
1. Authentication <br>
JWT-based login/signup/logout <br>
bcrypt password hashing <br>
Role-based (admin, customer) <br>
To show logged-in user’s name in header <br>

2. Product Management <br>
Products stored in MongoDB <br>
admin: create/update/delete products <br>
password: adminpass123 <br>
Search, category filter, pagination <br>
Server-side sorting (price DESC default, switchable by evaluator request) <br>

4. Cart & Checkout <br>
Add/remove items <br>
Checkout to create SQL orders + order_items <br>
Server computes total <br>

5. Reports <br>
SQL aggregation: e.g. daily revenue <br>
MongoDB aggregation: e.g. category-wise sales <br>
Display both on “Reports” page
