Crypto Mining Game - Professional Telegram WebApp
A professional crypto mining game built as a Telegram WebApp with modern technologies and production-ready features.

🎮 Features
Interactive Gameplay: Tap-to-earn mechanics with automatic mining
Upgrade System: 50+ upgrades with dynamic pricing and effects
Admin Dashboard: Complete admin panel with user management and analytics
Telegram Integration: Native Telegram WebApp with user authentication
Mission System: Daily tasks, achievements, and reward mechanisms
Real-time Progress: Automatic progress saving and offline earnings calculation
🚀 Tech Stack
Frontend
React 18 + TypeScript
Tailwind CSS + Framer Motion
Vite + Modern Build Tools
TanStack Query for state management
Backend
Node.js + Express
PostgreSQL + Drizzle ORM
Telegram Bot API
Session-based authentication
📁 Project Structure
├── client/                 # Frontend React application
│   ├── src/
│   │   ├── pages/         # Application pages
│   │   ├── components/    # Reusable components
│   │   └── lib/          # Utilities and configurations
├── server/                # Backend Express application
│   ├── admin.ts          # Admin functionality
│   ├── db.ts            # Database configuration
│   ├── index.ts         # Main server entry point
│   ├── routes.ts        # API routes
│   └── telegram-bot.ts  # Telegram bot integration
├── shared/               # Shared types and schemas
│   └── schema.ts        # Database schema and types
└── public/              # Static assets
🛠️ Installation
Clone the repository

Install dependencies:

npm install
Set up environment variables:

# Create .env file with:
DATABASE_URL=your_postgresql_url
SESSION_SECRET=your_session_secret
TELEGRAM_BOT_TOKEN=your_bot_token  # Optional
Initialize the database:

npm run db:push
Start the development server:

npm run dev
🎯 Admin Access
Default admin credentials:

Username: admin
Password: admin123
Access the admin panel at: /admin-{generated-suffix}

🌐 Production Deployment
The application is ready for production deployment on platforms like:

Replit
Vercel
Railway
Heroku
Ensure you have:

PostgreSQL database configured
Environment variables set
Static files served properly
📱 Telegram Bot Setup (Optional)
Create a bot via @BotFather
Get your bot token
Add the token to your environment variables
The bot will automatically start when the server runs
🔧 Development Commands
npm run dev         # Start development server
npm run build       # Build for production
npm run db:push     # Push database schema changes
npm run db:studio   # Open database studio (if available)
📊 Database Schema
The application uses a comprehensive schema including:

Users management with progress tracking
Upgrade system with definitions and user purchases
Admin functionality with activity logging
Mission system with daily tasks
Referral system for user growth
🎨 Customization
The application is highly customizable:

Modify upgrade definitions in shared/schema.ts
Customize game mechanics in the React components
Add new missions and rewards
Extend admin functionality
🔒 Security Features
Session-based authentication
Password hashing with bcrypt
Admin activity logging
Input validation with Zod schemas
SQL injection protection with Drizzle ORM
📄 License
This project is available for purchase. Contact the developer for licensing and commercial use.

💬 Support
For technical support, custom development, or licensing inquiries, contact the developer via Telegram.

