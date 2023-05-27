# Tutorial: Typescript - Next 13 - Prisma - Tailwind

Next 13 uses server components, in this case coupled with prisma to handle sqlite DB

Setup:

- npm create-next-app@latest . (default guided installation)
- npm i prisma -D
- npx prisma init --datasource-provider sqlite (create prisma schema)
- add .env to gitignore
- npx prisma migrate dev --name init
- add dev.db\* into gitignore
- npm run dev
