# PrintEasy

PrintEasy is an online platform designed to streamline print shop operations by offering a convenient, user-friendly interface for customers and shop owners alike. It simplifies the process of placing print orders, monitoring status, and managing shop settings, enhancing overall efficiency and user experience.

- **Hosted Link**: [https://print-easy.vercel.app/](https://print-easy.vercel.app/)

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features
- **User Authentication**: Secure login and registration for both users and shop owners using PassportJS.
- **Print Order Management**: Seamless ordering system that allows users to upload files and monitor order status.
- **Priority Feature**: Users can expedite their print orders with a nominal fee for urgent needs.
- **User & Shop Portals**: Separate dashboards for users and shop owners to manage orders, customization, and shop settings.
- **File Sharing**: Hassle-free file sharing for users without the need to log in.
- **Notification System**: Real-time updates and alerts for users regarding order status.
- **Distinct Portals**: Separate portals for shop owners and users to customize shop settings and manage print orders.

## Technologies Used
- **Frontend**: React.js, Redux, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: PassportJS, Google OAuth
- **File Management**: Multer for file uploads
- **PDF Handling**: react-pdf for PDF file rendering and manipulation
- **Other Libraries**: react-toastify (notifications), archiver, react-qrcode

## Installation
To get a local copy up and running, follow these steps:

1. **Clone the repository:**
    ```bash
    git clone https://github.com/AyushSinghSrikoti/PrintEasy.git
    ```

2. **Navigate to the project directory:**
    ```bash
    cd PrintEasy
    ```

3. **Install dependencies:**
    ```bash
    npm install
    ```

4. **Set up environment variables:**
    Create a `.env` file in the root directory and add your configuration variables:
    ```plaintext
    MONGO_URI=your_mongodb_connection_string
    JWT_SECRET=your_jwt_secret
    ```

5. **Start the development server:**
    ```bash
    npm start
    ```

## Usage
- **User Portal**: Users can upload files, place print orders, and track order status.
- **Shop Owner Portal**: Shop owners can customize print settings, manage orders, and view analytics.
- **Priority Feature**: Users can pay a nominal fee to expedite their print jobs.
- **File Upload**: Users can share files easily without needing to log in.

## Contributing
Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project.
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`).
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the Branch (`git push origin feature/AmazingFeature`).
5. Open a Pull Request.

## License
Distributed under the MIT License. See `LICENSE` for more information.

## Contact
- **Project Link**: [https://github.com/AyushSinghSrikoti/PrintEasy](https://github.com/AyushSinghSrikoti/PrintEasy)
- **Email**: [ayushsinghsrikoti@gmail.com](mailto:ayushsinghsrikoti@gmail.com)
- **Website**: [My website](https://thriving-semolina-bd662b.netlify.app/)
