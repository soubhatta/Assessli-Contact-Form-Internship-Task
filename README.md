# Assessli React Internship Assignment

This project is a React assignment for Assessli. It aims to create a dynamic and visually appealing contact page using React that can be easily integrated into your website to allow visitors to send you messages. The contact page includes a form with fields for name, email, phone, and message. The project integrates with Google Sheets, and the form data is being submitted to the where the proper working of the form can be checked.

## Deployed Link - [https://data-form-google-sheet.vercel.app/](https://assessli-contact-form-soumalya.vercel.app/)
## Google Sheet Link - [https://docs.google.com/spreadsheets/d/1VapHovBWX465rAr-R6IlcHH44kuHUn5Zs_ag12BW_o0/edit#gid=0](https://docs.google.com/spreadsheets/d/1S10TgX1J6QuH6DDKoUG4G-3QX3hgvrz65J6wQ_neW0w/edit?usp=sharing)

# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

### Once We Clone the Repository, we have to run the following commands ->

### Available Scripts

In the project directory, you can run:

#### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

#### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

#### `npm run build` fails to minify

This function creates a compact folders of all the essential part of the application so that it can be deployed. 


## Steps to integrate Google Sheets with React.js using Google App Scripts
Integrating Google Sheets with a React.js application using Google Apps Script involves creating an Apps Script project to act as an intermediary between our React.js front end and the Google Sheets backend. This allows our React.js application to send data to Google Sheets for storage and retrieval. Here are the steps to achieve this integration:

1. Create a new Google Sheets document or open an existing one.
2. Set up the sheet with the necessary columns to store your data.
3. Go to the Google Apps Script website.
4. Create a new project and give it a name.
5. Write the Apps Script code to handle incoming HTTP requests and interact with Google Sheets.
6. Deploy your Apps Script project as a web app to obtain a URL that your React.js application can send requests to.
7. Choose "Web App" as the deployment type and configure settings like access permissions.
8. Deploy the web app and note down the URL generated.
9. Create a new React.js application or use an existing one and fetch the api from Google Sheet backend.
10. Now after fixing the CORS issue, we can create the frontend and retrieve the data written in the app directly from google sheet.


## Features


## Setup Instructions

1. Clone the repository: `git clone https://github.com/soubhatta/Assessli-Contact-Form-Internship-Task.git`
2. Install dependencies: `npm install`
3. Run the project: `npm run dev`
4. Access the server at [http://localhost:5173](http://localhost:5173)

## Google Sheets Integration

The project integrates with Google Sheets, and the form data is being submitted to [[https://docs.google.com/spreadsheets/d/1S10TgX1J6QuH6DDKoUG4G-3QX3hgvrz65J6wQ_neW0w/edit?usp=sharing](https://docs.google.com/spreadsheets/d/1VapHovBWX465rAr-R6IlcHH44kuHUn5Zs_ag12BW_o0/edit#gid=0)], where you can check the data submitted to the form.

## Additional Information

- The project uses React for frontend development.
- For any issues or suggestions, please contact me.
Email: [soumalyabhatta19@gmail.com](mailto:soumalyabhatta19@gmail.com)

## React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
