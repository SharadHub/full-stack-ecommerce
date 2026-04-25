# E-Commerce

Full-stack e-commerce application

## Stack

- **Frontend**: React, Vite, TailwindCSS, Redux Toolkit, shadcn/ui
- **Backend**: Express, MongoDB, Mongoose


## Project Structure

```
client/
├── src/
│   ├── components/   # Reusable UI components
│   ├── pages/        # Route-level pages (auth, admin, shopping)
│   ├── store/        # Redux store configuration
│   └── lib/          # Utility functions
├── public/
└── package.json

server/
├── server.js         # Express entry point
└── package.json
```

## Getting Started

```bash
# Client
cd client && npm run dev

# Server
cd server && npm run dev
```

