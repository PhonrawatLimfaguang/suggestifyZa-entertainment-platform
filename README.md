# 🎬 SuggestifyZa: Anime & K-Drama Review Platform

**SuggestifyZa** is a web-based community platform designed for **Anime** and **Korean Drama (K-Drama)** enthusiasts. The platform allows users to discover trending series, read community reviews, and manage their personal watchlists.

<img width="975" height="455" alt="image" src="https://github.com/user-attachments/assets/304e73d6-3f0f-4017-87f1-7017691df9a2" />
<img width="975" height="455" alt="image" src="https://github.com/user-attachments/assets/8c8acf41-c4bb-40e5-93eb-94c94cf29ca1" />
<img width="975" height="455" alt="image" src="https://github.com/user-attachments/assets/f0a49755-f4ed-4516-9233-c04112fa818f" />
<img width="975" height="455" alt="image" src="https://github.com/user-attachments/assets/4c958675-72e3-4605-a01d-0a540cda801e" />
<img width="975" height="455" alt="image" src="https://github.com/user-attachments/assets/c08584be-7105-4904-9744-02173ee7a816" />
<img width="975" height="455" alt="image" src="https://github.com/user-attachments/assets/8b3d7ee0-5961-4d30-816b-9dbe5d06193c" />
<img width="975" height="455" alt="image" src="https://github.com/user-attachments/assets/9cf85421-67ce-41cd-aeae-aa575a891114" />






## 📖 About The Project
Developed as part of the **Web Programming (DE251)** course, this project aims to solve the "Paradox of Choice" for entertainment lovers. By providing a centralized hub for ratings and reviews, SuggestifyZa helps users decide **"What to watch next?"** in the world of Asian entertainment.

## 🚀 Key Features

### 🌟 Content Discovery
* **Curated Lists:** Browse top-rated K-Dramas and Anime (e.g., *Start-Up, Demon Slayer, Blue Lock*).
* **Category Filtering:** Easily separate content between Anime and Series.

### ✍️ Community & Reviews
* **User Reviews:** Users can post comments and rate their favorite shows.
* **Rating System:** Dynamic calculation of average scores based on user feedback.

### 👤 User Personalization
* **Profile Management:** Users can customize their profiles, including **Avatar Uploads**.
* **Personal Watchlist:** Save interesting titles to a private "Watch Later" list.
* **Account Security:** Secure Login/Register system with session management.

## 🛠️ Tech Stack

* **Frontend:**
    * HTML5, CSS3 (Custom Grid System - `grid.css`)
    * JavaScript (DOM Manipulation)
* **Backend:**
    * **PHP (Native)** - Server-side logic and session handling.
* **Database:**
    * **MySQL** - Relational database for storing users, content, and reviews.
* **Architecture:**
    * MVC-inspired structure (separating Logic, View, and Database).

## 💾 Database Structure
The system is powered by a Relational Database (see `SQL_WEB.sql`). Key tables include:

| Table Name | Description |
| :--- | :--- |
| `users` | Stores user credentials, email, and profile image paths. |
| `content` | Metadata for Anime & K-Dramas (Title, Genre, Description). |
| `reviews` | Stores user comments and ratings (Linked to `users` and `content`). |
| `watchlist` | Many-to-Many relationship table for user's saved items. |

## ⚙️ Installation Guide (Localhost)

1.  **Clone the repository**
    ```bash
    git clone [https://github.com/PhonrawatLimfaguang/suggestifyZa-entertainment-platform.git](https://github.com/PhonrawatLimfaguang/suggestifyZa-entertainment-platform.git)
    ```
2.  **Setup Web Server**
    * Use **XAMPP** or **WAMP**.
    * Move the project folder to `htdocs` (XAMPP) or `www` (WAMP).
3.  **Import Database**
    * Open **phpMyAdmin** (`http://localhost/phpmyadmin`).
    * Create a new database named `suggestify_db` (or check `db_connection.php` for the name).
    * Import the **`SQL_WEB.sql`** file provided in this repo.
4.  **Configure Connection**
    * Check `db_connection.php` to ensure username/password matches your local MySQL setup.
5.  **Run**
    * Open browser: `http://localhost/suggestifyZa-entertainment-platform/index.php`

## 👥 Development Team
* **Phonrawat Limfaguang** - *Fullstack Developer & Database Design*
* **Pannathorn** - *Frontend & UX/UI*
* **Phonlawit** - *Content Management & Testing*

---
