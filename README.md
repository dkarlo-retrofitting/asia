# asia
Retrofitting Asia
construction-coop-platform/
├── README.md
├── LICENSE
├── .env.example
├── docker-compose.yml
├── package.json
├── pnpm-lock.yaml / yarn.lock / package-lock.json
│
├── client/                         # Frontend (React)
│   ├── public/
│   ├── src/
│   │   ├── assets/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── routes/
│   │   ├── services/              # API calls
│   │   ├── context/               # Auth/user context
│   │   └── App.js
│   └── package.json
│
├── server/                         # Backend (Node.js + Express)
│   ├── src/
│   │   ├── config/                # DB, environment configs
│   │   ├── controllers/
│   │   ├── middleware/
│   │   ├── models/                # Sequelize/Prisma models
│   │   ├── routes/                # API endpoints
│   │   └── app.js
│   ├── tests/
│   └── package.json
│
├── prisma/                         # If using Prisma ORM
│   ├── schema.prisma
│   └── migrations/
│
├── database/                       # SQL dump or seeders
│   ├── init.sql
│   └── seed.sql
│
├── docs/                           # Project documents
│   ├── wireframes/
│   ├── architecture.md
│   └── governance-model.md
│
└── scripts/                        # Utility scripts (e.g., deployment)
    ├── deploy.sh
    └── init-db.sh
