CraftConnect.ai

CraftConnect.ai is a web platform connecting artisans and craftspeople with clients — built for discovery, communication, and managing craft-based work in one place.

Tech Stack
React 18 + TypeScript
Vite — build tool & dev server
Tailwind CSS — styling
React Router — client-side routing
Supabase — backend, authentication & database
Recharts — data visualization / analytics
Lucide React — icons
Getting Started
Prerequisites
Node.js (v18+ recommended)
npm
Installation
bash
git clone https://github.com/your-username/craftconnect-ai.git
cd craftconnect-ai
npm install
Environment Variables

Create a .env file in the root directory with your Supabase credentials:

VITE_SUPABASE_URL=your_supabase_project_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
Development
bash
npm run dev

The app will be available at http://localhost:5173.

Build
bash
npm run build
Preview Production Build
bash
npm run preview
Linting & Type Checking
bash
npm run lint
npm run typecheck
Project Structure
craftconnect-ai/
├── src/
│   ├── components/     # Reusable UI components
│   ├── pages/           # Route-level pages
│   ├── lib/              # Supabase client, utilities
│   ├── main.tsx
│   └── App.tsx
├── index.html
├── vite.config.ts
├── tailwind.config.js
└── package.json
Contributing
Fork the repository
Create a feature branch (git checkout -b feature/your-feature)
Commit your changes
Push to the branch and open a Pull Request
License

This project is licensed under the MIT License.
