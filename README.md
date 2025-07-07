
# 🧠 Task S2.03. Data Structure - MongoDB

---

## 📄 Description – Project Overview

This repository contains a series of structured exercises focused on designing NoSQL databases using MongoDB. The goal is to practice logical database modeling for real-world scenarios, emphasizing document-oriented design principles and proper schema structuring.

The exercises progress through three difficulty levels, from basic data models to more complex applications involving multiple collections and relationships.

---

## 🎯 Objectives

- Learn how to model NoSQL databases using MongoDB.
- Understand schema design concepts such as embedded documents, references, and data duplication.
- Validate that the database models support typical application queries and workflows.

---

## 💻 Technologies Used

- MongoDB for document-based database modeling and querying.
- Optional: MongoDB Compass or any other GUI tool for visualizing collections.
- Git & GitHub for version control.

---

## 📋 Requirements

- Basic knowledge of MongoDB and NoSQL databases.
- MongoDB installed locally or access to a cloud MongoDB service (optional).
- Basic familiarity with JSON and document structure.

---

## 🛠️ Installation and Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/luriguso/TaskS203DataStructureMongoDB.git
   cd TaskS203DataStructureMongoDB
   ```

2. Review the exercise descriptions and proposed schema designs.

3. Implement the MongoDB collections and documents based on the exercises.

4. Use MongoDB shell or Compass to insert sample data and run queries to validate your design.

---

## 🧩 Exercises and Levels

### 🔹 Level 1 – Optics “Cul d'Ampolla”

A local optics shop wants to manage customers and eyeglass sales.

- **Provider:** Store details like name, full address (street, number, floor, door, city, postal code, country), phone, fax, and tax ID.
- **Glasses:** Include brand, lens prescription for each glass, frame type (floating, plastic, metal), frame color, lens colors, and price.
- **Clients:** Store name, postal address, phone, email, registration date, and if applicable, the recommending client.
- **Sales:** Track which employee sold which eyeglasses and record the date/time of each sale.

**Exercise 1:**  
Design the database from the customer’s interface perspective.

**Exercise 2:**  
Design the database from the glasses’ perspective.

---

### 🔹 Level 2 – Food Delivery Web Application

Design a database for an online food ordering website.

- **Clients:** Store unique ID, name, surname, address, postal code, city, province, and phone number.
- **Orders:** Each order has a unique ID, date/time, delivery type (delivery or pickup), quantities of products, total price, and additional notes.
- **Products:** Include pizzas, burgers, and drinks with unique ID, name, description, image, and price.
- **Stores:** Each store has a unique ID, address, postal code, city, and province.
- **Employees:** Each employee works at one store with details like name, surname, tax ID, phone, role (cook or delivery person).
- Track which employee delivered each order and the delivery date/time.

---

### 🔹 Level 3 – Simplified YouTube Model

Model a simple version of a video-sharing platform.

- **Users:** Store unique ID, email, password, username, birth date, gender, country, and postal code.
- **Videos:** Store unique ID, title, description, file size, filename, duration, thumbnail, views, likes, dislikes.
- Video states: public, hidden, private.
- Store which user uploaded each video and the upload date/time.
- **Channels:** Each user can create a channel with unique ID, name, description, and creation date.
- **Subscriptions:** Users can subscribe to other users’ channels.
- **Likes/Dislikes:** Track which user liked or disliked each video and when.
- **Playlists:** Users can create playlists with videos, having a name, creation date, and visibility (public/private).
- **Comments:** Users can comment on videos; comments have unique IDs, text, and timestamp.

---

## 📌 Validation Queries

Example queries to validate database design include:

- Optics: Find total sales per client in a date range, glasses sold by employee, suppliers for sold glasses.
- Food Delivery: Count products sold by category in a city, orders handled by a specific employee.
- YouTube: List videos per user, subscribers per channel, likes/dislikes on a video.

---

## 🌐 Deployment

This project is for educational use and is not intended for production deployment.

---

## 🤝 Contributions

Contributions are welcome. To contribute:

1. Fork the repository.  
2. Create a feature branch: `git checkout -b feature/my-feature`  
3. Commit your changes.  
4. Push to your branch: `git push origin feature/my-feature`  
5. Open a Pull Request.

---

## ✨ Author

[Your Name] – [luriguso]  
🌐 [GitHub Profile](https://github.com/luriguso)

---

## 📝 License

This project is for educational purposes only and not licensed for commercial use.

