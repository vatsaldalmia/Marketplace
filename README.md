# Marketplace

A full-stack marketplace platform that allows users to browse, list, and manage products through a modern web interface. The application follows a scalable client-server architecture with a React frontend and Node.js backend.

## Features

- User authentication and authorization
- Product listing and management
- Responsive user interface
- RESTful API architecture
- Secure backend middleware
- Modular MVC backend structure
- Modern React + TypeScript frontend
- Tailwind CSS styling

## Tech Stack

### Frontend
- React
- TypeScript
- Vite
- Tailwind CSS

### Backend
- Node.js
- Express.js
- MongoDB (if applicable)
- JWT Authentication (if applicable)

## Project Structure

```text
Marketplace/
│
├── Backend/
│   ├── config/
│   ├── controllers/
│   ├── middlewares/
│   ├── models/
│   ├── routes/
│   ├── utils/
│   ├── server.js
│   └── package.json
│
├── Frontend/
│   ├── public/
│   ├── src/
│   ├── vite.config.ts
│   ├── tailwind.config.js
│   └── package.json
│
└── .gitignore
```

## Installation

### Clone the Repository

```bash
git clone https://github.com/vatsaldalmia/Marketplace.git
cd Marketplace
```

### Backend Setup

```bash
cd Backend
npm install
```

Create a `.env` file inside the Backend directory:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

Start the backend server:

```bash
npm start
```

or

```bash
node server.js
```

### Frontend Setup

```bash
cd Frontend
npm install
npm run dev
```

The frontend will typically run on:

```text
http://localhost:5173
```

## API Architecture

The backend follows the MVC architecture:

- **Models** → Database schemas and business data
- **Controllers** → Request handling logic
- **Routes** → API endpoint definitions
- **Middlewares** → Authentication and request validation
- **Utils** → Helper functions and reusable logic

## Development Workflow

```bash
# Backend
cd Backend
npm install
npm start

# Frontend
cd Frontend
npm install
npm run dev
```

## Future Improvements

- Product search and filtering
- Wishlist functionality
- Payment gateway integration
- Order tracking
- Admin dashboard
- Real-time notifications
- Product reviews and ratings

## Contributing

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature/new-feature
```

3. Commit your changes

```bash
git commit -m "Add new feature"
```

4. Push to your branch

```bash
git push origin feature/new-feature
```

5. Open a Pull Request

## License

This project is licensed under the MIT License.

## Author

**Vatsal Dalmia**

GitHub: https://github.com/vatsaldalmia
