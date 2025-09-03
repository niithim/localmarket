🛒 Local Market Website

A web-based local marketplace platform that allows users to browse products and place orders. Built to provide a smooth and intuitive shopping experience. Currently, after booking, only the admin can view/manage orders.

🚀 Features

🛍️ Product Catalog – Browse products with images, descriptions, and prices.

🛒 Shopping Cart & Checkout – Add/remove products and complete the order process.

🎨 Responsive Design – Works perfectly on desktop, tablet, and mobile devices.

⚡ Frontend Technologies – Built using HTML, CSS, Bootstrap, and JavaScript.

🔒 Admin-only Booking Management – After booking, only the admin can view/manage orders. Users cannot see their order status yet.

🛠️ Tech Stack

Frontend: HTML, CSS, Bootstrap, JavaScript

Backend / Data Storage: Google Sheets (via Google Apps Script)

Hosting: GitHub Pages 

📂 Project Structure
localmarket/
│── index.html          # Home page
│── product.html        # Product listing / details page
│── cart.html           # Shopping cart page
│── order-form.html     # Booking/order form page
│── style.css           # Custom styles
│── script.js           # JavaScript functionality
│── /assets             # Images, icons, and static files
│── README.md           # Project documentation

⚙️ Setup & Installation

Clone the repository:

git clone https://github.com/niithim/localmarket.git


Open index.html in your browser.

Connect the booking form with Google Sheets (via Google Apps Script):

Create a Google Sheet for storing bookings/orders.

Write a Google Apps Script to handle form submissions.

Deploy it as a Web App and copy the endpoint URL.

Update the form’s action attribute with this URL.

📊 Workflow

Users browse products and submit a booking/order form.

Booking/order data is sent to Google Sheets via Apps Script.

Admin can view and manage all bookings/orders.

Users cannot see their order status in the current version.

🎯 Future Enhancements

🔐 User Accounts – Allow users to view their booking history.

💳 Online Payment Integration – Support payments directly through the platform.

📩 Notifications – Email/SMS updates for users about their orders.

📊 Admin Dashboard – Analytics for orders, popular products, and trends.

🛠️ Vendor Portal – Vendors can manage inventory and orders directly.

🚚 Live Order Tracking – Allow users to track their orders in real-time.

👨‍💻 Author

Nitin Kumar
Technologies used: HTML, CSS, Bootstrap, JavaScript, Google Apps Script
