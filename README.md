 SensAI – AI-Powered Career Assistant
<p align="center"> <b>Build smarter job applications, prepare for interviews, and accelerate your career using AI.</b> </p> <p align="center"> <img src="https://img.shields.io/badge/Next.js-13+-black?style=for-the-badge&logo=next.js" /> <img src="https://img.shields.io/badge/React-JS-blue?style=for-the-badge&logo=react" /> <img src="https://img.shields.io/badge/Tailwind-CSS-38B2AC?style=for-the-badge&logo=tailwind-css" /> <img src="https://img.shields.io/badge/Prisma-ORM-2D3748?style=for-the-badge&logo=prisma" /> <img src="https://img.shields.io/badge/PostgreSQL-Database-blue?style=for-the-badge&logo=postgresql" /> <img src="https://img.shields.io/badge/Clerk-Auth-purple?style=for-the-badge" /> </p>


### What This Project Demonstrates  

- Real-world problem solving – Addresses practical challenges in job preparation such as generating personalized cover letters and improving interview readiness  
- Full-stack development expertise – Implements both frontend and backend using modern technologies like Next.js, APIs, and database integration  
- AI integration in a production use-case – Leverages AI to generate meaningful, user-specific content, showcasing practical application of AI in real products  
- Scalable and maintainable architecture – Structured codebase with reusable components, modular design, and efficient data handling  
- Modern UI/UX design principles – Clean, responsive, and user-friendly interface built with Tailwind CSS  
- Authentication and security handling – Secure user management using industry-standard authentication mechanisms (Clerk)  
### Tech Stack  

| Category     | Technologies Used                |
|--------------|---------------------------------|
| Frontend     | Next.js, React.js, Tailwind CSS |
| Backend      | Next.js API Routes              |
| Database     | PostgreSQL, Prisma ORM          |
| Authentication | Clerk                        |
| AI           | Gemini API / AI APIs            |

---

## Features  

- AI-powered cover letter generation tailored to job roles  
- User profile management for storing professional details  
- Interview preparation module with structured questions  
- Secure authentication and session management  
- Responsive and user-friendly interface  

## Project Structure  
<img width="536" height="726" alt="image" src="https://github.com/user-attachments/assets/2f2e72fe-419b-43ae-be24-6fc4a9a7d727" />

## Getting Started  

### Clone the repository  
git clone https://github.com/akanshalakhina/SENSAI.git
cd SENSAI

### Install dependencies  
pnpm install

### Configure environment variables  

Create a `.env` file in the root directory:
DATABASE_URL=your_database_url
NEXT_PUBLIC_CLERK_FRONTEND_API=your_clerk_key
CLERK_SECRET_KEY=your_clerk_secret

### Setup database  

pnpm prisma generate
pnpm prisma migrate dev

### Run the application  

pnpm dev
Open http://localhost:3000  

## Use Cases  

- Students preparing for placements  
- Job seekers creating personalized applications  
- Professionals improving interview performance  
- Developers exploring AI-based applications

  ## Demo  

Live Demo: https://senseai-nxj8iw3gz-akanshalakhinas-projects.vercel.app/



