# ⚽ Football Ticket Booking System

## 📖 Assignment Overview

This project is a PostgreSQL-based Football Ticket Booking System designed to manage users, football matches, and ticket bookings.

The assignment demonstrates:

- Database Design
- Entity Relationship Diagram (ERD)
- Primary Keys & Foreign Keys
- SQL Constraints
- SQL Queries
- Joins
- Subqueries
- Aggregation Functions

---

## 🗄️ Database Tables

### 👤 Users

Stores information about football fans and ticket managers.

| Field | Description |
|---------|-------------|
| user_id | Primary Key |
| full_name | User's full name |
| email | Unique email address |
| role | Football Fan / Ticket Manager |
| phone_number | Contact number |

---

### ⚽ Matches

Stores football match information.

| Field | Description |
|---------|-------------|
| match_id | Primary Key |
| fixture | Match teams |
| tournament_category | Tournament name |
| base_ticket_price | Ticket price |
| match_status | Availability status |

---

### 🎟️ Bookings

Stores ticket booking records.

| Field | Description |
|---------|-------------|
| booking_id | Primary Key |
| user_id | Foreign Key |
| match_id | Foreign Key |
| seat_number | Assigned seat |
| payment_status | Payment state |
| total_cost | Booking amount |

---

## 🔗 Relationships

- One User can create multiple Bookings.
- One Match can have multiple Bookings.
- Each Booking belongs to exactly one User and one Match.

---

## 📂 Project Files

text QUERY.sql ERD.png README.md 

---

## 🛠️ Technologies Used

- PostgreSQL
- Beekeeper Studio
- Draw.io

