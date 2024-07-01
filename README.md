

# Email Marketing Sequencer

**Email Marketing Sequencer** is a web application built on the MERN stack that facilitates the creation and management of automated email sequences using a visual flowchart interface. It leverages React Flow for the frontend, Agenda for email scheduling, and Nodemailer for sending emails.

## Features

- **Flowchart Interface**: Intuitive visual interface for designing email sequences.
- **Node Types**:
  - **Lead-Source**: Defines recipients for the email sequence.
  - **Cold-Email**: Represents emails to be sent, including subject and content.
  - **Wait/Delay**: Introduces delays between emails.
- **Scheduling**: Automatically schedules and sends emails based on the flowchart configuration.
- **Modal Forms**: User-friendly forms for adding and editing nodes in the flowchart.
- **Backend Integration**: Handles node and edge data to initiate email sequences.

## Technologies Used

### Frontend

- React
- React Flow
- Axios
- Modal from react-modal

### Backend

- Node.js
- Express
- Agenda
- Nodemailer
- MongoDB (via Mongoose)

## Installation

### Setup Environment Variables

Create `.env` files for both frontend and backend. Use `.env.sample` as a template and populate with appropriate values.

### Install Dependencies

```bash
# Backend
cd backend
npm install

# Frontend
cd frontend
npm install
```

### Start Backend & Frontend Servers

```bash
# Backend
cd backend
npm run dev

# Frontend
cd frontend
npm run dev
```

### Access the Application

Open your browser and go to `http://localhost:5173` to view the application.

## Environment Variables

- **Backend** (example):
  - `PORT=5000`
  - `ORIGIN=http://localhost:3000`
  - `MONGODB_URI="your-mongodb-connection-string"`
  - `MAILTRAP_HOST="live.smtp.mailtrap.io"`
  - `MAILTRAP_PORT=587`
  - `MAILTRAP_USER=api`
  - `MAILTRAP_PASSWORD="your-mailtrap-password"`
  
- **Frontend** (example):
  - `VITE_BASE_URL="http://localhost:3000"`

