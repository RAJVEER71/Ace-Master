I developed a software for users and administrators to enhance exam preparation across multiple courses. It offers a structured and interactive environment for students to take assessments and track their progress, while administrators can manage courses, quizzes, and user accounts.

🡺 Key Features:
🎯 JWT-based authentication with role-based access control (Admin/Student).
📊 Real-time performance analytics using Chart.js
📱 Mobile-responsive Vue.js frontend
⏰ Celery-powered daily reminders & monthly reports + async jobs for CSV export.
🔒 Protected API endpoints with proper authorization
🛑 Deadline-based availability control +Single-attempt restriction capability. 
💳 Secure payment processing for premium quizzes +Transaction history tracking
✨ Responsive design using Tailwind CSS + Intuitive navigation with Breadcrumbs

🡺 Designed scalable DB schema with 10+ interconnected tables.
🡺 Implemented CSV export for quiz results and transactions.
🡺 Reduced server load by using Redis caching.
🡺 Created 25+ RESTful API endpoints with Flask-RESTful. 
🡺 Implented Email rate limiting so that the emails don't cross the free tier.
