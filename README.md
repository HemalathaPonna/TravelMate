# Trippie - Trip Planner & Blog Creator

## 🌍 Overview
Trippie is a **Trip Planner & Blog Creator** designed to help travelers efficiently plan their trips by selecting cities, exploring places, scheduling visits, and even getting crowd insights. Additionally, it includes a blog generation feature that allows users to create travel blogs using AI.

## 🚀 Features
- **City Selection**: Users can choose a city they want to visit.
- **Attractions & Places**: Displays places of interest within the selected city.
- **Trip Scheduling**: Allows users to select places and time slots for their visit.
- **Crowd Insights**: Provides information on when the crowd will be low at a location.
- **Ticket Booking Redirection**: Redirects users to platforms where they can book tickets if necessary.
- **AI-Powered Blog Creator**: Automatically generates blog content based on user inputs.

## 🛠️ Installation
### 1. Clone the Repository
```sh
git clone https://github.com/pratap834/trippie.git
cd trippie
```

### 2. Install Backend Dependencies
```sh
cd backend
pip install -r requirements.txt
```

### 3. Install Frontend Dependencies
```sh
cd frontend
npm install
```

## ▶️ Usage
### Running the Backend
```sh
cd backend
uvicorn app:app --host 0.0.0.0 --port 8000
```
The backend will run on **http://localhost:8000**

### Running the Frontend
```sh
cd frontend
npm start
```
The frontend will run on **http://localhost:3000**

## 🔗 API Endpoints
- `POST /generate-blog`: Generates a travel blog based on user inputs.
- `GET /places?city=<city_name>`: Fetches places of interest for a selected city.
- `GET /crowd-info?place=<place_name>`: Provides crowd level insights.

## 📌 Notes
- The **backend (FastAPI) must be running on port 8000** to ensure frontend communication.
- The **frontend (React) runs on port 3000**.
- Ensure that **both ports match** in API calls for proper functioning.

## 📜 License
This project is open-source and available under the MIT License.

---

### 📧 Contact
For any issues or contributions, please create an **issue** or submit a **pull request** on the [GitHub repository](https://github.com/pratap834/trippie).

