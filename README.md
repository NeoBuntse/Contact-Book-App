# Contact-Book-App

contact-book-app/

├── index.html

├── add.contact.html

├── edit-contact.html

├── enter-api-key.html

├── config.js

├── style.css          # (not yet but will in the future)

├── screenshot.png     

├── README.md

└── .gitignore

# Contact Book App 📒

A modern web-based contact management application that allows users to add, view, edit, and delete contact entries using a remote API.

## 📱 Features

- View contact list with profile image, first name, and last name
- Add new contacts using a form (`add.contact.html`)
- Edit or delete existing contacts (`edit-contact.html`)
- API key entry for secured operations (`enter-api-key.html`)
- Responsive layout with buttons for adding and refreshing data

## 🌐 Technologies Used

- HTML
- CSS
- JavaScript
- REST API

## 🛠 How It Works

- Uses a REST API hosted at:
https://mysite.itvarsity.org/api/ContactBook/

- Data is retrieved, added, updated, and deleted via this endpoint using fetch API calls in `config.js`.

## 🗂 File Structure

| File | Description |
|------|-------------|
| `index.html` | Home page to view all contacts |
| `add.contact.html` | Form page to add a new contact |
| `edit-contact.html` | Edit or delete an existing contact |
| `enter-api-key.html` | Page to enter API key |
| `config.js` | Contains API endpoint and logic for handling contact data |

## 🔐 API Notes

To use this project, you must have a valid API key to interact with the `ContactBook` endpoint. The key is entered via `enter-api-key.html`.

## 🚀 How to Run

1. Clone the repository
2. Open `enter-api-key.html` in your browser
3. Enter your API key
4. Use the app via `index.html`

## 📸 Demo Screenshot

![image](https://github.com/user-attachments/assets/0a503373-0037-4ed4-8037-63350c10a6f4)

![image](https://github.com/user-attachments/assets/d04aa21b-c91e-416e-8e51-f49239afef0b)

![image](https://github.com/user-attachments/assets/9cf3b480-a920-40e2-809b-d864b08502da)

![image](https://github.com/user-attachments/assets/b22fb00e-f895-414a-a8c7-edd5c800cc58)


> You can take a screenshot of your app and save it as `screenshot.png` for this section.

## 📄 License

This project is licensed under the [MIT License](LICENSE).

