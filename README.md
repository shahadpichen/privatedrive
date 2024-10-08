# ZeroDrive

**ZeroDrive** is a tool that keeps your Google Drive files secure with end-to-end encryption. Here’s what you need to know:

## Key Features

- **End-to-End Encryption:** Your files are encrypted on your device before uploading to Google Drive. Only you can decrypt them.
- **Open Source:** The code is fully available for review, ensuring transparency and trust.
- **Easy to Use:** Drag, drop, and encrypt—no technical skills needed.
- **Customizable:** Review, modify, and host the tool on your own servers if desired.
- **IndexedDB Storage:** Efficient local storage management.

## Getting Started

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/shahadpichen/zerodrive.git
   ```

2. **Install Dependencies:**
   ```bash
   cd zerodrive
   npm install
   ```
3. **Set Environment Variables:**
   
    Before starting the application, make sure to add the following environment variables:
   
   ```bash
   REACT_APP_PUBLIC_CLIENT_ID
   REACT_APP_PUBLIC_SCOPE
   ```
   You can add these variables in a .env.local file in the project root.
5. **Run the Application:**
   ```bash
   npm start
   ```
4. Visit localhost:3000 in your browser to start using ZeroDrive.

## Contact

For support or questions, open an issue on GitHub
