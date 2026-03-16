# FeedFlow - RSS News Aggregator 🚀

FeedFlow is a clean, modern, and distraction-free RSS news aggregator built to keep you updated with your favorite sources in one place. Whether it's tech, world news, or niche blogs, FeedFlow organizes your feeds into a seamless reading experience.

![FeedFlow Preview](https://via.placeholder.com/800x400?text=FeedFlow+Dashboard+Preview)

## ✨ Key Features

- **Personalized Feed Management**: Add, name, and manage your own RSS feeds easily.
- **Top Stories Dashboard**: A curated "Trending" and "Categories" view for quick navigation.
- **Modern UI/UX**: Clean, responsive design with smooth transitions and loading states.
- **Authentication System**: Secure user registration and login to save your personalized feeds.
- **Feedback Loop**: Integrated feedback form to help improve the platform.
- **Admin Dashboard**: Specialized tools for administrators (e.g., managing users or site content).

## 🛠️ Tech Stack

- **Frontend**: 
  - Vanilla HTML5 & CSS3 (Custom design system)
  - JavaScript (ES6+) for dynamic feed processing
  - FontAwesome for intuitive iconography
- **Backend**:
  - PHP (Session handling & Server-side logic)
  - PDO for secure database interactions
- **Database**:
  - MySQL/MariaDB
- **APIs**:
  - RSS2JSON for reliable RSS feed parsing and proxying

## 🚀 Getting Started

Follow these steps to set up FeedFlow in your local environment.

### Prerequisites

- PHP 7.4 or higher
- MySQL 5.7 or higher
- A web server (Apache, Nginx, or local development like XAMPP/MAMP)

### Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/feedflow.git
   cd feedflow
   ```

2. **Configure the Database**
   - Create a new MySQL database (e.g., `rss_reader`).
   - Import the database schema (if provided, use the `.sql` file).

3. **Update Configuration**
   - Rename `config.php.example` to `config.php` (or edit the existing `config.php`).
   - Update your database credentials:
     ```php
     $host = 'localhost';
     $dbname = 'rss_reader';
     $username = 'your_username';
     $password = 'your_password';
     ```

4. **Launch the App**
   - Copy the files to your web server root.
   - Access the application in your browser at `http://localhost/feedflow`.

## 📖 Usage

1. **Register/Login**: Create an account to start saving your own feeds.
2. **Add a Feed**: Click the **+** button in the sidebar, enter an RSS URL and a name.
3. **Read**: Select a feed from the list. The app will fetch and display the latest articles.
4. **Delete**: Easily remove feeds you no longer wish to follow using the 'x' button.

## 🤝 Contributing

Contributions are welcome! If you have suggestions for new features or improvements:
1. Fork the project.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a Pull Request.

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

---

*© 2025 FeedFlow. All rights reserved.*
