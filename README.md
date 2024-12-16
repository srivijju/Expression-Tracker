# Facial Expression Tracker for Dyslexic Kids  

## Project Overview  

This project is an advanced tool designed to integrate facial expression analysis into educational games tailored for dyslexic children. It leverages real-time facial data and gameplay interactions, processes this information using a Vision Transformer (ViT) model for emotion recognition, and organizes the analysis in a MongoDB database. The results are accessible via an admin dashboard, enabling therapists and caregivers to enhance the child's learning experience effectively.  

## Features  

### **Role-Based Login**  
- **Admin**: Access session-wise emotional analysis and insights through a dashboard.  
- **Kid**: Engage in educational gameplay with automated background image capture for analysis.  

### **Image Capture**  
- Automatic screenshots and webcam captures are taken during gameplay for detailed analysis.  

### **Emotion Recognition**  
- Real-time analysis of facial expressions using a ViT-based deep learning model hosted on Hugging Face.  

### **Session Management**  
- Session-wise data organization to track and analyze each game individually.  

### **Data Storage**  
- Images and analytical results are stored locally and in a MongoDB database for scalability and accessibility.  

### **Admin Dashboard**  
- A React-powered interface displaying emotional insights, session histories, and overall trends for better decision-making.  

## Tech Stack  

### **Frontend**  
- **React.js**: For building dynamic user interfaces.  
- **React Router**: Enables role-based navigation and routing.  
- **Axios**: Simplifies API communication.  

### **Backend**  
- **Node.js**: Handles server-side logic.  
- **Express.js**: Develops RESTful APIs for seamless data transfer.  
- **Multer**: Manages file uploads, particularly images.  

### **Database**  
- **MongoDB**: Stores user profiles, session details, and analysis results efficiently.  

### **AI Model**  
- **Vision Transformer (ViT)**: A pre-trained model hosted on Hugging Face for advanced facial expression recognition.  

## Project Structure  

```
Facial-Expression-Tracker/
├── client/               # React frontend  
├── server/               # Express backend  
├── models/               # Deep learning models and utilities  
├── routes/               # API routes for data handling  
├── public/               # Static files and assets  
├── uploads/              # Captured images and screenshots  
└── README.md             # Documentation  
```  

## Installation  

1. Clone the repository:  
   ```bash  
   git clone https://github.com/your-repo-name.git  
   cd Facial-Expression-Tracker  
   ```  

2. Install dependencies for both frontend and backend:  
   ```bash  
   cd client  
   npm install  
   cd ../server  
   npm install  
   ```  

3. Configure environment variables:  
   - Create `.env` files in both `client` and `server` directories.  
   - Add necessary keys, such as MongoDB URI, API keys, and server ports.  

4. Start the development servers:  
   - Backend:  
     ```bash  
     cd server  
     npm start  
     ```  
   - Frontend:  
     ```bash  
     cd client  
     npm start  
     ```  

## Future Enhancements  

- Real-time notifications for therapists during gameplay sessions.  
- Adaptive gameplay tailored to the child's emotional feedback.  
- Integration of additional deep learning models for more comprehensive insights.  

## License  

This project is licensed under the MIT License.  

---  

Let me know if you’d like to customize any specific sections further!
