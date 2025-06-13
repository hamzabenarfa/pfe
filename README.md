# 📋 Project-Planner

> A modern, full-stack project management application built with NestJS and Next.js

[![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat&logo=nestjs&logoColor=white)](https://nestjs.com/)
[![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=next.js&logoColor=white)](https://nextjs.org/)
[![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat&logo=prisma&logoColor=white)](https://www.prisma.io/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)

## ✨ Overview

Project-Planner is a comprehensive project management solution that empowers teams to collaborate effectively, track progress, and deliver projects on time. Built with modern technologies and best practices, it offers an intuitive interface for managing projects, teams, and workflows.

## 🚀 Features

### 🔐 Authentication & Security
- Secure user registration and login
- JWT-based authentication
- Role-based access control
- Password encryption and validation

### 📊 Project Management
- **Create & Organize**: Set up projects with detailed descriptions, deadlines, and priorities
- **Progress Tracking**: Monitor project status and completion rates
- **Task Management**: Break down projects into manageable tasks
- **Timeline Views**: Visualize project schedules and milestones

### 👥 Team Collaboration
- **Team Creation**: Build and manage project teams
- **Member Assignment**: Assign team members to specific projects and tasks
- **Role Management**: Define roles and permissions for team members
- **Communication**: Built-in collaboration tools for team coordination

### 📱 User Experience
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Real-time Updates**: Live synchronization across all devices
- **Intuitive UI**: Clean, modern interface built with Tailwind CSS
- **Dark/Light Mode**: Customizable theme preferences

## 🛠️ Technology Stack

### Backend Architecture
- **[NestJS](https://nestjs.com/)** - Scalable Node.js framework with TypeScript
- **[Prisma](https://www.prisma.io/)** - Next-generation ORM for database management
- **TypeScript** - Type-safe development
- **PostgreSQL** - Robust relational database
- **JWT** - Secure authentication tokens

### Frontend Stack
- **[Next.js 14+](https://nextjs.org/)** - React framework with App Router
- **TypeScript** - Enhanced developer experience with type safety
- **[Tailwind CSS](https://tailwindcss.com/)** - Utility-first CSS framework
- **React Hooks** - Modern state management
- **Responsive Design** - Mobile-first approach

## 📦 Installation

### Prerequisites

Ensure you have the following installed on your system:

- **Node.js** v18.17+ ([Download](https://nodejs.org/))
- **npm** v9+ or **pnpm** v8+ ([Install pnpm](https://pnpm.io/installation))
- **PostgreSQL** v13+ ([Download](https://www.postgresql.org/download/))
- **Git** ([Download](https://git-scm.com/downloads))

### Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/hamzabenarfa/Project-Planner.git
   cd Project-Planner
   ```

2. **Install dependencies**
   ```bash
   # Backend dependencies
   cd backend
   pnpm install
   
   # Frontend dependencies
   cd ../frontend
   pnpm install
   ```

3. **Environment Configuration**
   
   Create `.env` files in both backend and frontend directories:
   
   **Backend (`backend/.env`)**:
   ```env
   DATABASE_URL="postgresql://username:password@localhost:5432/project_planner"
   JWT_SECRET="your-super-secret-jwt-key-here"
   JWT_EXPIRES_IN="7d"
   PORT=3001
   ```
   
   **Frontend (`frontend/.env.local`)**:
   ```env
   NEXT_PUBLIC_API_URL=http://localhost:3001
   NEXTAUTH_SECRET="your-nextauth-secret-here"
   NEXTAUTH_URL=http://localhost:3000
   ```

4. **Database Setup**
   ```bash
   cd backend
   
   # Generate Prisma client
   npx prisma generate
   
   # Run database migrations
   npx prisma migrate dev --name init
   
   # (Optional) Seed the database with sample data
   npx prisma db seed
   ```

5. **Start the Development Servers**
   
   Open two terminal windows:
   
   **Terminal 1 - Backend**:
   ```bash
   cd backend
   pnpm run start:dev
   ```
   
   **Terminal 2 - Frontend**:
   ```bash
   cd frontend
   pnpm run dev
   ```

6. **Access the Application**
   - Frontend: [http://localhost:3000](http://localhost:3000)
   - Backend API: [http://localhost:3001](http://localhost:3001)


## 🎯 Usage Guide

### Getting Started

1. **Register an Account**: Create your user account or log in if you already have one
2. **Create Your First Project**: Set up a new project with description, timeline, and goals
3. **Build Your Team**: Invite team members and assign roles
4. **Plan & Execute**: Break down your project into tasks and start collaborating

### Key Workflows

**Project Creation**:
- Navigate to "Projects" → "New Project"
- Fill in project details, set deadlines, and define objectives
- Assign team members and set permissions

**Team Management**:
- Go to "Teams" → "Create Team"
- Add members by email invitation
- Define roles and access levels

**Task Tracking**:
- Within each project, create tasks and subtasks
- Set priorities, due dates, and assignees
- Track progress with status updates



## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Built with ❤️ by [hamzabenarfa](https://github.com/hamzabenarfa)
- Inspired by modern project management tools
- Thanks to all contributors and the open-source community

## 📞 Support

Need help? Have questions?

- 📧 **Email**: [hamzabenarfa4@gmail.com](mailto:hamzabenarfa4@gmail.com)
- 🐛 **Issues**: [GitHub Issues](https://github.com/hamzabenarfa/Project-Planner/issues)
- 💬 **Discussions**: [GitHub Discussions](https://github.com/hamzabenarfa/Project-Planner/discussions)

---
