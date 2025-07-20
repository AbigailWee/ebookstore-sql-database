# Architecting Success: A Tailored Database System for Efficient E-Bookstore Management

## 📚 Introduction
The E-Bookstore, based in Kuala Lumpur, Malaysia, houses an extensive collection of books across various genres, sourced from multiple publishers. As the business expanded, the management initiated the development of an online store to reach a broader customer base and streamline book purchases. 

This project involves designing and implementing a robust database system to support the operations of this newly established electronic bookstore.

## 📋 Business Rules
- The bookstore purchases books from publishers, which are then sold to its members. The bookstore manager compiles a list of needed books and sends an order to the publishers. The publisher supplies the ordered books to the bookstore. The manager records the details of the new books that have arrived. An invoice is sent to the accounts department to be processed and paid.
- Anyone who wishes to purchase books online must first register as a member. Members can view book information and read reviews.
- Members who wish to purchase can add books to their shopping cart. The cart displays a summary of the selection and the total cost. Once payment is made, the bookstore will deliver the books to members within 7 working days.
- The database should manage information about books in the bookstore, members, and the books they have ordered.
- Members can also provide a review for a book, including a rating (1–10, where 1 = terrible and 10 = masterpiece) along with optional short text. No changes are allowed; only one review per member per book is permitted.

## 📈 Diagrams

#### Entity Relationship Diagram (Crow’s Foot Notation)
![Entity Relationship Diagram](https://github.com/user-attachments/assets/1397badc-92df-4620-b47b-becbab40df02)

#### Database Diagram
![Database Diagram](https://github.com/user-attachments/assets/d3ac0e46-cd6a-4e6f-afd3-682756abede4)

## ❓Business Queries to be Addressed
- Find the total number of feedback entries per book. Show book ID, book title, and total number of feedback entries per book.
- Find the total number of feedback entries per member. Show member ID, member name, and total number of feedback entries per member.
- Find the total number of books published by each publisher. Show publisher ID, publisher name, and number of books published.
- Find the total number of books for each category. Show category ID, category name, and number of books per category.
- List the books where the quantity is more than the average quantity of all books (from the book table).
- Show how many books exist for each genre.
- Show the members who did not place any orders.
- Find the average rating for each book.
- Show the total number of books added to shopping carts.
- Show the members who made more than 2 orders.

## 🖇️ Additional Aspects Covered in the Project
- Benefits of databases and Database Management Systems in managing electronic bookstores.
