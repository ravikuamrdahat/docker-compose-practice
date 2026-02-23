# docker-compose-practice


# Docker Compose Practice Lab

This project demonstrates a multi-container application using Docker Compose.

## 🚀 Stack

- Node.js application
- Redis cache
- Nginx (optional)
- Docker Compose orchestration

## 📂 Project Structure

docker-compose-practice/
├── app/
├── docker-compose.yml
├── .env.example
└── README.md


## ⚙️ Prerequisites

- Docker
- Docker Compose v2+

## 🔧 Setup

Clone the repo:

##bash
git clone <your-repo-url>
cd docker-compose-practice

Create enviorment file:

cp .env.example .env


##Star the stack:

docker compose up -d --build


##Verify

http://127.0.0.1:3000

##Stop:

docker compose down
