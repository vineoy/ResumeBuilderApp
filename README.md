
# AI Resume Generator

## Overview

The AI Resume Generator is a web application that helps users create professional resumes with the power of AI. It leverages Spring Boot for the backend, integrates with Ollama (local AI model) for resume generation, stores data in JSON files, and provides a sleek and interactive frontend built using React.js.


## Features

1. AI-Powered Resume Generation: Uses Ollama's local AI model to generate tailored resumes based on user input.

2. JSON-Based Storage: Simple and lightweight storage using JSON files.

3. Responsive Frontend: Built with React.js and styled with Tailwind CSS and DaisyUI for a modern UI.

4. Downloadable Resumes: Export resumes in PDF format.

5. Real-time Editing: Users can preview and edit their resume before downloading.
## Tech Stack

### Backend (Spring Boot)

#### Spring Boot (Java) - Handles API requests and business logic.

#### Ollama Local AI Model - Generates resume content based on user input.

#### JSON File Storage - Simple, lightweight, and easy-to-manage data storage.

#### Spring Web - For REST API development.

### Frontend (React.js)

#### React.js - Provides a dynamic and interactive user experience.

#### Tailwind CSS + DaisyUI - For modern, responsive styling.

#### React Router - Handles client-side navigation.

### Other Tools

#### PDF.js - Converts resume templates into downloadable PDFs.

#### Axios - Handles API calls between the frontend and backend.
## API Endpoints

#### Resume API (Spring Boot)
```http
  GET /api/items
```

| Method | Endpoints     | Description                |
| :-------- | :------- | :------------------------- |
| `GET` | `/api/resumes` | Fetch all saved resumes |
| `POST` | `/api/resumes/generate` | Generate a new resume using AI |
| `GET` | `/api/resumes/{id}` | Get a specific resume by ID |
| `DELETE` | `/api/resumes/{id}` | Delete a resume |



## Installation

### Clone the repository:
```bash
  git clone https://github.com/yourusername/ai-resume-generator.git
cd ai-resume-generator/backend
```

```bash
  mvn clean install
```
### Run the Spring Boot application:
```bash
  mvn spring-boot:run
```
## Frontend Setup (React.js)

### Navigate to the frontend directory:
```bash
  cd ../frontend
```
```bash
  npm install
```
### Start the React application:
```bash
  npm run dev
```

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)

[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)

[![AGPL License](https://img.shields.io/badge/license-AGPL-blue.svg)](http://www.gnu.org/licenses/agpl-3.0)

