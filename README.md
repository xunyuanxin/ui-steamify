# STEAMIFY - UI

> ✨ React frontend for the STEAMIFY MVP  
> 🌱 Built with Vite + React + Supabase  
> 🎯 Designed for serverless scalability and game embedding via S3


## 🔧 Tech Stack

### Frontend
- [React](https://reactjs.org/)
- [Vite](https://vitejs.dev/)
- [React Router](https://reactrouter.com/)
- [Supabase Auth](https://supabase.com/docs/guides/auth)
### Backend
- [Supabase](https://supabase.io/) - database, RLS, file storage
- [AWS Lambda](https://aws.amazon.com/lambda/) - prompt processing / generating games
- [AWS S3](https://aws.amazon.com/s3/) - hosting games
### DevOps
- [GitHub](https://github.com/)
- [Vercel](https://vercel.com/)


## 🚀 Getting Started

### 1. Clone and install

```bash
git clone https://github.com/xunyuanxin/ui-steamify.git
cd ui-steamify
npm install
```

### 2. Start development

```bash
npm run dev
```

### 3. Open browser
http://localhost:5173/


## 👥 Environment Variables
Create a `.env` file and add:
```env
VITE_SUPABASE_URL=https://aycsqllnzvzvlbiovdqj.supabase.co
VITE_SUPABASE_ANON_KEY={your-anon-key}
```
