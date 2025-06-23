# ElevateLabs_Task1
  📚 Library Management System – Database Schema

## 🧩 Objective
Learn to create databases, tables, and define relationships.

## 🛠 Tools Used

- MySQL Workbench 
- SQL

## 📁 Files

- `Task-01.sql`: SQL script to create the complete database schema.

## 🧱 Schema Overview

This system includes the following entities:

- **Authors** – stores details about book authors.
- **Categories** – organizes books into categories.
- **Books** – stores book info with links to categories.
- **BookAuthors** – junction table for books and their authors (many-to-many).
- **Members** – library members who can borrow books.
- **BorrowRecords** – logs who borrowed what and when.


## 🔗 Relationships

- Each **book** belongs to one **category**.
- Each **book** can have multiple **authors**, and each **author** can write multiple **books**.
- Each **member** can borrow multiple **books**, and each **book** can be borrowed multiple times.


## 💡Outcome
A well-structured schema.


