Project Title
Civic Sense Reporting and Resolving System
Short Description
A smart web-based civic issue reporting and management system that allows citizens to report problems such as potholes, garbage, water leakage, drainage issues, and broken streetlights. The system uses GenAI for automatic issue analysis and XAI for providing understandable explanations of AI decisions.

Key Features
- 👤 User Authentication – Secure registration and login using JWT.
- 📝 Civic Issue Reporting – Users can report civic problems with descriptions and images.
- 📍 Location Tagging – Automatically captures the geographical location of reported issues.
- 🎤 Voice-Based Reporting – Users can provide issue descriptions using voice input.
- 🤖 Generative AI Analysis – Automatically analyzes complaints and generates summary, category, and priority.
- 🔍 Explainable AI (XAI) – Provides a human-readable explanation for the AI's classification.
- 🏷️ Automatic Categorization – Classifies issues into Road, Garbage, Lighting, Water, Drainage, or Other.
- 🚨 Priority Detection – Assigns Low, Medium, or High priority based on the complaint.
- 🏢 Department Routing – Routes complaints to the appropriate department based on issue category.
- 🗺️ Interactive Map – Displays reported issues using geographical markers.
- 📊 Admin Dashboard – Allows administrators to monitor and manage reported issues.
- 🔄 Issue Status Tracking – Tracks complaints through Pending → In Progress → Resolved.
- 🖼️ Image Upload – Supports uploading photographs of civic problems.
- 🔧 AI Fallback Mechanism – Uses keyword-based classification when the AI service is unavailable.
Technology Stack
Frontend
- React.js
- Vite
- Tailwind CSS
- React Router
- Leaflet
Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT
- Multer
AI
- OpenAI API
- GenAI
- Explainable AI
- Heuristic/keyword-based fallback
Objective
The main objective of this project is to provide a centralized and intelligent platform for reporting, analyzing, managing, and resolving civic issues efficiently while improving transparency through Explainable AI.

Future Scope
- 📷 Image-based automatic issue detection using computer vision
- 🧠 More advanced AI/ML classification
- 🔔 Real-time notifications
- 📱 Mobile application
- 📈 Advanced analytics and heatmaps
- 🏙️ Integration with municipal/government systems
- 🌐 Multilingual and regional-language support
