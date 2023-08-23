Train Schedule Web App - README
Overview
Welcome to the Train Schedule Web App! This application provides real-time train schedules for John Doe Railways. It's a responsive React-based frontend application that displays train information, including seat availability, prices, and delays. The app consists of two main pages: one for displaying all trains and another for displaying details of a single train. The application is built using React and utilizes Material UI for styling.

Features
Real-time train schedules for all trains, including seat availability and prices.
No user registration required to view train schedules.
Two train coach types: Sleeper and AC, with prices and seat availability.
Trains departing within the next 30 minutes are excluded.
Trains are sorted based on price, ticket availability, and departure time (considering delays).
Prominent display of train delays, expensive and cheap trains, seat availability, and coach class.
Setup and Running the Application
Clone this repository: git clone [repository URL]
Navigate to the project directory: cd train-schedule-app
Install dependencies: npm install
Run the application: npm run dev
The application will be accessible at http://localhost:3000.

Authentication and API Usage
To access the John Doe Railways APIs, an authentication token is required. This token is obtained using your company's registered roll number and access code provided via email/message.
API calls are chargeable, so the app is designed to minimize the number of calls while providing timely responses.
Evolution of Train Data
The application is built to handle evolving train data. As the train schedules, prices, and availability change based on market conditions, the app will still display up-to-date information by fetching the latest data from the John Doe Railways APIs.

Conclusion
The Train Schedule Web App provides users with real-time train schedules, prices, and seat availability for John Doe Railways. It's a responsive and user-friendly application built using React and Material UI. By following a comprehensive testing process, I've ensured that the app delivers accurate information, excellent performance, and a seamless user experience.
