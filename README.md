Job Portal (MERN Stack)

## Overview
A full-stack job portal application built using the **MERN (MongoDB, Express.js, React.js, Node.js) stack**. The platform allows users to browse, apply for jobs, and manage applications. Admins can manage job listings and companies.

## Project Demo
[Live Demo](https://job-portal-mern-2-eqph.onrender.com/)


## Features
### User Features
- User authentication (Login/Signup)
- Browse and search job listings
- Apply for jobs
- View application status
- Update user profile

### Company Features
- Company registration and authentication
- Post new job listings
- Manage job postings
- View applicants

### Admin Features
- Manage jobs and companies
- View all applicants
- Approve or reject job applications

## Tech Stack
- **Frontend**: React.js, Vite, Tailwind CSS
- **Backend**: Node.js, Express.js, MongoDB
- **State Management**: Redux Toolkit
- **Authentication**: JWT (JSON Web Token)
- **File Uploads**: Cloudinary
- **Middleware**: Multer, Authentication Middleware

## Installation

### Prerequisites
Make sure you have the following installed:
- Node.js
- MongoDB
- Git

### Clone the Repository
```sh
git clone https://github.com/yourusername/chegurishashikanth-job-portal-mern.git
cd chegurishashikanth-job-portal-mern
```

### Backend Setup
```sh
cd backend
npm install
```

#### Environment Variables
Create a `.env` file in the `backend/` directory and add the following:
```
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
```

#### Start the Backend Server
```sh
npm start
```

### Frontend Setup
```sh
cd ../frontend
npm install
```

#### Start the Frontend Server
```sh
npm run dev
```

## Folder Structure
```
chegurishashikanth-job-portal-mern/
├── backend/
│   ├── controllers/
│   ├── middlewares/
│   ├── models/
│   ├── routes/
│   ├── utils/
│   ├── index.js
├── frontend/
│   ├── src/
│   ├── components/
│   ├── hooks/
│   ├── redux/
│   ├── utils/
│   ├── App.jsx
│   ├── main.jsx
│   ├── index.css
│   ├── vite.config.js
```

## API Routes
### Authentication
- `POST /api/auth/signup` - Register a new user
- `POST /api/auth/login` - Authenticate user

### Jobs
- `GET /api/jobs` - Get all jobs
- `POST /api/jobs` - Create a job (Admin only)
- `GET /api/jobs/:id` - Get job by ID

### Applications
- `POST /api/applications` - Apply for a job
- `GET /api/applications` - View applied jobs

## Contributing
1. Fork the repository
2. Create a new branch (`feature-branch`)
3. Commit your changes (`git commit -m "Added new feature"`)
4. Push to the branch (`git push origin feature-branch`)
5. Open a pull request

## License
This project is licensed under the MIT License.

## Contact
For inquiries, reach out via [LinkedIn](https://www.linkedin.com/in/Cheguri-Shashikanth/).

