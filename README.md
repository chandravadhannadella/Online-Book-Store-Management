# Online Book Store Management

A simple web‑based application for managing an online book store. It provides separate interfaces for **Admins**, **Sellers**, and **Buyers** to register, log in, and perform their respective tasks.

## Features
- Home page with navigation to all sections
- Admin panel for managing users and books
- Seller registration and product management
- Buyer registration, browsing, and purchasing
- Contact and About pages
- Responsive layout using CSS

## Project Structure
```
Online-Book-Store-Management-main/
│   about.html
│   Admin.html
│   Buyer.html
│   buyerregister.html
│   contact.html
│   Home.html
│   Seller.html
│   sellerregister.html
│
└───css/
        about.css
        adminstyle.css
        buyerregister.css
        buyerstyle.css
        contact.css
        main.css
        sellerregister.css
        sellerstyle.css
        style.css
```

## Installation
1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Open the project folder in a web browser (e.g., double‑click `Home.html` or serve it via a simple HTTP server).
   ```bash
   # Using Python's built‑in server (optional)
   cd Online-Book-Store-Management-main
   python -m http.server 8000
   ```
3. No additional dependencies are required; the app runs purely with HTML, CSS, and client‑side JavaScript (if any).

## Usage
- Open `Home.html` in a browser to start.
- Navigate to the desired role (Admin, Seller, Buyer) using the navigation links.
- Register new users via the respective registration pages.
- Admins can manage listings and users through `Admin.html`.

## Contributing
Feel free to fork the repository and submit pull requests. Suggested improvements:
- Add backend support (e.g., Node.js, Django) for persistent data.
- Implement client‑side validation and dynamic UI with JavaScript frameworks.
- Enhance styling and make the site fully responsive.

## License
There is no license for this, it is an open project and can be used by anyone.
