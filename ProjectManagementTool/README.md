
# PlanPoint - Project Management Web App

## Local Setup Instructions
1. Clone the repository:
   ```bash
   git clone <repository-link>

2. Navigate to the project directory:

   ```bash
   cd PlanPoint
   ```
3. Install dependencies:

   ```bash
   npm install
   ```
4. Start the development server:

   ```bash
   npm start
   ```
5. Open [http://localhost:3000](http://localhost:3000) in your browser to view the app.

---

## Architecture Diagram

```
[Frontend - React + Syncfusion] <---> [Backend - Node.js + Express (planned)]  
                  |  
           [Future Pub/Sub with Kafka]  
                  |  
           [AI Integration with OpenAI API]  
                  |  
             [Deployment on Vercel]
```

*Note: Backend is planned and will handle APIs and business logic, with pub/sub architecture via Kafka to improve scalability and real-time features.*

---

## Summary of Technologies and AI Tools Used

* **Frontend:** React.js, Syncfusion component library for UI, charts, Kanban boards, and calendar integrations.
* **Backend (Planned):** Node.js with Express framework to serve REST APIs.
* **AI Tools (Future):** Integration with OpenAI API for intelligent task automation, suggestions, and insights.
* **Architecture (Future):** Pub/Sub model using Kafka for efficient asynchronous messaging and event-driven workflows.
* **Deployment:** Frontend currently deployed on Vercel.

---

## Known Limitations and Assumptions

* Currently, only the frontend portion is implemented, focusing on user interface and interaction using React and Syncfusion.
* Backend API and real-time features are under development.
* AI capabilities and Kafka-based pub/sub architecture are planned enhancements, reflecting scalable and intelligent future expansions.
* Assumes users have Node.js and npm installed for local development.
* Deployment is configured for frontend; backend deployment and integration will follow in subsequent updates.

---

*This README reflects my understanding of modern web development, event-driven architectures, and AI integration strategies to build scalable and intelligent project management solutions.*


