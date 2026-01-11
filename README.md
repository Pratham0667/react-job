# React Jobs

A modern job listing application built with React and Vite that allows users to browse, search, add, edit, and manage job postings with a beautiful UI powered by Tailwind CSS.

## 🚀 Features

- **Browse Jobs**: View a comprehensive list of available job positions
- **Job Details**: View detailed information about each job posting
- **Add Jobs**: Create new job listings with a user-friendly form
- **Edit Jobs**: Update existing job postings
- **Delete Jobs**: Remove job listings
- **Responsive Design**: Fully responsive UI built with Tailwind CSS
- **Loading States**: Smooth loading animations with React Spinners
- **Toast Notifications**: User feedback with React Toastify
- **Fast Development**: Powered by Vite for lightning-fast HMR (Hot Module Replacement)
- **Mock API**: JSON Server for development and testing

## 🛠️ Technologies Used

- **React 19** - Latest version of React for building user interfaces
- **Vite** - Next-generation frontend build tool for fast development
- **React Router DOM** - Client-side routing and navigation
- **Tailwind CSS** - Utility-first CSS framework for modern styling
- **React Icons** - Popular icon library
- **React Toastify** - Beautiful toast notifications
- **React Spinners** - Loading spinners and animations
- **JSON Server** - Mock REST API for development

## 📋 Prerequisites

Before running this project, make sure you have:

- **Node.js** (v16 or higher)
- **npm** or **yarn** package manager

## 🔧 Installation

1. Clone the repository:
```bash
git clone https://github.com/Pratham0667/react-job.git
```

2. Navigate to the project directory:
```bash
cd react-job/react-jobs
```

3. Install dependencies:
```bash
npm install
```

## 🚀 Running the Application

### Development Mode

You need to run **two terminals** simultaneously:

**Terminal 1** - Start the JSON Server (Mock Backend):
```bash
npm run server
```
This will start the JSON Server on `http://localhost:8000`

**Terminal 2** - Start the Vite Development Server:
```bash
npm run dev
```
This will start the React app, usually on `http://localhost:5173`

The app will automatically open in your browser with hot module replacement enabled.

### Production Build

Create an optimized production build:
```bash
npm run build
```

Preview the production build:
```bash
npm run preview
```

### Linting

Run ESLint to check code quality:
```bash
npm run lint
```

## 📁 Project Structure

```
react-jobs/
├── public/              # Static assets
├── src/
│   ├── components/      # Reusable UI components
│   ├── pages/           # Page components
│   ├── layouts/         # Layout components
│   ├── jobs.json        # Mock job data for JSON Server
│   ├── App.jsx          # Main application component
│   ├── index.css        # Global styles with Tailwind
│   └── main.jsx         # Application entry point
├── .eslintrc.cjs        # ESLint configuration
├── tailwind.config.js   # Tailwind CSS configuration
├── postcss.config.js    # PostCSS configuration
├── vite.config.js       # Vite configuration
├── package.json
└── README.md
```

## 🎯 Available Scripts

| Command | Description |
|---------|-------------|
| `npm run dev` | Starts Vite development server with HMR |
| `npm run build` | Creates production build in `dist/` folder |
| `npm run preview` | Preview production build locally |
| `npm run server` | Starts JSON Server on port 8000 |
| `npm run lint` | Runs ESLint to check code quality |

## 🌟 Key Features

### React Router
- Client-side routing for seamless navigation
- Dynamic routes for individual job pages
- Nested routes and layouts

### Tailwind CSS
- Utility-first CSS for rapid UI development
- Fully responsive design
- Custom theme configuration

### JSON Server
- RESTful API endpoints for CRUD operations
- Auto-generated routes from `jobs.json`
- Perfect for development and prototyping

### React Toastify
- Success/error notifications
- Customizable toast messages
- Beautiful animations

## 🔌 API Endpoints (JSON Server)

The JSON Server provides the following endpoints:

- `GET /jobs` - Get all jobs
- `GET /jobs/:id` - Get a single job
- `POST /jobs` - Create a new job
- `PUT /jobs/:id` - Update a job
- `DELETE /jobs/:id` - Delete a job

## 🎨 Styling

This project uses **Tailwind CSS v3** with the following features:
- Utility-first approach
- Custom color schemes
- Responsive breakpoints
- Dark mode support (if implemented)

## 🔮 Future Enhancements

- [ ] User authentication and authorization
- [ ] Search and filter functionality
- [ ] Job categories and tags
- [ ] Save favorite jobs
- [ ] Job application tracking
- [ ] Email notifications
- [ ] Employer dashboard
- [ ] Integration with real job APIs
- [ ] Advanced filtering and sorting
- [ ] Pagination for large datasets

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/YourFeature`)
5. Open a Pull Request



## 👤 Author

**Pratham**

- GitHub: [@Pratham0667](https://github.com/Pratham0667)

## 🙏 Acknowledgments

- React team for React 19
- Vite team for the amazing build tool
- Tailwind CSS for the utility-first framework
- All open-source contributors

## 📧 Support

For questions or issues, please open an issue in the [GitHub repository](https://github.com/Pratham0667/react-job/issues).

---

**Made with ❤️ using React & Vite**
