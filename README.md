# Web App

A full-stack web application built with Node.js/Express backend and vanilla JavaScript frontend.

## Features

- ✨ Express.js backend API
- 🎨 Responsive HTML/CSS/JavaScript frontend
- 🔗 Frontend-backend communication with fetch API
- 📝 Contact form with backend submission
- 🚀 Ready to deploy

## Project Structure

```
web-app/
├── server.js           # Express server
├── package.json        # Dependencies
├── .env.example        # Environment variables template
├── .gitignore         # Git ignore file
└── public/
    ├── index.html     # Main HTML page
    ├── styles.css     # Styling
    └── script.js      # Frontend logic
```

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone https://github.com/welxer/web-app.git
cd web-app
```

2. Install dependencies:
```bash
npm install
```

3. Create a `.env` file from the template:
```bash
cp .env.example .env
```

4. Start the development server:
```bash
npm run dev
```

5. Open your browser and navigate to:
```
http://localhost:5000
```

## Available Scripts

- `npm start` - Start the production server
- `npm run dev` - Start the development server with nodemon
- `npm run build` - Build script placeholder
- `npm test` - Test script placeholder

## API Endpoints

### GET /api/hello
Returns a greeting message from the backend.

**Response:**
```json
{
  "message": "Hello from the backend!"
}
```

### GET /api/data
Returns sample data.

**Response:**
```json
{
  "data": [
    { "id": 1, "title": "Item 1", "description": "..." },
    ...
  ]
}
```

### POST /api/submit
Submit contact form data.

**Request Body:**
```json
{
  "name": "John Doe",
  "email": "john@example.com"
}
```

**Response:**
```json
{
  "success": true,
  "message": "Thank you, John Doe! We'll contact you at john@example.com"
}
```

## Features to Add

- [ ] Database integration (MongoDB/PostgreSQL)
- [ ] User authentication
- [ ] Error handling and validation
- [ ] Unit tests
- [ ] CI/CD pipeline with GitHub Actions
- [ ] Docker containerization
- [ ] Deployment configuration

## Technologies Used

- **Backend:** Node.js, Express.js
- **Frontend:** HTML5, CSS3, Vanilla JavaScript
- **Middleware:** CORS, body-parser

## License

ISC

## Author

welxer

---

Happy coding! 🚀
