# Instagram User Analytics

This project focuses on **analyzing Instagram user data** using **Python (Jupyter Notebook)** and **MySQL**.  
It is designed to help **Instagram’s Marketing Team** and **Investors** make data-driven decisions about user engagement, campaigns, and overall platform performance.

---

## Project Overview
- **Marketing Team Goals**:
  - Identify loyal (oldest) users
  - Detect inactive users
  - Analyze popular hashtags
  - Launch contests & ads based on user activity
- **Investor Goals**:
  - Measure user engagement
  - Detect bots and fake accounts
  - Assess if Instagram is staying relevant  

The project integrates **Python with MySQL** using the `mysql.connector` library to run SQL queries and analyze results in **Pandas DataFrames** for further exploration and visualization.

---

## Database Schema
The database used is named **`ig_clone`**, containing the following tables:
- **users** → registered user details  
- **photos** → uploaded photos info  
- **tags** → hashtags used  
- **photo_tags** → mapping photos with tags  
- **likes** → user likes on photos  
- **comments** → user comments on photos  
- **follows** → followers and followings  

[Database Creation Commands](https://docs.google.com/document/d/1-WhNRX1iYJIz7e5l28DMPWgsPklpE_w6/edit)

---

## Tech Stack
- **MySQL** → Database  
- **Python (Jupyter Notebook)** → Analysis & Visualization  
- **mysql.connector** → Database integration  
- **Pandas** → Query results transformation  


