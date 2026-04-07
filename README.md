Start docker compose: sudo docker compose --env-file .env up -d
Start the backend: npm run dev -w @esp/backend
Start the web: npm run dev -w @esp/web
You can start both at the same time: npm run dev
If you want to check the data in postgres: npx prisma studio