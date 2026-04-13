# Agricultural Database System

## 📌 Project Overview
This project implements a relational database system for managing agricultural services. 
It supports data collection, monitoring, and reporting for farmers, farms, and agricultural activities.

The system is designed based on an Enhanced Entity Relationship Diagram (EERD) and implemented using MySQL.

---

## 🎯 Objectives
- To model agricultural data efficiently
- To support farmer registration and farm management
- To track production and seasonal activities
- To manage agricultural inputs and extension services
- To enforce data integrity using constraints and triggers

---

## 🧱 System Components

### 1. Entities
- Person (Farmer, Extension Worker, Ministry Official)
- Farm
- Production
- Coffee Variety & Type
- Input Distribution
- Reports
- Location (Region, District, Subcounty)

### 2. Relationships
- Farmers own farms
- Farms produce crops
- Extension workers visit farms
- Inputs are distributed to farms
- Reports are generated from field activities

---

## ⚙️ Technologies Used
- MySQL (Database)
- SQL (DDL, DML, Triggers, Procedures)
- GitHub (Version Control)

---

## ▶️ How to Run the Project

### Step 1: Open MySQL
### Step 2: Import the database

```sql
SOURCE database/agric_db.sql;
