# Carpool App

## Overview
The **Carpool App** connects drivers with passengers traveling on similar routes, promoting cost-effective and environmentally friendly commuting. This application reduces traffic congestion and encourages community-based collaboration.

---

## Prerequisites
Before extracting and running the project, ensure the following are installed:

### Mobile Development Tools:
- A text editor or IDE (e.g., VS Code, Android Studio).
- **Node.js** (for React Native development).
- **npm** or **yarn** (package managers).
- **Android/iOS Emulator** or a physical device.

### Web Development Tools:
- A web browser (e.g., Chrome, Firefox).
- Node.js and npm.

### Backend Tools:
- **Node.js** (if using Express.js) or **Python** (if using Django/Flask).

### Database:
- MongoDB, MySQL, or PostgreSQL.

### Version Control:
- Git (for cloning the repository).

---

## Project Setup

### 1. Extract the Project

#### From ZIP File:
1. Download the project ZIP file.
2. Extract it to a desired folder on your system.

#### From Git Repository:
1. Clone the repository using the terminal:
   ```bash
   git clone <repository_url>
   cd <project_directory>
   ```

---

### 2. Backend Setup

#### Install Dependencies
1. Navigate to the backend directory:
   ```bash
   cd backend
   ```
2. Install required packages:
   - **For Node.js**:
     ```bash
     npm install
     ```
   - **For Python**:
     ```bash
     pip install -r requirements.txt
     ```

#### Configure the Database
1. Create a database using your preferred management tool.
2. Update database credentials in the configuration file:
   - **Node.js**: Update `.env` or `config.js`.
   - **Django**: Update `settings.py`.

#### Run Backend Server
- Start the backend server:
  - **Node.js**:
    ```bash
    npm start
    ```
  - **Django**:
    ```bash
    python manage.py runserver
    ```

---

### 3. Frontend Setup (Web)

#### Install Dependencies
1. Navigate to the web frontend directory:
   ```bash
   cd frontend
   ```
2. Install required packages:
   ```bash
   npm install
   ```

#### Run Web Frontend Server
- Start the development server:
  ```bash
  npm start
  ```
- Open the app in your browser at:
  ```
  http://localhost:3000
  ```

---

### 4. Mobile App Setup

#### Install Dependencies
1. Navigate to the mobile app directory:
   ```bash
   cd mobile
   ```
2. Install required packages:
   ```bash
   npm install
   ```

#### Run Mobile App
1. Start the development server:
   ```bash
   npm start
   ```
2. Use the Expo app (for React Native) to scan the QR code or launch an emulator for testing.

---

### 5. Database Setup

#### Apply Migrations
- Apply migrations to set up database tables:
  - **Django**:
    ```bash
    python manage.py makemigrations
    python manage.py migrate
    ```
  - **Node.js (Sequelize)**:
    ```bash
    npx sequelize-cli db:migrate
    ```

#### Seed Initial Data (Optional)
- **Django**:
  ```bash
  python manage.py loaddata <data_file>
  ```
- **Node.js (Sequelize)**:
  ```bash
  npx sequelize-cli db:seed:all
  ```

---

### 6. Testing
- **Frontend Testing**:
  Verify navigation and usability features (e.g., ride creation, ride search).
- **API Testing**:
  Use tools like **Postman** or **Insomnia** to test endpoints.

---

### 7. Deployment

#### Frontend Deployment:
- Deploy the web app using platforms like **Netlify** or **Vercel**.

#### Mobile App Deployment:
- Publish the mobile app on app stores (Google Play Store, Apple App Store).

#### Backend Deployment:
- Host the backend server on **AWS**, **Heroku**, or **DigitalOcean**.

#### Database Hosting:
- Use cloud-hosted databases like **MongoDB Atlas**, **AWS RDS**, or **Google Cloud SQL**.

---

## Notes
- Ensure environment variables (API keys, database credentials) are properly configured in the `.env` file before starting the project.
- Regularly check logs for errors and resolve issues promptly.

---

## Contact
For questions or support, contact the development team.
