# REST API CRUD with NestJS and Prisma

## Tools

- Visual Studio Code

## Extension Visual Studio Code

- Prettier - Code formatter
- GitLens — Git supercharged

## How to Use

1. Clone this repository
2. Make sure project folder already active at terminal / command line
3. Run `cp .env.example .env` and update database url
4. Run `npm install` to install dependency
5. Run `npx prisma db push` to migrate table
6. Run `npm run start:dev` to run project
7. Happy Hacking

## Endpoint list

| Route      | Method   | Description       |
| ---------- | -------- | ----------------- |
| /tasks     | `GET`    | Get tasks list    |
| /tasks/:id | `GET`    | Get task by ID    |
| /tasks     | `POST`   | Save new task     |
| /tasks/:id | `PATCH`  | Update task by ID |
| /tasks/:id | `DELETE` | Delete task ID    |

## Swagger

| Route    | Method | Description     |
| -------- | ------ | --------------- |
| /openapi | `GET`  | Show swagger UI |
