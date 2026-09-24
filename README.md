# 🔐 Password Generator

A simple and interactive **Password Generator** web application built using **HTML, CSS, and JavaScript**.

The application generates random passwords based on the user's selected preferences, including password length, uppercase letters, lowercase letters, numbers, and symbols.

## 📌 Features

* Generate random passwords instantly
* Choose password length from **4 to 20 characters**
* Include uppercase letters
* Include lowercase letters
* Include numbers
* Include special symbols
* Copy the generated password to the clipboard
* Simple and responsive user interface

## 🛠️ Technologies Used

* **HTML5** – Structure of the application
* **CSS3** – Styling and responsive layout
* **JavaScript** – Password generation and functionality
* **Font Awesome** – Clipboard icon

## ⚙️ How It Works

The user can select the required password options and click **Generate Password**.

The JavaScript program dynamically checks the selected options and generates characters from the corresponding character sets.

The application supports:

* Lowercase characters
* Uppercase characters
* Numbers
* Special symbols

The password is generated according to the selected length and displayed on the screen.

## 📋 Password Options

| Option            | Description                             |
| ----------------- | --------------------------------------- |
| Password Length   | Select password length between 4 and 20 |
| Uppercase Letters | Adds A–Z characters                     |
| Lowercase Letters | Adds a–z characters                     |
| Numbers           | Adds 0–9 characters                     |
| Symbols           | Adds special characters                 |

The default configuration has all four character types enabled and a password length of 20.

## 📋 Copy Password

A clipboard button is provided to copy the generated password directly to the clipboard.

When the user clicks the clipboard button, the generated password is copied using the browser's Clipboard API.

## 📁 Project Structure

```text
Password-Generator/
│
├── index.html
├── style.css
└── scri
```
