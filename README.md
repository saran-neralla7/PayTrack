PayTrack - Futuristic Payment Reminder App
A sleek, futuristic payment reminder app that helps you track your recurring payments with style. Built with vanilla HTML, CSS, and JavaScript - no frameworks, no backend, just pure awesomeness.

✨ Features
🎨 Futuristic UI Design: Neon blue gradients, glassmorphism effects, and smooth animations that make tracking payments feel like a sci-fi experience
💰 Indian Rupee Support: All amounts displayed in ₹ (Indian Rupees) with proper formatting
📱 Fully Responsive: Works beautifully on desktop, tablet, and mobile devices
🔄 Payment Management: Add, edit, and delete payments with all the details you need
📊 Smart Dashboard: View all your payments in an elegant card layout with status indicators
📜 Payment History: Keep track of all your past payments in a separate section
🔔 Smart Notifications: Get browser notifications when payments are due (with fallback alerts)
📱 WhatsApp Integration: One-click WhatsApp reminders for each payment
🌙 Dark/Light Mode: Toggle between futuristic dark mode and clean light mode
💾 Local Storage: All data stored locally in your browser - no server required
📤 Export/Import: Backup your payment data as JSON and restore it when needed
📲 PWA Ready: Install as an app on your iOS/Android device for quick access
🚀 Getting Started
Prerequisites
A modern web browser (Chrome, Firefox, Safari, Edge)
No installation required - just open the HTML file!
Installation
Clone or download this repository
Open index.html in your web browser
Start adding your payments!
PWA Setup (Optional)
To install PayTrack as an app on your device:

Extract the manifest.json and service-worker.js files:
Open index.html in your browser
Open Developer Tools (F12)
Go to the Console tab
Type JSON.stringify(manifest, null, 2) and press Enter
Copy the output and save it as manifest.json
Type serviceWorkerCode and press Enter
Copy the output and save it as service-worker.js
Create app icons:
Create two square images: icon-192.png (192x192px) and icon-512.png (512x512px)
Use your logo or any design that represents your app
Install the app:
Open index.html in a modern browser
Look for the install icon in the address bar (usually a plus sign or download icon)
Click it to install PayTrack on your device
📝 How to Use
Adding a Payment:
Click the "Add Payment" button or the floating action button
Fill in the payment details (name, amount, frequency, start date)
Click "Save" to add it to your dashboard
Marking as Paid:
When a payment is due, click the "Mark Paid" button
The payment will move to your history section
The next due date will be automatically calculated
Setting WhatsApp Reminders:
Click the WhatsApp button on any payment card
A pre-filled message will open in WhatsApp
Send it to yourself or others as a reminder
Managing Payments:
Edit payment details anytime with the "Edit" button
Remove payments with the "Delete" button
View all past payments in the "History" tab
Backing Up Your Data:
Click "Export" to download all your payment data as JSON
Use "Import" to restore your data from a backup
🛠️ Tech Stack
HTML5: Semantic markup and structure
CSS3: Modern styling with variables, flexbox, grid, and animations
Vanilla JavaScript: No frameworks, just pure JS for all functionality
LocalStorage: For data persistence
Service Worker: For PWA capabilities
Font Awesome: For beautiful icons
Google Fonts: Poppins and Orbitron for that futuristic feel
🎨 Customization
Changing the Color Scheme
The app uses CSS variables for theming. To change colors:

css

Line Wrapping

Collapse
Copy
1
2
3
4
5
⌄
:root {
    --primary-color: #007bff;    /* Change this to your primary color */
    --secondary-color: #00d4ff;  /* Change this to your secondary color */
    /* ... other variables */
}
Adding New Features
The code is well-structured and commented. To add features:

Create a new function in the <script> section
Add event listeners in setupEventListeners()
Update the UI as needed
🤝 Contributing
Contributions are welcome! If you have a suggestion or want to improve the app:

Fork the repository
Create your feature branch (git checkout -b feature/amazing-feature)
Commit your changes (git commit -m 'Add amazing feature')
Push to the branch (git push origin feature/amazing-feature)
Open a Pull Request
📄 License
This project is licensed under the MIT License - see the LICENSE file for details.

🙏 Acknowledgments
Font Awesome for the awesome icons
Google Fonts for the beautiful typography
The PWA community for inspiration
Made with ❤️ for anyone who wants to track their payments in style!
