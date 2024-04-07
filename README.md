# Mini-Project-4

# Intelligent Parking Management System

This project is an intelligent parking management system that leverages computer vision techniques and real-time data synchronization to provide users with up-to-date information on parking availability. The system consists of two main components: a backend component for video processing and data synchronization, and a frontend web application for visualizing parking availability.

## Backend

The backend component, located in the `server/` folder, is responsible for processing the video feed from a parking camera using OpenCV. It detects vacant and occupied parking slots by analyzing the video frames and comparing them with predefined parking slot coordinates. The status of each parking slot (occupied or vacant) is continuously updated in the Firebase Realtime Database, ensuring real-time data availability.

**Technologies and Tools:**
- OpenCV (for computer vision tasks)
- Python
- Pyrebase (for interacting with Firebase)
- Firebase Realtime Database

## Frontend

The frontend component, located in the `client/` folder, is a Next.js web application that fetches real-time parking data from the Firebase Realtime Database. It provides a user-friendly interface for visualizing the current status of each parking slot, allowing users to quickly identify available spaces. The frontend seamlessly integrates with the backend, displaying the latest parking data as it is updated in the database.

**Technologies and Tools:**
- Next.js (React framework for server-rendered applications)
- JavaScript
- Firebase Realtime Database

## Getting Started

Follow the instructions below to set up and run the project locally.

### Prerequisites

- Node.js and npm installed on your machine
- Python and pip installed on your machine

### Installation

1. Clone the repository: https://github.com/rohit4242/Mini-Project-4

2. Navigate to the `client/` folder and install the required dependencies:
 `npm install `


3. Navigate to the `server/` folder and install the required dependencies:

```bash
cd server

pip install -r requirements.txt

```

### Running the Project

1. Start the backend server:

```bash
cd server

main.py

```


2. In a separate terminal, start the frontend development server:
npm run dev
```bash
cd client

npm install

npm run dev
```

3. Open your web browser and navigate to `http://localhost:3000` to access the Intelligent Parking Management System.

## Contributing

Contributions to this project are welcome. If you encounter any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Learning During Project Work

- **Computer Vision and Image Processing with OpenCV**
- **Real-time Data Processing and Synchronization with Firebase**
- **Front-end Web Development with Next.js and React**
- **System Integration and Architecture Design**
- **Problem-Solving and Optimization Skills**

The project provided hands-on learning opportunities in computer vision, real-time data processing, web development, system integration, and problem-solving, allowing you to develop practical skills and gain a deeper understanding of the technologies and techniques involved.