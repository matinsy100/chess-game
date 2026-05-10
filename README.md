# ♟ ChessArena

A real-time multiplayer chess game built with React and Supabase.

## Project Structure

```
chess-game/
├── src/
│   ├── lib/
│   │   └── supabase.js       # Supabase client
│   ├── pages/
│   │   ├── AuthPage.jsx      # Sign in / Sign up
│   │   └── Dashboard.jsx     # Player dashboard
│   └── App.js                # Auth routing
├── .env.example              # Environment variable template
└── package.json
```

## Setup

### 1. Install dependencies
```bash
npm install
```

### 2. Add your Supabase credentials
```bash
cp .env.example .env.local
```
Then open `.env.local` and fill in your Supabase URL and anon key.
Find them at: **Supabase Dashboard → Project Settings → API**

### 3. Enable Email Auth in Supabase
Go to **Supabase Dashboard → Authentication → Providers → Email** and make sure it's enabled.

### 4. Run the app
```bash
npm start
```

## Coming Next
- [ ] Chess board UI
- [ ] Multiplayer matchmaking
- [ ] Real-time game sync via Supabase Realtime
- [ ] ELO rating system
- [ ] Game history
