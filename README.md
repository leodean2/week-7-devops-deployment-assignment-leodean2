# MERN Stack Deployment Project

## Application URLs
- Frontend: [https://your-app.vercel.app](mern-stack-frontend-vqmv.vercel.app)
- Backend: [https://your-api.render.com](https://your-app-backend-wjq4.onrender.com)

## Deployment Process
1. Backend deployed to Render
2. Frontend deployed to Vercel
3. CI/CD pipelines configured with GitHub Actions

## Screenshots
![CI Pipeline](screenshots/ci-pipeline.png)
![CD Pipeline](screenshots/cd-pipeline.png)

## Environment Variables
### Backend
- `MONGODB_URI`: MongoDB Atlas connection string
- `JWT_SECRET`: Secret for JWT token generation

### Frontend
- `REACT_APP_API_BASE_URL`: Base URL for API requests
