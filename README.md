# COMP3304 PROJECT - WAITERLY (Smart Digital Waiter System)

## DESCRIPTION
Waiterly is a Smart Digital Waiter System designed to address the issue of traditional menus being organized around products rather than customer moods or requests. It is an innovative digital ordering website for cafés, bars, and restaurants that provides a personalized ordering experience. The system aims to speed up the ordering process, reduce waiting times, and improve overall customer satisfaction while helping businesses operate more efficiently and cost-effectively.

## TECH STACK
* **Frontend:** React and HTML
* **Backend:** Node.js
* **Database:** MongoDB

## KEY FEATURES
* **QR Code Menu Access & Table Session:** Customers can scan a QR code to access the digital menu, enter their table number, start a secure ordering session, and view their total bill.
* **Mood-Based Recommendations:** The system suggests drinks or meals according to the user's current mood, turning a simple task into an enjoyable experience.
* **Ingredient Selection & Custom Creations:** Users can choose specific ingredients they want, allowing them to create personalized cocktails or meals.
* **Allergen & Ingredient Visibility:** Provides clear allergen details for each item to help customers with allergies order safely.
* **Order Notification System:** Sends real-time order notifications to staff, ensuring fast and efficient service.
* **Admin Panel (Menu Management):** Allows business owners or staff to easily update menu items, prices, and availability through a centralized system.
* **Product Rating & Popular Items:** Users can rate consumed products, contributing to a "most liked" section to help future customers discover popular items.

## SYSTEM ARCHITECTURE & DESIGN
* **Layered Architecture:** The application is separated into a Presentation Layer (UI), Application Layer (business logic like orders and recommendations), and Data Layer (databases) to ensure modularity, scalability, and easy maintenance.
* **Strategy Pattern:** Implemented in the recommendation system to dynamically switch between two algorithms: mood-based filtering and ingredient-based filtering.
* **Observer Pattern:** Implemented in the order notification system to provide real-time updates across multiple components, instantly notifying waiter panels and kitchen screens when a new order is placed.

## GOALS & IMPACT
* Speed up the ordering process and reduce customer waiting times.
* Optimize staff workload and help business owners handle rush hours without needing to hire additional staff.
* Create an engaging, interactive, and mood-centered menu experience.
* Allow customers to easily request additional service (like calling the waiter) directly through the website without leaving their table.

## TEAM MEMBERS (Team Server)
* Bora Çetin
* Emre Dağlı
* Dilan Işık
* Ahmet Burak Namal
