# 🏋️‍♂️ Gym Site

Welcome to the Gym Site repository! This project is a full-featured web application for a gym, built using the MERN stack (MongoDB, Express.js, React.js, Node.js). The site provides a comprehensive solution for gym enthusiasts to explore services, check pricing, book workout sessions, and get in touch with the gym.

## ✨ Features

- **User-Friendly Interface:** A modern and responsive design built with React.js to ensure a seamless user experience.
- **Contact Form:** Users can easily get in touch with the gym through the contact form. Messages are processed and sent using the backend email service.
- **Workout Sessions:** Browse and book various workout sessions offered by the gym.
- **BMI Calculator:** A handy tool for users to calculate their Body Mass Index.
- **Photo Gallery:** A visual showcase of the gym's facilities and events.
- **Pricing Plans:** Detailed information about the various membership and session pricing plans.

## 🛠️ Technologies Used

- **Frontend:**
  - React.js (`^18.3.1`)
  - React Router DOM (`^6.24.1`)
  - Axios (`^1.7.2`)
  - React Spinners (`^0.14.1`)
  - React Toastify (`^10.0.5`)
  - Lucide React (`^0.400.0`)

- **Backend:**
  - Node.js
  - Express.js (`^4.19.2`)
  - Nodemailer (`^6.9.14`)
  - Dotenv (`^16.4.5`)
  - CORS (`^2.8.5`)

## 🚀 Getting Started

### Prerequisites

- Node.js and npm installed
- MongoDB instance running locally or on a cloud service

### Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/your-username/gym-site.git
   cd gym-site
   ```

2. **Setup Backend:**
   ```sh
   cd backend
   npm install
   ```

3. **Setup Frontend:**
   ```sh
   cd ../frontend
   npm install
   ```

4. **Set Environment Variables:**
   - Create a `config.env` file in the `backend` directory with the following variables:

     ```sh
     PORT=<your-backend-port>
     FRONTEND_URL=<your-frontend-url>
     SMTP_HOST=smtp.gmail.com
     SMTP_PORT=465
     SMTP_SERVICE=gmail
     SMTP_MAIL=your-email@gmail.com
     SMTP_PASSWORD=your-email-password
     ```

### Running the Application

1. **Start Backend Server:**
   ```sh
   cd backend
   node app.js
   ```

2. **Start Frontend Development Server:**
   ```sh
   cd frontend
   npm run dev
   ```

3. **Access the Application:**
   - Open your browser and navigate to `http://localhost:5173`

## 🌐 Deployment

### Backend

The backend can be deployed on platforms like Heroku, AWS, or any other cloud service that supports Node.js applications. Make sure to set up your environment variables for SMTP settings and any other configurations needed.

### Frontend

The frontend can be deployed on platforms like Vercel, Netlify, or any static site hosting service. Ensure the frontend is configured to communicate with the backend URL.

## 🤝 Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes. For major changes, please open an issue first to discuss what you would like to change.

