Facial Expression Tracker for Dyslexic Kids
Project Overview
This project is an innovative tool that integrates facial expression analysis into educational games for dyslexic children. It captures real-time facial data and gameplay interactions, processes this data through a Vision Transformer (ViT) model for emotion recognition, and stores the analysis in a MongoDB database. The results are displayed on an admin dashboard for therapists or caregivers to assess and improve the child’s learning experience.

Features
Role-Based Login:
Admin: Access the dashboard for session-wise analysis. Kid: Play the educational game with background image capture for analysis.

Image Capture:
Automatic screenshots and webcam images captured during gameplay.

Emotion Recognition:
Analyzes facial expressions using a ViT-based deep learning model hosted on Hugging Face.

Session Management:
Session-wise organization of data for each game.

Data Storage:
Images and analysis results are stored locally and in a MongoDB database.

Admin Dashboard:
View emotional insights, session histories, and overall analysis trends.

Tech Stack
Frontend:
React.js: Dynamic user interfaces. React Router: Role-based routing for navigation. Axios: API communication.

Backend:
Node.js: Server-side logic. Express.js: RESTful API development. Multer: File handling for image uploads.

Database:
MongoDB: Stores user profiles, session data, and analysis results.

AI Model:
Vision Transformer (ViT): Facial expression recognition using a pre-trained model hosted on Hugging Face.

Future Enhancements
Real-time notifications for therapists during gameplay. Adaptive gameplay levels based on live emotional feedback. Integration with additional deep learning models for richer insights.
