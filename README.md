# 🔐 Secure User Authentication System with Dynamic Passcode Login 🚀

Welcome to the **Secure User Authentication System** project! This application demonstrates secure login and registration functionality using **PHP**, **MySQL**, **HTML**, and **CSS**. The system features a unique 4-digit passcode mechanism to enhance security and provide a smooth user experience.

## 🌟 Features

* **User Registration**
  * Users can create an account by providing a **username**, **email**, and **password**
  * A unique 4-digit **passcode** is generated for each user during registration
  * The passcode is displayed in a **popup** with a copy button for convenience

* **Passcode Login**
  * Users can log in using their email and password or by entering their **4-digit passcode**

* **Email Validation**
  * The system checks if the **email** is already in use and prompts users to choose a different email address

* **Secure Authentication**
  * Passwords are securely hashed using **BCRYPT**

* **Modern & Responsive UI**
  * The app has a clean and responsive design with modern **CSS** techniques, including gradients, hover effects, and smooth transitions

## 🛠 Technologies Used

* **Frontend**
  * HTML, CSS (Responsive Web Design)

* **Backend**
  * PHP, MySQL

* **Security**
  * **Password Hashing** with BCRYPT
  * **Passcode-Based Login Authentication**

## ⚙️ Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/secure-auth-system.git
   ```

2. **Set up the Database**:
   * Create a MySQL database named `user_auth`
   * Import the following SQL to create the necessary table:
     ```sql
     CREATE TABLE users (
       id INT AUTO_INCREMENT PRIMARY KEY,
       username VARCHAR(100) NOT NULL,
       email VARCHAR(100) NOT NULL UNIQUE,
       password VARCHAR(255) NOT NULL,
       passcode INT NOT NULL
     );
     ```

3. **Configure Database Connection**:
   * Open `config.php` and update the database connection settings with your own MySQL credentials

4. **Run the Application**:
   * Upload the files to your server or run it locally with a PHP server
   * Visit the registration page to sign up and the login page to access the system

## 🔑 How to Use

1. **Sign Up**:
   * Go to the registration page and fill in the details
   * After submitting, a **passcode** will be generated and displayed in a popup for the user to copy

2. **Login**:
   * Enter the **email** and **password**, or use the **4-digit passcode** in the provided popup
   * Upon successful login, you will be redirected to the **dashboard**

## 🎨 UI Design

* The design uses modern CSS with smooth transitions, hover effects, and a professional layout
* The passcode is shown in a clean, accessible popup for easy copying

## 📝 Contribution

Contributions are welcome! If you find any bugs or have ideas for new features, feel free to fork the repository, create a branch, and submit a **pull request**.

## 👨‍💻 Contact

* **GitHub**: [Kavishnu-G](https://github.com/Kavishnu-G/)
* **Email**: kavishnug@gmail.com
* **LinkedIn**: [KAVISHNU -G](https://www.linkdin.com/in/kavishnu-g-1a8612288)

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 👏 Acknowledgements

* Thanks to all open-source contributors for making this project possible
* Special thanks to **Stack Overflow** and **MDN Web Docs** for their helpful resources during development
