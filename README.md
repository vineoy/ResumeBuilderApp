AI Resume Generator

Overview

The AI Resume Generator is a web application that helps users create professional resumes with the power of AI. It leverages Spring Boot for the backend, integrates with Ollama (local AI model) for resume generation, stores data in JSON files, and provides a sleek and interactive frontend built using React.js.

Features

AI-Powered Resume Generation: Uses Ollama's local AI model to generate tailored resumes based on user input.

Multiple Resume Templates: Users can choose from various professionally designed resume templates.

JSON-Based Storage: Simple and lightweight storage using JSON files.

Responsive Frontend: Built with React.js and styled with Tailwind CSS and DaisyUI for a modern UI.

Downloadable Resumes: Export resumes in PDF format.

Real-time Editing: Users can preview and edit their resume before downloading.

Tech Stack

Backend (Spring Boot)

Spring Boot (Java) - Handles API requests and business logic.

Ollama Local AI Model - Generates resume content based on user input.

JSON File Storage - Simple, lightweight, and easy-to-manage data storage.

Spring Web - For REST API development.

Frontend (React.js)

React.js - Provides a dynamic and interactive user experience.

Tailwind CSS + DaisyUI - For modern, responsive styling.

React Router - Handles client-side navigation.

Other Tools

PDF.js - Converts resume templates into downloadable PDFs.

Axios - Handles API calls between the frontend and backend.

Installation & Setup

Prerequisites

Ensure you have the following installed:

Java 17+ (for Spring Boot backend)

Node.js 16+ (for React frontend)

Ollama AI Model (installed locally)

Backend Setup (Spring Boot)

Clone the repository:

git clone https://github.com/yourusername/ai-resume-generator.git
cd ai-resume-generator/backend

Install dependencies and build the project:

mvn clean install

Run the Spring Boot application:

mvn spring-boot:run

Frontend Setup (React.js)

Navigate to the frontend directory:

cd ../frontend

Install dependencies:

npm install

Start the React application:

npm start

The frontend should be accessible at http://localhost:3000, and the backend API should be running at http://localhost:8080.

API Endpoints

Resume API (Spring Boot)

Method

Endpoint

Description

GET

/api/resumes

Fetch all saved resumes

POST

/api/resumes/generate

Generate a new resume using AI

GET

/api/resumes/{id}

Get a specific resume by ID

DELETE

/api/resumes/{id}

Delete a resume

Usage Guide

Visit the Application: Open http://localhost:3000 in your browser.

Enter Your Details: Fill out the form with your personal and professional details.

Generate Resume: Click on the 'Generate' button to let the AI create a resume.

Select a Template: Choose from multiple templates to format your resume.

Download as PDF: Once satisfied, download your resume as a PDF.







This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
